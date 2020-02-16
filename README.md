# MLHW4 Explainable

## Prepare dataset and pretrained checkpoint
Cause dataset and checkpoint are stored at google drive, here we use **gdown** to download

```sh
pip3 install gdown

# Download and unzip Food dataset
gdown --id '1Zp5tXlrNfG1ei9PwoK302-svHgmV4Zk-' --output food-11.zip
unzip food-11.zip

# Download pretrained checkpoint
gdown --id '1EZK846nw9w43qpFwz7KdZz5bwA2d-Vzg' --output checkpoint.pth
```

## Run python script

```
python3 hw5_explainable.py
```
