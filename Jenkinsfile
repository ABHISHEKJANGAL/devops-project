pipeline {
    agent any
    stages {
        stage('Clone Repo') {
            steps {
                git branch: 'main', url: 'https://github.com/ABHISHEKJANGAL/devops-project.git'
            }
        }
        stage('Run Ansible Setup') {
            steps {
                sh 'ansible-playbook setup.yml'
            }
        }
        stage('Build Vehicle Service') {
            steps {
                dir('vehicle-service') {
                    sh 'echo "Build step placeholder"'
                }
            }
        }
    }
}
