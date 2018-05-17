node {
    checkout scm
    
    stage('test_stage') {
        echo 'Hello World'
    }
    
    stage('publish_results') {
        junit allowEmptyResults: true, testResults: '*.xml'
    }
}