FROM nginx
ARG TZ
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone

COPY ./default.conf /etc/nginx/conf.d/default.conf
