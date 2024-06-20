https://84kaoru.github.io/ar_pazzle.github.io/


1.FBX→gtlfは実行パスを記載　＄FBX2glTF-darwin-x64までのパス fbxまでのパス

2.マーカーは認識できる黒線の幅を調整

3.変換したgltfをbinファイルと共にzip→ar.js studioに適当な写真と共にアップロード
新たなgltfファイルをゲット　それをフォルダに入れる

##　使い方

# マーカーを変更したい場合
1. [AR.js Marker Training](https://jeromeetienne.github.io/AR.js/three.js/examples/marker-training/examples/generator.html)に画像をアップロード
※pattern ratio は変更可能だが、マーカーの読み取り制度に影響が出る(デフォルト0.5が妥当)

2. マーカーのimgとmattファイルを保存

3. コード内の既存のmattファイルと差し替える

# 3Dモデルを変更したい場合(元モデルがFBX形式の場合)
1. FBX2gLTFを使う→[FBX2glTF-darwin-x64をダウンロード](https://github.com/facebookincubator/FBX2glTF/releases)

[AR.js Studio](https://ar-js-org.github.io/studio/pages/marker/index.html)

