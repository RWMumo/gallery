pipeline { 
  agent any
 tools{
	nodejs 'Node-18'
  }
 
  stages { 
    stage('clone repository') {
      steps { 
       sh 'echo "here we will Build"'
      }
    }
     stage('Build the project') {
      steps { 
        sh 'echo "here we will Build"'
      }
    }
stage('Install Dependencies') {
      steps { 
        sh 'echo "install"'
      }
    }
    stage('Tests') {
      steps { 
        sh 'echo "test"'
      }
    }
	stage('Deploy Application') {
      steps {
             sh 'echo "deploy"'
              }
    }
  }
}