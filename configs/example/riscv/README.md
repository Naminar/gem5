
#RISCV 
- - -
`gem5/json_config` provide the set to use local packets for `obtain_resource` function
- - -
## Usage:

 Set path in config.json like that: `/home/namin/gem5/json_config/source.json`

```sh
GEM5_CONFIG=json_config/config.json ./build/RISCV/gem5.fast   configs/example/riscv/fs2.py
```

Now Gem5 would find kernels and disk images only via config.json.