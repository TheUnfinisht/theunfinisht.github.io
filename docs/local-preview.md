# Local Preview

This site is built by GitHub Pages using Jekyll and the Minima theme.

Local preview requires Ruby and Bundler. On macOS, the recommended path is to use a user-managed Ruby instead of the system Ruby, because system Ruby is often old and can make gem installation harder.

Use a modern Ruby 3.x when possible. The macOS system Ruby 2.6 line may fail when resolving current GitHub Pages dependencies.

Common user-managed Ruby options include:

- Homebrew Ruby
- rbenv
- chruby
- asdf

Python and pyenv are not relevant for this Jekyll preview workflow.

## Commands

Install the Ruby gems:

```bash
bundle install
```

Start the local preview server:

```bash
bundle exec jekyll serve
```

Then open:

```text
http://localhost:4000
```

### Local build artifacts

Jekyll and Bundler may create local-only files such as `_site/`, `.jekyll-cache/`, `.sass-cache/`, `.jekyll-metadata`, `.bundle/`, or `vendor/bundle/`. These should not be committed.

## Troubleshooting

If `bundle exec jekyll serve` cannot find Jekyll, run `bundle install` first.

If system Ruby causes install or build issues, install a modern user-managed Ruby and rerun `bundle install`.
