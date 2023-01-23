pipeline {

  agent any

  stages{

    stage('git checkout'){
        
        steps{
            git credentialsId: 'f07e70c9-0315-4e1d-86d3-f65e1e0e2388', url: 'https://github.com/naveenkallammanavar/MavenWarProject.git'
        }
    }
    stage('UNIT TESTING'){
        
        steps{
            sh mvn test
        }
    }
  }
}
