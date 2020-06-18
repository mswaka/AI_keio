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

* flickrのservices apiに登録して、apikeyとsecretの番号を使います。
* dl.pyでflickrから京王線の画像をダウンロードしてきます。
* image_to_db.pyで、画像データからNPZ化します。
* nn-keio.pyで、AIに学習させます。
* check.pyで、京王線の画像データを判定させます。

以上
