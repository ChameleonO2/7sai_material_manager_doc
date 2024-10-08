# 7sai Material Manager

[![トレイラー動画](img/thumbnail_16_9.png)](https://www.youtube.com/watch?v=45gonGhqhHw)

Blenderのマテリアル管理と割り当てを簡単にするためのアドオンです。このアドオンを使用すると、オブジェクトやコレクションに対して、マテリアルの作成、割り当て、管理を簡単に行うことができます。

## 機能
- Blender UI内で新しいマテリアルを作成。
- 選択したオブジェクトやコレクション全体にマテリアルを割り当て。
- すべてのマテリアルと割り当てられたオブジェクトを管理。
- 各マテリアルの関連オブジェクトの選択。
- 選択したマテリアルを簡単に削除。
- すべてのマテリアルを選択/解除、または未割り当てのマテリアルのみを選択可能。

## インストール方法
1. アドオンファイルをダウンロードします。
2. Blenderで`編集 > Preferences > Add-ons`を選択します。
3. 「インストール」ボタンを押し、ダウンロードしたアドオンファイルを選択します。
4. インストール後、「7sai Material Manager」の横のボックスにチェックを入れてアドオンを有効にします。

## 使い方

![Material Manager](img/TheBigPicture.png)

3Dビューのサイドバー（`View3D > Sidebar > Material Manager`）に移動します。

### マテリアルの管理 
![Material List](img/materiallist.png)

「Material List」パネルで既存のマテリアルを管理できます：
   - すべてのマテリアルを選択/解除。
   - 未割り当てのマテリアルのみの選択。
   - 各マテリアルに割り当てられたオブジェクトを表示。
   - 選択したマテリアルを削除。

### マテリアルの作成と割り当て
![Assign Material](img/assign_material.png)

「Assign Material」パネルで新しいマテリアルを作成し、オブジェクトやコレクションに割り当てられます：

#### Create New Material
新規マテリアルを作成します。
1. 「Name」に新しいマテリアルの名前を入力します。
2. Create New Materialボタンをクリックします。

#### Assign to Selected Objects
選択したオブジェクトにマテリアルを割り当てます。
1. 割り当てるマテリアルを「Material」の項目に入力します。
2. マテリアルを割り当てたいオブジェクトを選択します。
3. Assign to Selected Objectsボタンをクリックします。

#### Assign to Collection
1. 割り当てるマテリアルをPanelのマテリアルの項目に入力します。
2. マテリアルを割り当てたいコレクションを「Collection」の項目に入力します。
3. Assign to Collectionボタンをクリックします。


## ライセンス
このアドオンはGnu GPL v3ライセンスの下でリリースされています。詳細については、[LICENSE](LICENSE)ファイルを参照してください。

