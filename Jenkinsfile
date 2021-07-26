pipeline{
  agent any
  parameters{
    string(name:"Path" defaultvalue: "Source Fullpath" description: "some comments")
    text(name: "Newmsg" defaultvalue: "Title" descripition: "some text comments")
    
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
