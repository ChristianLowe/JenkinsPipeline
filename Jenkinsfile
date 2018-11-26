pipelineJob('Hello-Jenkins') {
    definition {
        cpsScm {
            scm {
                git('https://github.com/ChristianLowe/HelloJenkins.git') {
                    gitConfigName('Jenkins')
                    gitConfigEmail('jenkins@example.com')
                }
            }
        }
    }
}
