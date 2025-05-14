// 이 파일을 커밋하게 되면... 젠킨스와 깃허브가 뭐가 된대.. 자동 연동..?

pipeline {
	agent any
	stages {
		stage("build") {
			steps {
				echo 'building the application...'
			}
		}
		stage("test") {
			steps {
				echo 'testing the application...'
			}
		}
		stage("deploy") {
			steps {
				echo 'deploying the application...'
			}
		}
	}
}