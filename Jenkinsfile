pipeline { 
  agent any
 tools{
	nodejs 'Node-18'
  }
 
  stages { 
    stage('clone repository') {
      steps { 
       git 'https://github.com/RWMumo/gallery.git'
      }
    }
     stage('Build the project') {
      steps { 
        sh 'echo "here we will Build"'
      }
    }
stage('Install Dependencies') {
      steps { 
        sh 'npm install'
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