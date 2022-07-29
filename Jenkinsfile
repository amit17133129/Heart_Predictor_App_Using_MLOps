pipeline {
      agent any
      stages {
          stage('BuildingHeartPrectionPod'){
               when {
                expression {
                    return env.GIT_BRANCH == "origin/Developer1"
                }
            }
                steps {
                    sh 'echo "hi from developer1 branch in multi branch pipeline"'
                    // sh 'sudo kubectl expose deployment mlopsheartpred --type=NodePort  --port=4444   --kubeconfig /root/admin.conf'
                    // sh 'sudo kubectl get pod -o wide   --kubeconfig /root/admin.conf'
                    
                }
                
        }
        //  stage('gettingpod'){ 
        //        steps {
        //               sh 'sudo kubectl get pod -o wide  --kubeconfig /root/admin.conf'
        //               sh 'sudo kubectl get svc    --kubeconfig /root/admin.conf'
        //      }
        // }
    }
}
