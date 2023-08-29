pipeline {
  agent any
  stages {
    stage('STAGE 1') {
      steps {
        sh '''pipeline {
agent any
stages {
stage(\'Build Assets\') {
agent any
steps {
echo \'Building Assets...\'
}
}
stage(\'Test\') {
agent any
steps {
echo \'Testing stuff...\'
}
}
}
}'''
        }
      }

    }
  }