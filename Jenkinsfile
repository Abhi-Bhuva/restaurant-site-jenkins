pipeline{
    agent {label "abhi"}
    stages{
        stage("code"){
            steps{
                 echo "code is cloning"
                 git url:"https://github.com/Abhi-Bhuva/restaurant-site-jenkins.git",branch:"main"
                 echo "code successfull"
            }
        }
        stage("build"){
            steps{
                 echo "code is build"
            }
        }
        stage("test"){
            steps{
                 echo "code is testing"
            }
        }
        stage("deploy"){
            steps{
                 echo "code is deploy"
            }
        }
    }
}
