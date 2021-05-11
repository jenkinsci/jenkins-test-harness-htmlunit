node('maven') {
    checkout scm
    sh 'mvn -B -ntp -Dset.changelist clean install'
    infra.prepareToPublishIncrementals()
}
infra.maybePublishIncrementals()
