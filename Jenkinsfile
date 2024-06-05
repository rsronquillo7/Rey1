pipeline{
        agent any
        stages{
            stage('Make Directory'){
                steps{
                    sh "mkdir ~/jenkins-tutorial1"
                }
            }
            stage('Make Files'){
                steps{
                    sh "touch ~/jenkins-tutorial1/file1 ~/jenkins-tutorial1/file2"
                }
            }
        }
}
