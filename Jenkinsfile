pipelineJob('Hello-Jenkins') {
    definition {
        cpsScm {
            scm {
                git('https://github.com/ChristianLowe/HelloJenkins.git') { node ->
                    node / gitConfigName('Jenkins')
                    node / gitConfigEmail('jenkins@example.com')
                }
            }
        }
    }
}
