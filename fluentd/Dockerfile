FROM fluentd:v1.9-1
USER root
RUN ["gem", "install", "fluent-plugin-elasticsearch"]
#USER fluent

# 构建
# docker build -f fluentd/Dockerfile -t fluentd:v1.9-1.1 .