node {
    stage('Clone repository') {
        checkout scm
    }
    stage('Build image'){
        docker.build("test_build:${env.BUILD_ID}")
    }
}