FROM ruby:2.6.0

RUN apt-get update && apt-get install -y nodejs git
RUN git clone https://github.com/docker-hy/rails-example-project.git
WORKDIR rails-example-project
RUN gem install bundler
RUN bundle install
RUN rails db:migrate


EXPOSE 3000

ENTRYPOINT [ "rails", "s" ]