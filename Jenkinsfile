pipeline{
   agent any
     stages{
       stage(git_checkout){
       	steps{
          git  'https://github.com/Nikhil13-07/Checkout.git'
       }    
     }
	   stage(clean){
       	steps{
		echo 'hi  '
          sh "mvn clean "
       }    
     }
}
}
