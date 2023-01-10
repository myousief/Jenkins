node {
    
    stage('Git Checkout'){
        git 'https://github.com/myousief/Jenkins.git'
    }
    stage ('send file to ansible'){
        sshagent(['ansible']) {
            sh 'ssh master'
        }
    }
}
