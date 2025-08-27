pipeline {
    agent any

    environment {
        APP_SERVER = "appnode"
        SSH_KEY = "/home/ubuntu/vishal_new.pem"
    }

    stages {
        stage('Checkout Code') {
            steps {
                git branch: 'main', url: 'pipeline {
    agent any

    environment {
        APP_SERVER = "appnode"
        SSH_KEY = "/home/ubuntu/Vishal-key.pem"
    }

    stages {
        stage('Checkout Code') {
            steps {
                git branch: 'main', url: 'https://github.com/Vishal/your-repo-name.git'
            }
        }

        stage('Build & Package') {
            steps {
                sh 'mvn clean package'
            }
        }

        stage('Deploy to Tomcat') {
            steps {
                ansiblePlaybook(
                    playbook: 'ansible/playbooks/deploy_app.yml',
                    inventory: 'ansible/inventories/hosts.ini'
                )
            }
        }
    }
}
'
            }
        }

        stage('Build & Package') {
            steps {
                sh 'mvn clean package'
            }
        }

        stage('Deploy to Tomcat') {
            steps {
                ansiblePlaybook(
                    playbook: 'ansible/playbooks/deploy_app.yml',
                    inventory: 'ansible/inventories/hosts.ini'
                )
            }
        }
    }
}
