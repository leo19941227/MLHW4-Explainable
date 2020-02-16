pip3 install gdown

gdown --id '1Zp5tXlrNfG1ei9PwoK302-svHgmV4Zk-' --output food-11.zip
unzip food-11.zip

gdown --id '1EZK846nw9w43qpFwz7KdZz5bwA2d-Vzg' --output checkpoint.pth

python3 hw5_explainable.py
