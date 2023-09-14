//vars,functions

node {
def x =2
env.y = 3
stage('stageee1'){
print x
}
stage('stageee2'){
sh 'echo y - ${x}'
sample()
}
}


// conditions

node {
def x=1
env.y = 3
if (x > 10){
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

def sample() {
print "its a function"
}