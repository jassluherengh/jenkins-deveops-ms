pipeline{
	agent {
         docker {
             image "maven:3.6.3-jdk-13"
			// label "myDocker"
         }
	}
	//agent any

	//tools{
	//	maven "myMaven"
	//}
	stages{
		stage('Build'){
			steps{
					//sh 'ls'
					// sh "chmod +x -R ${env.WORKSPACE}"
				//	sh "chmod +x -R ${env.WORKSPACE}"
        			//sh './jenkins/test.sh
					sh 'ls'
					sh "mvn -version"
					//echo "Build"
					echo "Path -$PATH "
			}			
		}
		stage('Test'){
			steps{
					echo "Test"
			}			
		}
		stage('Integeration Test'){
			steps{
					echo "Integeration Test Jissu"			
			}			
		}
	}
	post{
		always{
			echo "I am awsome, I am always called"
		}
		success{
			echo "build successful When you are success"
		}
		failure{
			echo "Build failed"
		}
	}
}
