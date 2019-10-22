### jenkins起動(Docker)
`docker run -p 8080:8080 -p 50000:50000 jenkins/jenkins:lts`

### マウントしつつ、jenkins起動(Docker)
`docker run -d -v `pwd`/jenkins_home:/var/jenkins_home -p 8080:8080 -p 50000:50000 jenkins/jenkins:lts`


### マウントしつつ、ポートを10080に変更しつつ、jenkins起動(Docker)
`docker run -d -v `pwd`/jenkins_home:/var/jenkins_home -p 10080:8080 -p 50000:50000 jenkins/jenkins:lts`
