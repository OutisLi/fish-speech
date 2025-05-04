# Linux

```shell
conda create -n fish-speech python=3.12 -y
conda activate fish-speech
pip install --pre torch torchvision torchaudio --index-url https://download.pytorch.org/whl/nightly/cu128
pip install -e .
```

```shell
conda create -n fish-speech python=3.10
pip install torch==2.4.1 torchvision==0.19.1 torchaudio==2.4.1
pip install --pre torch torchvision torchaudio --index-url https://download.pytorch.org/whl/nightly/cu128
```

```shell
sudo apt update && sudo apt upgrade -y && sudo apt autoremove -y
sudo apt install libsox-dev libasound-dev portaudio19-dev libportaudio2 libportaudiocpp0
```

## 安装 fish-speech

```shell
pip install -e .[stable]
```
