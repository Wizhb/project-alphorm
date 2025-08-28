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

