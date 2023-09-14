//vars,functions

node {
def x=1
env.y = 3
    stage('stage1') {
      echo 'this is stage1'
       print x
       sample()
    }
    stage('stage2') {
         sh 'echo x - ${y}'
        }
}

//conditions

node {
if (x>y){
    stage('stage3') {
      echo 'stage1'
    }
}
else
    stage('stage4') {
    echo 'stage2'
}
}


def sample() {
print "its a function"
}