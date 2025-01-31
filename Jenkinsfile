pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                git branch: 'main', url: 'https://github.com/DeeptiSingh2409/Jenkins_bash.git'
            }
        }
        stage('Running Script') {
            steps {
                sh 'chmod +x system_admin.sh'
                sh './linuxcommands_sh'
            }
        }
    }
}
