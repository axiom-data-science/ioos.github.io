# ioos.github.io
IOOS Documentation Portal.

See website at http://ioos.github.io

## Developer Info: Running Locally

When you clone or pull this repo, make sure to run `git submodule update --init` to update the git submodules.

To run, use one of the options below. After jekyll has started, go to http://localhost:4000 to view the site. As you update pages in the repo, the changes will be automatically reflected.

### Option 1: run Jekyll directly

Follow the quickstart instructions at https://jekyllrb.com/docs/ to install jekyll and serve this site.

### Option 2: Run Jekyll via Docker

```
docker run \
  -v "$PWD:/srv/jekyll" \
  -p 4000:4000 \
  jekyll/jekyll:3.8 \
  jekyll serve
```
