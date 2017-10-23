# heroku-buildpack-copy-samples
Heroku buildpack provides ability to copy .yml.sample config files in your rails projects.

### Installation

The key have to be stored in the application's env:
```bash
heroku config:set COPY_SAMPLE_FILE_TEMPLATE="yml.sample"
```

Then you have to install this buildpack on your app:
```bash
heroku buildpacks:add -i 1 https://github.com/spirosure/heroku-buildpack-copy-samples.git
```

Or you can read [Instructions](https://devcenter.heroku.com/articles/platform-api-reference#buildpack-installations)
