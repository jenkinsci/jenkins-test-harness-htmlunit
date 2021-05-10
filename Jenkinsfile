node('maven') {
    checkout scm
    sh 'mvn -B -Dset.changelist clean install'
    infra.prepareToPublishIncrementals()
}
infra.maybePublishIncrementals()
