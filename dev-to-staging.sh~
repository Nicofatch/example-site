#!/bin/sh
git commit -am $1
git push origin develop
git checkout staging
git merge develop
git push origin staging
git push staging-heroku staging:master
