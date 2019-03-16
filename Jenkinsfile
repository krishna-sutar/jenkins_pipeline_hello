node {
    stage('build'){
        echo "building"
    }
}
anyagent {
    stage('test'){
        echo "testing"
    }
}
stage('Get approval'){
    input "Deploy to qa?"
}
node {
    stage('deploy to qa'){
        echo "deploying"
    }
}
node {
    stage('deploy to Prod'){
    echo "deploying to prod"
}
}

