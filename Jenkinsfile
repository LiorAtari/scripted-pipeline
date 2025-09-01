@Library ('my-shared-lib') _
node {
    stage ("Checkout code") {
        git branch: 'main', url: 'https://github.com/LiorAtari/scripted-pipeline.git'
    }
    stage ('Installing Dependencies') {
            sh 'npm install'
        }

    stage ("Printing hello") {
        printingHello 'Lior Atari'
    }
    // stage ('Run tests') {
    //         sh 'npm test'
    // }
    stage ('Finished') {
        echo 'Pipeline finished successfully'
    }
}
