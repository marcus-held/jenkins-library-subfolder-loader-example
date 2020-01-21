@Library('local-shared-library@1.0') _
loadLocalLibrary scm, "library"

pipeline {
	agent any
	stages {
		stage("Test") {
			steps {
				localTest()
			}
		}
	}
}
