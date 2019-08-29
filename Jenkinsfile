pipeline {
    agent any
    stages {
        stage('Unit Tests') {
            steps {
                executeUnitTest()
            }
        }
        stage('Package') {
            steps {
                executePackage()
            }
        }
        stage('Deploy') {
            steps {
                executeDeploy()
            }
        }
        stage('API Tests') {
            steps {
                executeAPITests()
            }
        }
    }

}

def executeUnitTest(){
    echo "Hello, executeUnitTest.3"
}

def executePackage(){
    echo "Hello, executePackage.3"
}

def executeDeploy(){
    echo "Hello, executeDeploy.3"
}

def executeAPITests(){
    echo "Hello, executeAPITests.3"
}
