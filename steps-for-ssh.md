https://medium.com/featurepreneur/setting-up-ssh-key-with-github-for-ubuntu-cd8f2fabf25b

cd .ssh/

ssh-keygen -t rsa -b 4096 -C "itzswika@gmail.com"

cat id_rsa.pub 

copy the output to github ssh settings

ssh -T git@github.com  #for testing
