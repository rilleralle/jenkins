node {
    stage('Build') {
        echo 'Building....'
        sh 'pwd && \
              curl -X POST -H "Content-type: application/json" --data {text:$(pwd)}" https://hooks.slack.com/services/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'
    }
    stage('Test') {
        echo 'Building....'
    }
    stage('Deploy') {
        echo 'Deploying....'
    }
}
