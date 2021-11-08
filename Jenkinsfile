node{
  stage('SCM Chekout'){
    git 'https://github.com/ichrak787/StudentServiceJenkins.git'
  }
  stage('Compile-package') {
    //Get Maven Home path
    def mvnHome = 
      sh"${mvnHome}/bin/mvn package" 
  }
}
