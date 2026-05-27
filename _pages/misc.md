---
title: ""
permalink: /misc/
author_profile: true
---

## Setup Local Website Preview

- Install Ruby + Bundler + Jekyll: macOS (Homebrew)
```
brew install ruby
echo 'export PATH="/opt/homebrew/opt/ruby/bin:$PATH"' >> ~/.zshrc && source ~/.zshrc
gem install bundler jekyll
```
- From site folder (where `Gemfile` lives)
```
bundle install
bundle exec jekyll serve --livereload --baseurl ""
```
- Open prevew
```
http://localhost:4000/
```

## Vibe Coding Projects

- 2048 Learner on Google AI Studio: 
[https://ai.studio/apps/731372fa-cd52-4022-b039-469d4215c568?fullscreenApplet=true](https://ai.studio/apps/731372fa-cd52-4022-b039-469d4215c568?fullscreenApplet=true)