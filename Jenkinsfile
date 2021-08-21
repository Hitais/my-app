pipeline{
    agent any
    stages{
        
    stage('SCM Checkout'){
        step{
        git 'https://github.com/Hitais/my-app'
        }
    }
    satge('Compile Package'){
        step{
            
        def mvnHome = tool name: 'default', type: 'maven'
        sh "${mvnHome}/bin/mvn package"
        }
    }
    }
}
