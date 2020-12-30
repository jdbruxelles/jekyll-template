# Jekyll basic template

## Installation
- [Use directly in a new repository](https://github.com/rboot-dev/jekyll-template/generate)
- [Download the zip](https://github.com/rboot-dev/jekyll-template/archive/main.zip)
- Clone using [Git](https://git-scm.com/):
  ````
  $ git clone https://github.com/rboot-dev/jekyll-template.git
  ````
- Clone using [GitHub CLI](https://cli.github.com/):
  ````
  $ gh repo clone rboot-dev/jekyll-template
  ````
https://github.com/rboot-dev/jekyll-template/generate
## Run locally

If you have a full Jekyll environment installed, you can skip to the step 3:

1. Install a full [Ruby development environment](https://jekyllrb.com/docs/installation/)

2. Install [Jekyll](https://jekyllrb.com/docs/ruby-101/#bundler) and [Bundler](https://jekyllrb.com/docs/ruby-101/#gems)

```
gem install jekyll bundler
```

3. Install dependencies from Gemfile

```
bundle install
```

4. Replace the sample data with your data in the `_config.yml` file.

5. Build the site and make it available on a local server

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

## More about Jekyll
See the [Jekyll documentation](https://jekyllrb.com/docs/) for more.