pipeline {
    agent any
    stages {
        stage('Clone Project') {
            steps {
                git url: 'https://github.com/ABHISHEKJANGAL/devops-project.git', branch: 'main'
            }
        }
        stage('Run Ansible Playbook') {
            steps {
                sh 'ansible-playbook setup.yml'
            }
        }
    }
}
