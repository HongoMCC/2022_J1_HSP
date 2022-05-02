# 5/2 中1 HSP
## 既出
mes
color
pos
repeat-loop
goto-フラグ
button
変数の四則演算
演算子+-*/ AND OR NOT
wait
await
cls
font
if-else
boxf
stick
redraw
## 目標
マルチメディア処理を覚える/まとめ/インクルード紹介/screen/フリータイム(やりたいものを決めてもらう)
## 新出
celload-celput
mmload-mmplay
picload
## サンプル
### サンプル1(Celload)
cls 4  
celload "invader.png",1  
celput 1  
### サンプル2(mmload)
#### A
cls  
mmload "jump01.mp3",1  
mmplay 1  
#### B
cls  
mmload "jump01.mp3",1,1  
mmplay 1  
#### C
cls  
mmload "jump01.mp3",1,1  
mmplay 1  
repeat  
stick key  
if key=32:mmstop  
await 1  
loop  

