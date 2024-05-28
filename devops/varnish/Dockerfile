# syntax=docker/dockerfile:1
FROM varnish:7.4

LABEL maintainer="liciob <liciob@gmail.com>" \
      org.label-schema.name="trems-varnish" \
      org.label-schema.description="Treinamento TRE-MS Varnish image." \
      org.label-schema.vendor="liciob"

COPY etc/varnish.vcl /etc/varnish/default.vcl
