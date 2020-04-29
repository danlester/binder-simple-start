

repo2docker --user-name jovyan --user-id 1000 --volume /Users/dan/Dev/binder-simple-start:/home/jovyan --publish-all --debug /Users/dan/Dev/binder-simple-start



repo2docker --volume /Users/dan/Dev/binder-simple-start:/home/jovyan --debug /Users/dan/Dev/binder-simple-start



docker run -v /Users/dan/Dev/binder-simple-start:/home/jovyan -p 8888:8888 --rm r2d-2fusers-2fdan-2fdev-2fbinder-2dsimple-2dstart1588176851:latest


