docker run --name focused_nobel  -p 8081:8080 -p 50003:50000  -v /var/jenkins_home:/var/jenkins_home -v /root/maven/apache-maven-3.6.0:/var/maven_home  -v /android_sdk:/var/android_sdk  jenkinszbj
