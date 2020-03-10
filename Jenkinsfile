node {
    stage('GITHUB'){
        git 'https://github.com/nusrat777/maven.git'
    }
    stage('build'){
        sh label: '', script: 'mvn -f  web/pom.xml clean package'
    }
}
