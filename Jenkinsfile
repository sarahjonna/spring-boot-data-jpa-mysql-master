pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', 
                    url: 'https://github.com/sarahjonna/spring-boot-data-jpa-mysql-master'
            }
        }
         stage('Compile-Package') {
          sh 'mvn package'
        }
    }
}
