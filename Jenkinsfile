pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World';
            }
        }
        
        stage('Junit'){
            steps {
                echo "Junit passed successfully!";
            }
        }
        
        stage("build"){
            steps{
                echo "build.sh!";
            }
        }
        
        
        stage('Last Step'){
            steps {
                echo "Last step passed successfully!";
            }
        }
        
        
    }
}
