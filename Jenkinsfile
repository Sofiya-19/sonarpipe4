node{
    stage('Build'){      
        echo "building the project!.."
    }
    stage('Test'){
        echo "running test..."
    }
    stage('Deploy'){
        echo "Deploying the application....."
    }
    if(currentBuild.currentResult=='Success'){
        echo " looks good"
    }else{
        echo "failed"
    }
}
