*in pursuit of a virtual forever home...*

# My NixOS config. 

To set up on a new machine. 

```
git clone ${this_repo} ~/nixos-config
# make a backup of the default config
sudo mv /etc/nixos /etc/nixos.bak
sudo ln -s ~/nixos-config /etc/nixos

# TODO: hardware specific adjustments here
# TODO: deal with hardware configuration in a more 
# TODO: elegant way so we don't have to use --impure
sudo nixos-rebuild switch --impure
```

*kept public for educational purposes*


[Inspired by the NixOS beginner's guide](https://nixos-and-flakes.thiscute.world/nixos-with-flakes/other-useful-tips)
