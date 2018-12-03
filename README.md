# gitbucket
Personal docker build from the scala project here:  https://github.com/gitbucket/gitbucket




docker pull gitbucket/gitbucket

docker run -d -p 8080:8080 -p 29418:29418 -v /opt/apps/gitbucket:/gitbucket gitbucket/gitbucket

