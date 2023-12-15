### Python environment setup with Conda

conda create -n myenv python=3.9

conda activate myenv

pip install torch==1.10.1 torchvision==0.13.1 torchaudio==0.12.1 --trusted-host download.pytorch.org

pip install torch-scatter torch-sparse torch-cluster torch-spline-conv torch-geometric==2.2.0 --trusted-host data.pyg.org

pip install rdkit

pip install torchmetrics==0.9.1

pip install ogb

pip install tensorboardX

pip install yacs

pip install opt_einsum

pip install graphgym 

pip install pytorch-lightning # required by graphgym 

pip install setuptools==59.5.0

### Running the file

python main.py --cfg configs/GRIT/zinc-GRIT.yaml  wandb.use 
