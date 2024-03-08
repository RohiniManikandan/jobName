pipeline{
    agent any
    stages{
        stage('Compile'){
            steps{
                bat '''javac Sample.java
                java Sample.java'''
            }
        }
    }
}
