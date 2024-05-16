node{
    stage('SCM Checkout') {
           git 'https://github.com/sarahjonna/spring-boot-data-jpa-mysql-master'
        }
         stage('Compile-Package') {
          sh 'mvn package'
        }
       
}
