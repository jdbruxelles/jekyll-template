# Jekyll basic template


## Installation

If you don't have a full Jekyll environment installed, please follow these steps:

1. Install a full [Ruby development environment](https://jekyllrb.com/docs/installation/)

2. Install [Jekyll](https://jekyllrb.com/docs/ruby-101/#bundler) and [Bundler](https://jekyllrb.com/docs/ruby-101/#gems)

```
gem install jekyll bundler
```

3. Install dependencies from Gemfile:

```
bundle install
```

4. Build the site and make it available on a local server

```
bundle exec jekyll serve
```

You should see something like:
```
Configuration file: /PROJECT_NAME/_config.yml
            Source: .
       Destination: ./_site
 Incremental build: disabled. Enable with --incremental
      Generating...
                    done in 2.633 seconds.
 Auto-regeneration: enabled for '.'
    Server address: http://127.0.0.1:4000
  Server running... press ctrl-c to stop.
```

5. Now browse to [http://localhost:4000](http://localhost:4000).

See the [Jekyll documentation](https://jekyllrb.com/docs/) for more.