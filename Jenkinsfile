node{
    stage('SCM Checkout'){
        git 'https://github.com/Hitais/my-app'
    }
    satge('Compile Package'){
        def mvnHome = tool name: 'default', type: 'maven'
        sh "${mvnHome}/bin/mvn package"
    }
}
