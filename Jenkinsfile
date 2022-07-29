pipeline {
      agent any
      stages {
          stage('BuildingHeartPrectionPod'){
            checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/amit17133129/Heart_Predictor_App_Using_MLOps.git']]])
          }
      
    }
  }

