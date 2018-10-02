# Run local server

`hugo server -D` to run a local server including drafts.

## Production

To run in production (e.g. to have Google Analytics show up), run `HUGO_ENV=production` before your build command. For example:

```
HUGO_ENV=production hugo
```

# Deployment to Github Page

See: https://gohugo.io/hosting-and-deployment/hosting-on-github/

Press Ctrl+C to kill the server
`rm -rf public` to completely remove the public directory

You can then run `./deploy.sh` "Your optional commit message" to send changes to <USERNAME>.github.io. Note that you likely will want to commit changes to your <YOUR-PROJECT> repository as well.

That’s it! Your personal page should be up and running at https://<USERNAME>.github.io within a couple minutes.