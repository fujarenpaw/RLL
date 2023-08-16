# RLL

Reinforcement Learning Learning

強化学習をお勉強するリポジトリ



## 仮想環境の作り方

1. 適当なフォルダを作成
2. ターミナルを立ち上げてCD
3. `conda create -n 仮想環境名 python=バージョン` で仮想環境を立ち上げる
   仮想環境名とバージョンは任意
4. `conda activate 仮想環境名`で仮想環境を有効化





## Pytorch環境

|         | Version |
| ------- | ------- |
| GPU     | RTX2060 |
| Cuda    | 12.1 |
| Python  | 3.10     |
| Pytorch | 2.0.1+cu118  |

Cuda12.1の場合でもPytorchのバージョンは`2.0.1+cu118`でいいみたい



**インストールコマンド**

```
conda create -n 仮想環境名 python=3.10
conda activate 仮想環境名
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
```

**pip list**

```
(my_env) C:\Users\hoge\Documents\GitHub\RLL>pip list | grep torch
torch              2.0.1+cu118
torchaudio         2.0.2+cu118
torchvision        0.15.2+cu118
```

