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
stage('Deploy approval'){
    input "Deploy to prod?"
}
node {
    stage('deploy to prod'){
        echo "deploying"
    }
}
