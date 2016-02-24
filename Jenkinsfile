// using multibranch
node {
    stage "checkout"
    checkout scm
    stage "build"
    sh '''env
    echo date1 job $BUILD_NUMBER > outfile.txt
    date >> outfile.txt'''
}
