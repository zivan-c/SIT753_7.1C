pipeline {
    //test for commit
    //test for another commit
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Task: Compile and package the code.'
                echo 'Tool: Maven'
            }
        }
        stage('Unit and Integration Tests') {
            steps {
                echo 'Task: Run unit and integration tests to ensure components work together.'
                echo 'Tool: JUnit and Selenium'
            }
        }
        stage('Code Analysis') {
            steps {
                echo 'Task: Analyze code to ensure it meets industry standards.'
                echo 'Tool: SonarQube'
            }
        }
        stage('Security Scan') {
            steps {
                echo 'Task: Perform a security scan to identify vulnerabilities.'
                echo 'Tool: OWASP ZAP'
            }
        }
        stage('Deploy to Staging') {
            steps {
                echo 'Task: Deploy the application to a staging server.'
                echo 'Tool: AWS CodeDeploy (EC2)'
            }
        }
        stage('Integration Tests on Staging') {
            steps {
                echo 'Task: Run integration tests on the staging environment.'
                echo 'Tool: Cypress'
            }
        }
        stage('Deploy to Production') {
            steps {
                echo 'Task: Deploy the application to a production server.'
                echo 'Tool: AWS CodeDeploy (EC2)'
            }
        }
    }
}