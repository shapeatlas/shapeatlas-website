# Shape Atlas Website

Hugo theme and content for shapeatlas.com. Images are copyright Roman Bejnar.

## Run local server

`hugo server -D` to run a local server including drafts.

## Production Build

To run in production (e.g. to have Google Analytics show up), run `HUGO_ENV=production` before your build command. For example:

```
HUGO_ENV=production hugo
```

# Deployment to S3 and Cloudfront

See: [s3deploy](https://github.com/bep/s3deploy)