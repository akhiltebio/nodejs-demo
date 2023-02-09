pipeline{
    agent any 
    stages{
        stage('chickout'){
            steps{
            git 'https://github.com/akhiltebio/nodejs-demo.git'
            }
        }
        stage('build'){
            steps{
                nodejs(nodeJSInstallationName :'Nodejs'){
                    sh 'npm install'
                }
            }
        }
    }
}
