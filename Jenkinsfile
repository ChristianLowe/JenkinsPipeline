job('Hello-Jenkins') {
    scm {
        git('https://github.com/ChristianLowe/HelloJenkins.git')
    }

    triggers {
        scm('H/15 * * * *')
    }

    steps {
        maven('-e clean test')
    }
}
