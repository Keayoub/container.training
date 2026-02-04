FROM ruby:4.0.1-trixie
RUN gem install fluentd
RUN gem install fluent-plugin-elasticsearch
COPY fluentd.conf /fluentd.conf
CMD ["fluentd", "-c", "/fluentd.conf"]
