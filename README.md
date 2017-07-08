# Tips
My tips. Because I'm lazy to type it again

## Use NVM

Use [nvm](https://github.com/creationix/nvm) to manage node versions.

Quick usuage:

- Install NVM: https://github.com/creationix/nvm#install-script
- Install Node 8: `nvm install 8`
- Alias Node 8 as default `nvm alias default 8`
- Move global packages from one version to another: `// TODO`

## Avoid `sudo` to install global packages

Because it breaks stuff for everyone using it. 
See [this guide](https://github.com/sindresorhus/guides/blob/master/npm-global-without-sudo.md) for how to configure it manually or just use nvm
