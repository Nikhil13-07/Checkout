pipeline{
   agent any
     stages{
       stage(git_checkout){
       	steps{
		echo 'master12345678'	
          git  'https://github.com/Nikhil13-07/Checkout.git'
       }    
     }
	   stage(clean){
       	steps{

          sh "mvn clean "
       }    
     }
}
}
