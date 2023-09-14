node {
def x=1
    stage('stage1') {
            echo 'this is stage1'
            print x
    }
}

node {
env.y = 2
    stage('stage1') {
            echo 'this is stage1'
            sh '${y}'
    }
}