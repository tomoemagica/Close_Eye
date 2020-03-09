# Close_Eye
 Detect Close Eye

Download URL
http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2

Extract with Winrar etc.

Download URL

https://github.com/tomoemagica/Close_Eye

Place the close_eye.py file in the DFL\workspace folder.

how to use

py close_eye.py

Search for face images in the DFL\workspace\data_src\aligned folder,

Face image with closed eyes

Move to DFL\Workspace\data_src\aligned\close_eye folder.

Only the face close to the front works.

Profiles cannot be detected.

It worked fine with a 512x512 pixel face.

For a 256x256 pixel face,

Line 23 of the source code

if abs (y0-y1) <10:

You may need to change the threshold of 10.



閉じた目を検出

ダウンロードURL http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2

Winrarなどで解凍します

shape_predictor_68_face_landmarks.datファイルになるはずです。

DFL\workspaceフォルダーに配置します。


ダウンロードURL https://github.com/tomoemagica/Close_Eye

close_eye.pyファイルをDFL\workspaceフォルダーに配置します。

使用方法

py close_eye.py

DFL\workspace\data_src\alignedフォルダーで顔画像を検索し、

目を閉じた顔画像をDFL\Workspace\data_src\aligned\close_eyeフォルダーに移動します。

正面に近い顔だけが機能します。 横顔は検出できません。

512x512ピクセルの面で問題なく動作しました。 

256x256ピクセルの顔の場合、

ソースコードの行23：

abs（y0-y1）<10

10のしきい値

を変更する必要がある場合があります。

100%の検出精度ではありません。
