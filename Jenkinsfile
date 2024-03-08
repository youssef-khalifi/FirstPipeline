node {
    stage('Clone') {
        git branch: 'main', credentialsId: 'youssef', url: 'https://github.com/youssef-khalifi/FirstPipeline.git'
    }
    stage('Build') {
        sh 'javac Main.java'
    }
    stage('Run') {
        sh 'java Main'
    }
}
