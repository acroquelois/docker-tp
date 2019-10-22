# Run TP


## Hello docker

I want a docker run command to show this using the `docker/whalesay` image : 


```bash
 ______________ 
< Hello M1 III >
 -------------- 
    \
     \
      \     
                    ##        .            
              ## ## ##       ==            
           ## ## ## ##      ===            
       /""""""""""""""""___/ ===        
  ~~~ {~~ ~~~~ ~~~ ~~~~ ~~ ~ /  ===- ~~~   
       \______ o          __/            
        \    \        __/             
          \____\______/ 
```

And I want, with that same command, for the container to be **deleted**.

### Answer here :

> docker run --name first_container --rm -i docker/whalesay cowsay Hello

---


## Interactive python shell

I don't have admin rights on my computer and I want to test something with python 3.

With a `docker container run`, start an **interactive** container with python 3 running.

And I want, with that same command, for the container to be **deleted** when I'm done.

### Answer here :

> docker run --name python --rm -it python:3-alpine