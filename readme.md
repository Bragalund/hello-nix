# Hello Nix  

From:  
https://nixos.org/guides/dev-environment.html

## Prerequisits  

Install nix  

````sh
mkdir /nix  
chown <YOUR_USERNAME> /nix
sh <(curl -L https://nixos.org/nix/install) --daemon
```

## How to build  

````sh
nix-build               # Build the nix package  
nix-shell default.nix   # start a nix shell
python3 myapp.py        # run the app 
# in another terminal  
curl localhost:5000     # should return "hello Nix!"  
```


