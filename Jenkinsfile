gitConfig = { node ->
    node / gitConfigName('Jenkins')
    node / gitConfigEmail('jenkins@example.com')
}

pipelineJob('Hello-Jenkins') {
    definition {
        cpsScm {
            scm {
                git('https://github.com/ChristianLowe/HelloJenkins.git', gitConfig)
            }
        }
    }
}
