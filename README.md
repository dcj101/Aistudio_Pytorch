# Aistudio_Pytorch
# 快速启动项目
```
python3 -m venv .venv
source .venv/bin/activate

python -m pip install --upgrade pip setuptools wheel

pip install ipykernel notebook jupyterlab numpy matplotlib pillow torchinfo
pip install torch --index-url https://download.pytorch.org/whl/cpu

python -m ipykernel install --user \
  --name aistudio-pytorch \
  --display-name "Python (.venv) Aistudio_Pytorch"
```
# 配置切换环境要点击jupyterlab的重启按钮
```
jupyter lab restart
```