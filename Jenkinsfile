pipeline{
        agent any
        stages{
            stage('Make Directory'){
                steps{
                    sh "mkdir -p /jenkins-tutorial-test"
                }
            }
            stage('Make Files'){
                steps{
                    sh "touch /jenkins-tutorial-test/file1"
                    sh "touch /jenkins-tutorial-test/file2"
                }
            }
        }
}
