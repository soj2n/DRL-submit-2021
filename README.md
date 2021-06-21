# DRL-submit-20215321-sojin jang
## requirements   
`Unity (2019.4.28)`  
`mlagents==0.8.1`  
`mlagents_envs==0.8.1`  
`tensorflow>=1.7,<1.8`  
`Pillow>=4.2.1`  
`matplotlib`  
`numpy>=1.13.3,<=1.14.5`  
`jupyter`  
`pytest>=3.2.2,<4.0.0`  
`docopt`  
`pyyaml`  
`protobuf>=3.6,<3.7`  
`grpcio>=1.11.0,<1.12.0`. 
`pypiwin32==223;platform_system=="Windows"`  
`python_requires=">=3.6,<3.7"`  

## To train
- Please clone mlagents==0.8.1 in this repository. https://github.com/Unity-Technologies/ml-agents
- Run this code.
```bash
mlagents-learn ~/trainer_config.yaml --env=~/env_drone_linux.x86_64 --run-id=<exp-id> --no-graphics
```
- You should use `--no-graphics` option if you are going to train a model on a server.
