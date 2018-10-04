# vuetodoapp
tutorial vuetodoapp with vue cli 3

## Preparation
Please install package below
- Docker for mac
- yarn

## Install
After download this repository
- docker-compose up -d
- docker-compose exec app bash

Inside Container
- vue create app
	- Check what you want config
- cd app
- yarn serve

## if error 'Failed to resolve loader: babel-loader' when yarn serve
[try 'yarn add -D babel-loader'](https://github.com/vuejs/vue-cli/issues/2599)

