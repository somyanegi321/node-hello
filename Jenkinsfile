pipeline{
  agent any
  stages{
    stage('clone'){
      steps{
      git branch: 'testing', url: 'https://github.com/somyanegi321/node-hello.git'
      }}
    stage('run'){
      steps{
     sh '''npm pack
npm start'''
      }}
  }
}
