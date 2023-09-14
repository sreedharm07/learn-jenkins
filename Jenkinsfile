//vars,functions

node {
def x=1
env.y = 3
if (x>y){
    stage('stage1') {
      echo 'this is stage1'
       print x
       sample()
    }
    }
    else
    stage('stage2') {
         sh 'echo x - ${y}'
        }
}
}




def sample() {
print "its a function"
}