pipeline {
    agent any


    stages {
        stage('TERRAFORM : CREATE INFRA') {
            steps {
                echo 'CREATE INFRA.'
                echo 'Initializing Terraform...'
                echo 'Planning Terraform...'
                echo 'Applying Terraform...'
                sh 'env'
            }
        }
        stage('ANSIBLE : CONFIG  INFRA') {
            steps {
                echo 'CONFIG INFRA.'
                echo 'Generate the config file...'
                echo 'Execute the playbook...'
                echo 'Safe in the S3 Bucket Terraform files...'
                sh 'pwd'
            }
        }
 

 

        
    }
}
