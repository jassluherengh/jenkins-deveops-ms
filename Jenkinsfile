pipeline{
	//agent {
        // docker {
        //     image 'maven:3.6.3'
        // }
     	// }
	agent any
	stages{
		stage('Build'){
			steps{
					//sh 'ls'
<<<<<<< HEAD
					// sh "chmod +x -R ${env.WORKSPACE}"
=======
				//	sh "chmod +x -R ${env.WORKSPACE}"
>>>>>>> daf54e6d55a62300c558a43315c44e0188297b4a
        			//sh './jenkins/test.sh
					sh 'ls'
					echo "Build"
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
