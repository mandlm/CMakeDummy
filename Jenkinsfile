pipeline {
	agent any

	stages {
		stage("Build") {
			steps {
				cmakeBuild installation: "InSearchPath", buildType: "Release", cleanBuild: true
			}
		}
	}
}
