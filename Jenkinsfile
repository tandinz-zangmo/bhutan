pipeline{
  agent any
  stages{
    stage ('hello'){
      steps{
        echo "demo of pipeline from Poll SCM" 
        echo "for trial"
        echo "tandin in tandin"> tandin
      }
    }
    stage ('pull'{
      steps{
        sh cat tandin
      }
    }
  }
} 
