node {
    stage {
        git url: https://github.com/LiorAtari/scripted-pipeline.git
    }
    stage ("Installing Dependencies") {
            sh "npm install"
        }

    stage ("Run tests") {
            sh "npm test"
    }
    stage ("Finished") {
        echo "Pipeline finished successfully"
    }
}
