# ASOCR(Auto Screen OCR)
Select range and every time you press Space key, OCR is activated.
範囲を選ぶと、あなたがスペースキーを押すたびに、画面が変わる度にOCRが起動します。

## usage:使い方
0. Settings->Privacy->Allow screen capture to terminal
1. `pip install -r requirements.txt`
2. download jpn.traineddata
https://github.com/tesseract-ocr/tessdata
3. move jpn.traineddata to `/usr/loacl/share/tessdata/`
4. `python main.py`
5. select range and press space key
6. it works!
7. escape by esc key

## usage2: select many windows
4. `python main_manywindows.py`
5. select range
6. delete range by delete key
7. press space key
8. it works!
9. escape by esc key


# 最終目標:todo
- Select range and every time the screen changes, OCR is activated. 範囲を選んで放置すると、画面が変わる度にOCRが起動します。
- 具体的には同じ画面が2秒以上続くと一度だけその画面をOCRします。