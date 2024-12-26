node{
    stage('Build'){
      steps{
        echo "building"
      }
    }
    stage('Test'){
      steps{
        echo "testing"
      }
      if(currentBuild.result=='Success'){
          echo " looks good"
      }else{
          echo "failed"
      }
    }
}
