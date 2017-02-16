node {
   
   	stage 'Stage 1'
   		echo 'Hello there, shell scripts'
   	stage 'Checkout'
   		git url: 'https://github.com/GeneChuang1/jenkins_pipeline_shell_scripts'
   	stage 'Build'
   		bat 'myBuild.sh'
   	stage 'Deploy'
   		bat './myDeployment.sh'
  
}