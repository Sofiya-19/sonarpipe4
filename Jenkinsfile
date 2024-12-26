node{
  stages{
    stage('Build'){
      steps{
        echo "building"
      }
    }
    stage('Test'){
      steps{
        echo "testing"
      }
      if(current.Build=='Success'){
          echo " looks good"
      }else{
          echo "failed"
      }
    }
}
