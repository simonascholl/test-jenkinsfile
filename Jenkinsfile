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
        'p3':{}
    )
}

node{
  stage 'other'
  'p1':{
        echo 'stuff'
      }
}
node{
  stage 'Wait for User input'
    input message: 'Continue computation?', submitter: 'admin'
}

node{
  stage 'Publish JUnit'
}
