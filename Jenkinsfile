node {
    stage('this is my code based git project game of life')
    {
        git 'https://github.com/wakaleo/game-of-life.git'

    }
    stage('build the packages') {
        sh 'mvn package'

    } 
    stage('archive'){
        archive 'target/*.exec'

    }
}
