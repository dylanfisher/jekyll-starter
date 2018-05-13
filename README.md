# Jekyll Starter

## Installation

Clone this app into your new project:

`git clone git@github.com:dylanfisher/jekyll-starter.git my-new-project`

Re-initialize the git repo:

```
cd ~/projects/my-new-project
rm -rf .git
git init
git add -A
git commit -m "first commit"
```

## Developing

Install Ruby according to `.ruby-version` (rbenv recommended to do this).

Install gems:

`bundle install`

This installation of Jekyll uses `guard-livereload` to compile changes as they are made.

To start the Jekyll server and watch for changes, run:

`bundle exec guard`
