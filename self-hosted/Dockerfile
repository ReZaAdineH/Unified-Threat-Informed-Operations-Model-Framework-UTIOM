FROM nginx:1.30.4-alpine

LABEL org.opencontainers.image.title="UTIOM Assessment Toolkit"
LABEL org.opencontainers.image.description="Self-hosted maturity, capability and metrics tools for the Unified Threat-Informed Operations Model"
LABEL org.opencontainers.image.url="https://utiom.de"
LABEL org.opencontainers.image.source="https://utiom.de"
LABEL org.opencontainers.image.licenses="PolyForm-Internal-Use-1.0.0"
LABEL org.opencontainers.image.authors="Reza Adineh"
LABEL org.opencontainers.image.version="1.4"
LABEL org.opencontainers.image.vendor="UTIOM"
LABEL org.opencontainers.image.documentation="https://utiom.de"

RUN rm -rf /usr/share/nginx/html/*

COPY nginx.conf /etc/nginx/conf.d/default.conf
COPY site/ /usr/share/nginx/html/

RUN chown -R nginx:nginx /usr/share/nginx/html && \
    chmod -R 444 /usr/share/nginx/html/*.html && \
    chmod 555 /usr/share/nginx/html && \
    touch /var/run/nginx.pid && \
    chown -R nginx:nginx /var/run/nginx.pid /var/cache/nginx /var/log/nginx

EXPOSE 8080

HEALTHCHECK --interval=30s --timeout=3s --start-period=5s --retries=3 \
  CMD wget --quiet --tries=1 --spider http://127.0.0.1:8080/ || exit 1

USER nginx

CMD ["nginx", "-g", "daemon off;"]
