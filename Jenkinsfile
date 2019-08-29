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
    echo "Hello, executeUnitTest."
}

def executePackage(){
    echo "Hello, executePackage."
}

def executeDeploy(){
    echo "Hello, executeDeploy."
}

def executeAPITests(){
    echo "Hello, executeAPITests."
}
