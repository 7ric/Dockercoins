FROM ruby:2.7-alpine3.12
RUN apk add --update build-base curl
RUN gem install sinatra -v 2.0.8.1 \
    && gem install thin -v 1.7.2
ADD hasher.rb /
CMD ["ruby", "hasher.rb"]
EXPOSE 80
