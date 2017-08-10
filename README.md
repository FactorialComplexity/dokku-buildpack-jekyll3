This is a dokku buildpack for installing Jekyll 3. It only complies Jekyll sitae and doesn't start any server. You will need another buildpack just for that. [dokku/buildpack-nginx](https://github.com/dokku/buildpack-nginx) will work.

Tested with:
- `dokku 0.10.3` and `jekyll-3.4.3`

### Credit

It is based on: [inket/dokku-buildpack-jekyll3-nginx](https://github.com/inket/dokku-buildpack-jekyll3-nginx).