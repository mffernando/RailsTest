# Quick Installation Guide

Installing the Ruby on Rails on Ubuntu 16.04 (Xenial Xerus).

## Ruby Installation (as sudo user (root)):
sudo apt-get update

sudo apt-get upgrade -y

sudo apt-get install build-essential patch ruby-dev zlib1g-dev liblzma-dev libsqlite3-dev

## Django Installation:
sudo gem install rails -v 5.0.0.1

## Check Ruby and Rails version:
ruby -v

rails -v

## Node.js Installation:
sudo apt-get install nodejs

## Create new project:
rails new ruby_on_rails_project_name

## Run project:
cd ruby_on_rails_project_name

rails s

## Test in the browser:
localhost:3000

##

If the message 'Yay! You’re on Rails!' Ruby on Rails installation is ok.

