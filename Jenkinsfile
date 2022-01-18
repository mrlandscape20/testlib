// @Library('testlib-jenkins@main') _
// evenOrOdd(currentBuild.getNumber())

pipeline {
    agent { label "master" }

    libraries {
        #lib('https://github.com/mrlandscape20/testlib')
        lib('https://github.com/mrlandscape20/testlib@main')
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


