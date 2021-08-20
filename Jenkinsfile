node{
    stage('SCM Checkout'){
        git 'https://github.com/Hitais/my-app.git'
    }
    satge('Compile Package'){
        def mvnHome = tool name: 'default', type: 'maven'
        sh "${mvnHome}/bin/mvn package"
    }
}
