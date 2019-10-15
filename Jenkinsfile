pipeline {
  agent any
  stages {
    stage('Snyk Dep Check') {
      steps {
        snykSecurity(organisation: 'jose-alvarez-arm', projectName: 'goSDL', severity: 'high', snykInstallation: 'Snyk', snykTokenId: '223a828a-794f-42cc-b3bb-df2f6d0d790a', additionalArguments: 'snyk test')
      }
    }
  }
}