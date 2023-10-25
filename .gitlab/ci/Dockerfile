ARG PHP_VERSION=8.1
ARG VARIANT=wordpress-web
ARG IMAGE_SUFFIX=debian-bullseye-rootless
FROM rewardenv/php-fpm:${PHP_VERSION}-${VARIANT}-${IMAGE_SUFFIX}

USER www-data

COPY --chown=www-data:www-data . .
