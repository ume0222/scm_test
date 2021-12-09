node {
  stage('Clone') {
    git('https://github.com/ume0222/scm_test.git')
  }
  stage('ファイルを確認') {
    sh 'ls -l'
    sh 'cat Jenkinsfile'
  }
}
