# npm-consumer-test

This consumes my private package @saschb2b/npm-package-test

.npmrc redirects all packages from @saschb2b to https://npm.pkg.github.com

As this repository is private we need to login before installing the dependencies

`npm login --registry=https://npm.pkg.github.com` and enter your credentials (This method gets deprecated soon)


If you are using a second factor you need a personal access token in replacement of the password
https://docs.github.com/en/github/authenticating-to-github/accessing-github-using-two-factor-authentication#using-two-factor-authentication-with-the-command-line

