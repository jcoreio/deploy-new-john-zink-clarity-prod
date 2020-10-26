# @jcoreio/deploy-new-john-zink-clarity-prod

This is the repo for the new John Zink clarity deployment.

All it contains is a dependency on the desired version of `@jcoreio/deploy-clarity`
(which controls which version of clarity gets deployed) and a `deploy-clarity-config.js`
which just has a pointer to the deploy config in S3.

I'd recommend adding `./node_modules/.bin` to your `PATH` so that in this directory
you can run the `deploy-clarity` CLI commands for working with the production deployment.
