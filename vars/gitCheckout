def call(String branch,String gitUrl){
  checkout([$class: 'GitSCM', branches: [[name: '${branch}']], extensions: [], userRemoteConfigs: [[url: '${gitUrl}']]])
}
