node {
stage('checkout SCM') {
     git 'https://github.com/DeepthiMogaparthi/TestGit.git'
}
stage('Build') {
 	def mvnHome = tool name: 'maven', type: 'maven'	
 	echo 'Hello World'	
 	sh "${mvnHome}/bin/mvn package"	 

   }
 }
