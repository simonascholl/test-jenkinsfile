node{
  stage 'Setup Systems'
  node{
  }
}
node{
  stage 'Start Tests'
      parallel(
          'p1':{
            input message: 'Continue computation?', submitter: 'admin'
          },
          'p2':{},
          'p3':{}
      )
}

node{
  stage 'other'
}

node{
  stage 'Publish JUnit'
}
