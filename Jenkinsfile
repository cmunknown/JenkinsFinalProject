pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    echo 'Build'
                    bat 'mvn compile'
                }
            } 
        }
        stage('Test') {
            steps {
                script {
                    echo 'Test'
                    bat 'mvn test'
                }
            }            
        }
//         stage('Package') {
//             steps {
//                 script {
//                 sh 'mvn package -Dmaven.test.skip'
//                     echo 'Package'
//                 }
//             }            
//         }
//         stage('Build Docker image') {
//             steps {
//                 script {
//                 sh 'docker build -t app .'
//                     echo 'Build Docker image'
//                 }
//             }            
//         }
//         stage('Push'){
//             steps {
//                 script {
//                     echo 'Push'
//                 }
//             }            
//         }
//         stage('Run local'){
//             steps {
//                 script {
//                     sh 'docker run -d -p 8060:8086 app'
//                 }
//             }            
//         }
//     }
}

// pipeline {
//     agent any
//     stages {
//         stage('Build') {
//             steps {
//                 script {
//                     echo 'Build'
//                     sh 'mvn compile'
//                 }
//             } 
//         }
//         stage('Test') {
//             steps {
//                 script {
//                     echo 'Test'
//                     sh 'mvn test'
//                 }
//             }            
//         }
//         stage('Package') {
//             steps {
//                 script {
//                 sh 'mvn package -Dmaven.test.skip'
//                     echo 'Package'
//                 }
//             }            
//         }
//         stage('Build Docker image') {
//             steps {
//                 script {
//                 sh 'docker build -t app .'
//                     echo 'Build Docker image'
//                 }
//             }            
//         }
//         stage('Push'){
//             steps {
//                 script {
//                     echo 'Push'
//                 }
//             }            
//         }
//         stage('Run local'){
//             steps {
//                 script {
//                     sh 'docker run -d -p 8060:8086 app'
//                 }
//             }            
//         }
//     }
// }
