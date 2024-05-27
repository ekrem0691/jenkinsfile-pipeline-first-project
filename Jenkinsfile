pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Compiling the java source code'
                sh 'javac Hello.java'
            }
        }
        stage('run') {
            steps {
                echo 'Running the compiled java code.'
                sh 'java Hello'
            }
        }
    }
}



// pipeline {
//     agent any
//     stages {
//         stage('build') {
//             steps {
//                 echo "Clarusway_Way to Reinvent Yourself"
//                 sh 'echo using shell within Jenkinsfile'
//                 echo 'not using shell in the Jenkinsfile'
//             }
//         }
//         stage('test') {
//             steps {
               
//                 sh 'touch deneme.txt'
          
//             }
//         }
//         stage('deploy') {
//             steps {
               
//                 sh 'echo  "hello" > deneme2.txt '
          
//             }
//         }
//     }
// }