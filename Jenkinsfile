pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "hello"
            }
        }
        
        stage('cat README'){
            when{
                branch "fix-*"
            }
            steps{
                echo "README"
            }
        }
    }
}
