pipeline {
	agent any
        stages {
                stage("Parallel") {
                        parallel {
                                stage("windows") {
                                        agent {
                                                label 'fetch'
                                        }
                                        steps {
                                                echo 'Hello Sir'
                                        }
                                }
                                stage("linux") {
                                agent any
					steps {
                                                echo 'Hello Sir'
                                        }
                                }
                        }
                }
        }
}
