## Kubernetes pod update using patch

kubectl patch pod ngix-standalone -p '{"spec":{"containers":[{"name":"nginx","image":"alpine"}]}}' **

## kubernetes to execute

 kubectl exec --stdin --tty nginx-standalone  -- sh

 kubectl exec --stdin --tty my-nginx-5bb9b897c8-7xg8m  -- sh

## install curl inside pod


##change color of the terminal

export PS1='\[\033[00;35m\]\u\[\033[00m\]@\[\033[00;35m\]\H\[\033[00m\]:\[\033[00;33m\]\W\[\033[00m\] \$\[\033[00;34m '

