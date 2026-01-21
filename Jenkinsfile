pipeline {
  agent any
  environment{
  ENV = 'DEV'
  APP_URL = 'myapp.host.name'	  
  }
  parameters{
  string(name: 'myname',defaultValue: 'Dipanjan',description:'This is my name')
  booleanParam(name: 'isManager', defaultValue: false, description: 'Is he a manager')
  }
  
  stages{ 
    stage ('SayHello'){
      steps {
        echo 'Hi Hello world'
        echo 'I am not AI'
}
} 
	  stage ('GoAhead'){
       steps{
        echo '************I will be the best of all************'
		echo "My Env in JenkinsFile: ${env.ENV}"
		echo "My App Url in JenkinsFile: ${env.APP_URL}"
      }
	  }
}
}
