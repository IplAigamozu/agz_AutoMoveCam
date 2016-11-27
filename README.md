# agz_AutoMoveCam

##OpenCVの使い方
###utilsブランチからopencvを任意の場所へコピー
* visual studio上の "表示" ⇒ "その他のウィンドウ" ⇒ "プロパティマネージャー" を開く
* Debug|Win32 をクリックし, "C/C++" ⇒ "全般" ⇒ "追加のインクルードディレクトリ" にopencv/build/includeまでのpathを記入
* 続いて, "リンカー" ⇒ "全般" ⇒ "追加のライブラリディレクトリ" にopencv/x86/vc12/lib までのpathを記入
* 最後に, "リンカー" ⇒ "入力" ⇒ "追加の依存ファイル"に"opencv_core249d.lib","opencv_highgui249d.lib","opencv_imgproc249d.lib"を記入

##OptCamSDKの使い方
###utilsブランチからOptCamSDKを任意の場所へコピー

*ここがemタグで強調されます*  
_ここがemタグで強調されます_
**ここがstrongタグで強調されます**
__ここがstrongタグで強調されます__


* 1番目
* 2番目
* 3番目
または
+ 1番目
+ 2番目
    + 2番目-1
    + 2番目-2
    + 2番目-3
+ 3番目
または
- 1番目
- 2番目
- 3番目

> これは引用です


### 打ち消し線のサポート
~~打ち消し線~~

### 区切り文字で囲われたコードブロック

```
ソースコードをここに書く
```

### ソースコードブロックのシンタックスハイライト機能

```rb
num = 0
while num < 2 do
   print("num = ", num)
end
print("End")
```
