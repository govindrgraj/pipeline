pipeline{
  agent any
  parameters{
    string(name:'Path', defaultValue: 'Source Fullpath', description: 'some comments')
    text(name: 'Newmsg', defaultValue: 'Title', description: 'some text comments')
    
  }
  stages{
    stage('Source'){
      steps{
        echo "Jenkins file executed"
      }
    }
    stage('Deploy'){
      steps{
        echo "output= ${params.Path} value!"
      }
    }
  }
}
