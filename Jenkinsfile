// pipeline {
//     agent {
//         label 'ansible'
//     }
//     stages {
//         stage('Hello') {
//             steps {
//                 echo 'Hello world'
//             }
//         }
//         stage('Hello1'){
//             steps {
//                 echo 'Hello world'
//             }
//         }
//         stage('Hello2'){
//             steps{
//                 echo 'Hello world'
//                 mail bcc: '', body: 'hello this is a test email', cc: '', from: '', replyTo: '', subject: 'test', to: 'nvrnagella@gmail.com'
//             }
//         }
//     }
//     post {
//         always {
//             echo "sending email"
//         }
//     }
// }
@Library('roboshop') _

pipeline{
    agent any
    stages{
        stage('test'){
            steps{
                def abc = "Hello"
                def xyz = 10

                print "abc = ${abc}"
                print "xyz = ${xyz}"

                print abc
            }
        }
    }
}