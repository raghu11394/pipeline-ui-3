pipeline {
  agent any
  tools {
    maven "Maven"
  }
  stages {
      stage("build") {
          steps {
            echo 'build ....'
              snDevOpsStep()
   		sleep 10
          }
      }
      stage("test") {
           steps {
             echo 'test .....'
                snDevOpsStep()
  		sleep 10
           }
       }
      stage("deploy") {
          steps {
            echo 'Deploying..'
            snDevOpsStep()
		sleep 10
          }
      }
  }
}