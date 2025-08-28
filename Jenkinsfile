#    stage('Clone') {
#	git 'https://github.com/Wizhb/project-alphorm.git'
 #   }
  #  stage('Build') { 
   #     sh 'javac Main.java'
#    }
#    stage('Run') {
#    sh 'java Main'
#    }
node {
    stage('Clone') {
        git branch: 'main', url: 'https://github.com/Wizhb/project-alphorm.git'
    }

    stage('Build and Run') {
        sh '''
            javac Main.java
            java Main
        '''
    }
}

