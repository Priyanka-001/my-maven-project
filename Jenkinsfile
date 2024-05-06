pipeline {
agent any
stages {
stage('Checkout') {
steps {
git 'https://github.com/Priyanka-001/my-maven-project.git'
}
}
stage('Build') {
steps {
sh 'mvn clean package'
}
}
}
}
