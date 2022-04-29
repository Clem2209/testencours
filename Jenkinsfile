node {
    stage('bonjour') {
        checkout scm
    }
    stage('Build Source Code') {
        echo "building Source Code"
        sh "mvn package -DskipTests"
    }
    stage('test'){
        echo "mvn test"
        sh "mvn test"
    }


}