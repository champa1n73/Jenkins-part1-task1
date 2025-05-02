pipeline {
    agent any 


    stages{
        stage('Build'){
            steps{
                echo "==================== Stage 1: Build ===================="
                echo "Building the project using Maven..."
            }
        }

        stage('Unit and Integration Tests'){
            steps{
                echo "==================== Stage 2: Unit and Integration Tests ===================="
                echo "Running unit tests with JUnit..."
                echo "Running integration tests..."
            }
        }

        stage('Code Analysis'){
            steps{
                echo "==================== Stage 3: Code Analysis ===================="
                echo "Analyzing code with SonarQube via Jenkins..."
            }
        }

        stage('Security Scan'){
            steps{
                echo "==================== Stage 4: Security Scan ===================="
                echo "Scanning code for vulnerabilities using OWASP ZAP..."
            }
        }

        stage('Deploy to Staging'){
            steps{
                echo "==================== Stage 5: Deploy to Staging ===================="
                echo "Deploying application to staging server (AWS EC2)..."
            }
        }

        stage('Integration Tests on Staging'){
            steps{
                echo "==================== Stage 6: Integration Tests on Staging ===================="
                echo "Running integration tests on staging environment..."
            }
        }

        stage('Deploy to Production'){
            steps{
                echo "==================== Stage 7: Deploy to Production ===================="
                echo "Deploying application to production server (AWS EC2)..."
            }
        }
    }
}
//hello
