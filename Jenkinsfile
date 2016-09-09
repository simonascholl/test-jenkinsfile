node{
  stage 'Setup Systems'
    node{
      echo 'stuff'
    }
}
node{
  stage 'Start Tests'
    parallel(
        'p1':{},
        'p2':{},
        'p3':{},
        failFast:false
    )
}

node{
  stage 'other'
}
node{
  stage 'Wait for User input'
    input message: 'Continue computation?', submitter: 'admin'
}

stages{
  node{
    stage 'Publish JUnit'
  }
}
