/*@Library('testlib@main') _
evenOrOdd(currentBuild.getNumber())*/

pipeline {
    agent { label "master" }

    libraries {
        lib('https://github.com/mrlandscape20/testlib')
    }
    stages {
        stage("Echostage") {
            steps {
               echo "foo"
               evenOrOdd(currentBuild.getNumber())
            }
        }
    }
}


