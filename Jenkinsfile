node {
def x=1
env.y = 3
    stage('stage1') {
            echo 'this is stage1'
            print x
    }
    stage('stage2') {
         sh '${y}'
        }
}
