pipeline{
   agent any
     stages{
       stage(git_checkout){
       	steps{
		echo 'feature1'
          git  'https://github.com/Nikhil13-07/Checkout.git'
       }    
     }
	   stage(clean){
       	steps{
          sh "mvn clean"
       }    
     }
}
}
