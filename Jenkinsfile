stage 'U1':{
node{
  stage 'Setup Systems'
  node{
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
}
}
node{
  stage 'Wait for User input'
    input message: 'Continue computation?', submitter: 'scholl_s'
}

node{
  stage 'Publish JUnit'
}
