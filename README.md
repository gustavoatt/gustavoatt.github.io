# gustavoatt.github.io

This is my personal blog. I will post about my projects, thoughts and experiences.

## Setup

To run this project locally, you need to have [Ruby](https://www.ruby-lang.org/en/) 
and [Jekyll](https://jekyllrb.com/) installed. We recommend using [RVM](https://rvm.io/)
to manage your Ruby versions first and then install everything else using `bundler`.

```bash
# Install ruby 2.7.7 with a custom openssl dir
rvm install ruby-2.7.7 --with-openssl-dir=/opt/homebrew/opt/openssl@1.1/


bundle install
bundle exec jekyll serve
```

Then, open your browser and go to `http://localhost:4000`.
