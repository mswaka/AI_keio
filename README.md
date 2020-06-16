Keio線判別AI

1. 判別できる種類

* 7000系
* 8000系
* 9000系
* 新5000系

2. AIフレームワーク

Tensorflow + kerasを使って判別しています。

3. AIの性格

やたら8000系を推してきますｗ

4. 使い方

1. dl.pyでflickrから京王線の画像をダウンロードしてきます。
2. image_to_db.pyで、画像データからNPZ化します。
3. nn-keio.pyで、AIに学習させます。
4. check.pyで、京王線の画像データを判定させます。

以上
