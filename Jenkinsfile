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
  bat'''cd lala
  '''
}
node{
  stage 'Wait for User input'
    input message: 'Continue computation?', submitter: 'admin'
}

node{
  stage 'Publish JUnit'
}
