# docker-packages
Personal docker packages registry

# 1) 🚀 PHP

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

#### 1.1) Usage

#### Pull image from the command line: 
`docker pull docker.pkg.github.com/samirmh-dev/docker-packages/php:version_tag` 

#### Use as base image in DockerFile: 
`FROM docker.pkg.github.com/samirmh-dev/docker-packages/php:version_tag`

#### Use as image in docker-compose.yml
`image: docker.pkg.github.com/samirmh-dev/docker-packages/php:version_tag`

#### Example: 
`FROM docker.pkg.github.com/samirmh-dev/docker-packages/php:7.3.13-fpm-buster`

#### 1.2) Pspell dictionaries

- [x] All default pspell dictionaries. Additional dictionaries included:
- [x] `Azerbaijan` dictionary for pspell

#### 1.3) XDebug installation docs
###### coming soon
<br>
## More coming ...


##### Feel free to create issues, pull requests, feature requests and etc.
