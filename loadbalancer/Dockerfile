FROM nginx:1

COPY ./vote.conf.template /etc/nginx/templates/vote.conf.template

ENV PORT=8080 \
    VOTE_HOST=localhost \
    VOTE_PORT=8088 \
    RESULT_HOST=localhost \
    RESULT_PORT=8888
