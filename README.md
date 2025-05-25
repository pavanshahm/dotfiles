*in pursuit of a computing forever home...*

# My NixOS config. 

To set up on a new machine. 

```
git clone ${this_repo} ~/nixos-config
sudo ln -s ~/nixos-config/etc/nixos

# TODO: hardware specific adjustments here

sudo nixos-rebuild switch
```


[Inspired by the NixOS beginner's guide](https://nixos-and-flakes.thiscute.world/nixos-with-flakes/other-useful-tips)
