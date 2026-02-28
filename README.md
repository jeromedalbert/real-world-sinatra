# Real World Sinatra

> Real World Sinatra apps and their open source codebases for developers to learn from

Learn from Sinatra apps written by experienced developers.

You'll find the source code for the Real World Sinatra apps in the
[`apps/`](apps/) subdirectory.

Thank you to every developer who has worked on a project this repo links to,
your work is helping developers learn Sinatra.

## How to install on your computer

```bash
# Clone this git repo:
git clone git@github.com:jeromedalbert/real-world-sinatra.git

cd real-world-sinatra/

# The apps are linked to as git submodules.
# This will take some time...
git submodule update --init --single-branch --jobs 4
```

## Other Real World Codebase Collections

- Real World Rails https://github.com/eliotsykes/real-world-rails
- Real World Ruby Apps https://github.com/jeromedalbert/real-world-ruby-apps
- Real World Ember https://github.com/eliotsykes/real-world-ember
- Real World Django https://github.com/ckrybus/real-world-django
- Real World Phoenix https://github.com/szTheory/real-world-phoenix
- Know any others? Please open a PR and add the link here

## Information for Contributors

#### How to add a Real World App

Given a GitHub repo for an app `githubuser/foo`:

```bash
# Inside the project root:
git submodule add -b master git@github.com:githubuser/foo.git apps/foo
```

#### Updating the apps submodules to latest

The apps in `apps/` are git submodules. Git submodules are locked to a revision
and don't stay in sync with the latest revision.

To update the revisions, run:

```bash
# This will take some time:
git submodule update --remote --single-branch --jobs 4
```

---

# Contributors

- Jerome Dalbert https://jeromedalbert.com
- Contributions are welcome, fork the GitHub repo, make your changes, then
  submit your pull request! Reach out if you'd like some help.
