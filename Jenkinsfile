node('master') {
  
   stage 'Git Checkout'
     git 'https://github.com/SwatiH12345/spring-petclinic.git'
         echo 'checkout done'

   stage('Maven Build'){
      echo 'Maven Project Compile'
     maven 'clean install'      
      post {
          success {
              junit 'target/surefire-reports/**/*.xml' 
          }
   


   stage 'Deploy'
        echo 'Deplyoing Docker Image'

   stage 'Testing'
        echo 'Reporting Getting Creating'

   stage 'Job Status Status'
        echo 'Notification Sending'
}
