pipeline {
  agent any
  environment{
  ENV = 'DEV'
  APP_URL = 'myapp.host.name'	  
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
		echo "My Env: ${env.ENV}"
		echo "My App Url: ${env.APP_URL}"
      }
	  }
}
}
