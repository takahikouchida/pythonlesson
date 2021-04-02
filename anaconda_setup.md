# Anacondaの基本からFlaskのインストール

## 環境  
Windows 64bit Home  
Python 3.8


```
conda create -n pythonenv1 python=3.8
```

仮想環境を作る

```
conda create -n {{環境名}} python=3.8
```

仮想環境のリスト
```
conda env list
```

仮想環境の有効化
```
activate {{環境名}}
```

Flaskのインストール
```
pip install flask
```

