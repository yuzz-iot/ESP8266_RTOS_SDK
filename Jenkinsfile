pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''export IDF_PATH=$(pwd)
cd $IDF_PATH/examples/get-started/project_template
PATH=$PATH:/opt/xtensa-lx106-elf/bin
make defconfig
make
'''
        sh '''export IDF_PATH=$(pwd)
cd $IDF_PATH/examples/get-started/project_template
PATH=$PATH:/opt/xtensa-lx106-elf/bin
make defconfig
make
'''
      }
    }
  }
}