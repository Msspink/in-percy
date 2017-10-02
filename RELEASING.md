# Releasing

1. `git checkout master`
1. `git pull origin master`
1. `npm version x.x.x` 
1. `git push`
1. `git push --tags`
1. Ensure tests have passed on that tag
1. Draft and publish a [new release on github](https://github.com/percy/in-percy/releases)
1. `npm publish`
1. [Visit NPM](https://www.npmjs.com/package/@percy-io/in-percy) and see that your version is now live.
