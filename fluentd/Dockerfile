# fluentd/Dockerfile
#FROM fluent/fluentd:v0.12-debian
FROM fluent/fluentd:v1.8-1
USER root


#RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-rdoc", "--no-ri", "--version", "1.18.2"]
#RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-rdoc", "--no-ri", "--version", "1.18.2"]
RUN ["gem", "install", "fluent-plugin-elasticsearch"]
RUN ["gem", "install", "fluent-plugin-multi-format-parser"]
