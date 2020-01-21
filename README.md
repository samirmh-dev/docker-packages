# docker-packages
Personal docker packages registry

### 1) 🚀 PHP

Version tags: **latest**, **7.3.13-fpm-buster**

#### What included?

- [x] PHP version 7.3.13
- [x] All locale files
- [x] All default extensions included. Additional extensions included:
- [x] `zip`, `unzip`, `vim` packages
- [x] `pgsql` extension
- [x] `mbstring` extension
- [x] `zip` extension
- [x] `exif` extension
- [x] `pcntl` extension
- [x] `pdo_pgsql` extension
- [x] `pspell` extension
- [x] `gd` extension
- [x] `imagick` extension
- [x] `pspell` extension
- [ ] `xdebug` extension

#### Pspell dictionaries

- [x] All default pspell dictionaries. Additional dictionaries included:
- [x] `Azerbaijan` dictionary for pspell

#### Pull image from the command line: 
`docker pull docker.pkg.github.com/samirmh-dev/docker-packages/php:version_tag` 

#### Use as base image in DockerFile: 
`FROM docker.pkg.github.com/samirmh-dev/docker-packages/php:version_tag`

#### Example: 
`FROM docker.pkg.github.com/samirmh-dev/docker-packages/php:7.3.13-fpm-buster`

#### XDebug installation docs
###### coming soon

## More coming ...


# Feel free to create issues, pull requests, feature requests and etc.
