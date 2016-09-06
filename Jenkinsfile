node{
  stage 'Setup Systems'
  node{
  }
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

node{
  stage 'Publish JUnit'
}
