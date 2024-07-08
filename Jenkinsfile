pipeline {
  agent any
  stages {
    stage ("run the build and archive job...") {
      steps {
        build job: "software-management/build yt-dlp CLI package"
      }
    }
  }
}