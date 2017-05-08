pipeline {
	agent any
	
	stages {
		stage ('build') {
			steps {
			sh 'ant -f build.xml -v'
			echo "Hi How are you Kishore..........."
			}
		}
	}
	post { always{
	archive 'dist/*.jar' 
		}
	}
}
