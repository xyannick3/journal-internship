#mission
### description of the mission :
we were asked to experiment with having Platon run on idx to allow for easier AI manipulation. 

I've already used idx for angular but I've never used it that way before. 

### current progress: 
- installed docker 
- imported ./idx/dev.nix to interact with the environment ()

### difficulties :
- installing the dependencies
- having the dependencies working (right now docker doesn't work well)
- having node running at the right version (nvm does not work)


### solutions found :
adding `services.docker.enable = true;` inside the `dev.nix` allows for the usage of docker. 

### plan:
as of right now it's not my priority and I've kinda met a brick wall.