node {
    stage('git clone') {
        git 'https://github.com/diamatemarcus/jenkinsTest.git'
    }
    stage('Test') {
        echo 'Testing....'
    }
    stage('execute sh') {
		sh "chmod 774 ./project.sh"
        sh "./project.sh"
    }
}
