pipeline{
    agent any
    stages{
        
    stage('SCM Checkout'){
        steps{
        git 'https://github.com/Hitais/my-app'
        }
    }
    satge('Compile Package'){
        steps{
            
        def mvnHome = tool name: 'default', type: 'maven'
        sh "${mvnHome}/bin/mvn package"
        }
    }
    }
}
