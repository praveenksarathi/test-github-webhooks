node {
  stage ("checkout") {
    checkout scm
  }
  stage ("Build") {
    sleep 10
    sh "ls -lrt"
  }
  
  stage ("Commit") {
    sleep 5
    echo "The commit stage has passed"
  }
  
  stage ("Deploy") {
    sleep 4
    echo "The Deploy stage has passed"
  }
}
