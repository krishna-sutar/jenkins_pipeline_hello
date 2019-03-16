node {
    stage('build'){
        echo "building"
    }
}
node {
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
stage('Get approval'){
    input "Deploying"
}
node {
    stage('deploy to Prod'){
    echo "deploying to prod"
}
}

