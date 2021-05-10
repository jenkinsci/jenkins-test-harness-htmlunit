node('maven') {
    sh 'mvn -B -Dset.changelist clean install'
    infra.prepareToPublishIncrementals()
}
infra.maybePublishIncrementals()
