node {
    stage('build')
    {
        if ( env.TAG_NAME != null )
        {
            println "we are building a tag with tag name ${env.TAG_NAME}"

        }
        else { println "we are building a branch" }
        if (env.TAG_NAME == "release-1.1")
        {
            println "deploying release-1.0"
        }

    }


}
