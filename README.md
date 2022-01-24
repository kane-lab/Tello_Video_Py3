# Tello_Video_Py3

Python2 で作成された Tello-Python/Tello_Video を Python3 で動作させる  

## Installation

1. Python3 をインストールする ("Add Python 3.x to PATH" にチェックを入れる)
1. コマンドプロンプトで以下のコマンドを実行する  

```
python -m pip install --upgrade pip
python -m pip install windows-curses
python -m pip install numpy
python -m pip install opencv-python
python -m pip install pillow
```

h264decoder は使用しません

## Usage

コマンドプロンプトで以下のコマンドを実行する  

```
python main.py
```

## Limitations

終了処理に問題があるため、終了後に Tello の電源を入れなおす必要あり

## Troubleshooting

* カメラの映像が表示されない
  * ファイアウォールの設定を確認する
