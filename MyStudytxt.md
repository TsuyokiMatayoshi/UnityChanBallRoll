# Udemy「Unityちゃん」

## Unityとは
結論：なんでもできる。

## Unity自体にtutorialがあるのでやる。

## プロジェクトの準備とオブジェクトの操作
GitHubからフォーク&クローン
ダウンロードZIPでもよい

UnityのProjectフォルダは直接エクスプローラーからいじらないほうが良い
※Unity内部から触るとよい

New  プロジェクトを作る
Open プロジェクトを開く

レイアウトを自分でいじって使いやすくしよう、自分は2By3
Projectの所にAssetsとPackages
Assetsの中にEtcとExample,StandardAssetsがある。

#### 新しいSceneの作成
1つのProjectの中にいくつも作れる。
OP,EDごとに作って使える

Unityの真ん中上にPlayモード、停止等のボタンがある。

メニューの左からNewScene
Assetsフォルダの中だとどこでもいいが、整理するとよい

#### オブジェクトの基本操作
思い通りに操作をする。
オブジェクトの周りの三方向矢印、Gizumo

いじりすぎても、InspectorのTransformのリセット
手入力でも位置調整ができる。

## マテリアルとテクスチャ
オブジェクトに色&模様をつける

Deleteで消せる。
Ctrl＋Zで一つ戻る。
Ctrl+yは戻す前に戻る。

#### ステージ作り
GameObject→3D→CUBE 　□
GameObject→3D→Plan   ○

配置後、コンポーネントの歯車から「Reset」を選ぶとシーンの真ん中へ
Sceneビューで見えにくい場合は、Hierarchyから探す。

GameObjectから、Sphereをツクル
床と被っていたため、上にあげる。Gizumoを使ってもよいです

1つの行動でもUnity上ではいくつも方法があります。自分に合ったものを

#### マテリアルを設定
オブジェクトの表面を決めるもの。マテリアルを使うと金属やガラスを表現できる
マテリアルは、オブジェクトのように単体で置くことはない（部品の一部）

プロジェクトウィンドウで作る,CreateからMaterialを選択
NewMaterialが完成　整理しよう

#### テクスチャを貼ろう
模様をつけたい＝Unityでかく×
模様を描いた画像を貼り付ける
画像＝テクスチャ

テクスチャをマテリアルに設定することで、
しっかりとすごい表現のモデルができる。

MaterialsのInspectorにあるAlbedoに写真を持っていて渡せる。

