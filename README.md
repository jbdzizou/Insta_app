###### tags: `Rails` `Docker`
# Rails Instagram app


## Description
Rails Instagram-like application

## Version
Docker version 19.03.2  
Docker-compose version 1.24.1  
Rails 5.2.3  
ruby 2.6.3  
mysql 5.7  

## Getting started
1.git pull files  
```
$ git clone git@github.com:jbdzizou/  
$ cd 
```
2.container build  
`$ docker-compose up -d`

3.Command to execute DB creation task in Rails container  
`$ docker-compose run web rake db:create`

If the database already exists,Enter the following command  
`$ docker-compose run web rails db:migrate`

4.login to localhost(your chrome or etc)  
http://localhost:3000 or http://address:3000

## ADD GEM

- bootstrap-sass
- simple_for
- haml
- devise
- paperclip
- masonry-rails
- acts_as_votable

