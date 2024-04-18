# karabiner

目次
- [キーバインド](https://github.com/YushiroDodo63/karabiner/tree/main#%E3%82%AD%E3%83%BC%E3%83%90%E3%82%A4%E3%83%B3%E3%83%89%E4%B8%80%E8%A6%A7)
  - [JIS](https://github.com/YushiroDodo63/karabiner/tree/main#jis)
  - [US](https://github.com/YushiroDodo63/karabiner/tree/main#us)

## karabiner の設定方法
### 1. Karabiner-Elements のダウンロード・インストール

下記URLから Karabiner-Elements をダウンロード  
URL: https://karabiner-elements.pqrs.org/  

ダウンロード後、dmgファイルを開いてpkgファイルを実行し、指示に従ってインストールする。 

アプリを開くまでにプライバシー設定やキーボードの配列を判定する画面が表示されるので、画面の案内通りに進める。


### 2. キーバインドの設定（USのみ）
<!-- 
Karabiner-ELements が開けると以下のような画面になると思うので、サイドバーの `Simple Modifications` を選択し、該当のキーボードを選択する。  
右側の `Add item` をクリックし、 caps_lock を left_control に置き換える
-->
<!-- 
<img width="1091" alt="スクリーンショット 2023-09-09 21 29 40" src="https://github.com/YushiroDodo63/karabiner/assets/71711872/cd3e9c26-7e54-47ca-8a45-3fd7d8b34d13"> 
-->

Karabiner-ELements が開けると、サイドバーの `Simple Modifications` を選択し、該当のキーボードを選択する。  
右側の `Add item` をクリックし、 caps_lock を left_control に置き換える


### 3. 設定の読み込み
#### 3.1 設定ファイルの配置
本リポジトリをクローンし、次の位置に配置する。  
`~/.config/karabiner/assets/complex_modifications/dodo.json`  

#### 3.2 Karabiner-Elements から設定を読み込み
<!-- 
Karabiner-Elements を開いて下記画面のサイドバーから `Complex Modifications` を選択し、 `Add rule` をクリック  
<img width="1095" alt="スクリーンショット 2023-09-09 22 10 35" src="https://github.com/YushiroDodo63/karabiner/assets/71711872/1f7b0dbb-c526-4b57-b636-72cea16a79ed">

下記画面のようなモーダルが表示されるので、キーボードに合わせて `All in one for JIS`, `All in one for US` のどちらかをクリック
<img width="1093" alt="スクリーンショット 2023-09-09 22 10 58" src="https://github.com/YushiroDodo63/karabiner/assets/71711872/893a048f-3feb-4deb-b64b-07e5712c883b">

以下のように `Add rule` の上に選択した設定が追加されていればOK
<img width="1096" alt="スクリーンショット 2023-09-09 22 10 21" src="https://github.com/YushiroDodo63/karabiner/assets/71711872/b2df2c1a-4d7c-46bb-8e4b-6b3fcf424526">
-->
Karabiner-Elements を開いてサイドバーから `Complex Modifications` を選択し、 `Add rule` をクリック  

モーダルが表示されるので、キーボードに合わせて `All in one for JIS`, `All in one for US` のどちらかをクリック

以下のように `Add rule` の上に選択した設定が追加されていればOK

## キーバインド一覧
※ JIS, US 共通で space を長押しすることで right_option になるように設定しています
### JIS
※ 英数長押し → left_command, かな長押し → right_option になるよう設定しているので以下の "left_command", "right_option" は 英数長押しまたはかな長押しに対応しています。

<table>
  <tr>
    <th>
      キーバインド
    </th>
    <th>
      置き換え後
    </th>
  </tr>
  
  <tr>
    <td colspan=2>
      キーバインドの変更
    </td>
  </tr>
  <tr>
    <td>
      英数（長押し）
    </td>
    <td>
      left_command
    </td>
  </tr>
  <tr>
    <td>
      かな（長押し）
    </td>
    <td>
      right_option
    </td>
  </tr>

  <tr>
    <td colspan=2>
      カーソル移動
    </td>
  </tr>
  <tr>
    <td>
      left_commend + h
    </td>
    <td>
      ←（カーソル左）
    </td>
  </tr>
  <tr>
    <td>
      left_commend + j
    </td>
    <td>
      ↓（カーソル下）
    </td>
  </tr>
  <tr>
    <td>
      left_commend + k
    </td>
    <td>
      ↑（カーソル上）
    </td>
  </tr>
  <tr>
    <td>
      left_commend + l
    </td>
    <td>
      →（カーソル右）
    </td>
  </tr>
  <tr>
    <td>
      left_commend + n
    </td>
    <td>
      left_command + ← (Home)
    </td>
  </tr>
  <tr>
    <td>
      left_commend + m
    </td>
    <td>
      left_command + → (End)
    </td>
  </tr>


  <tr>
    <td colspan=2>
      よく使うキー
    </td>
  </tr>
  <tr>
    <td>
      left_commend + d
    </td>
    <td>
      delete(back space)
    </td>
  </tr>  
  <tr>
    <td>
      left_commend + f
    </td>
    <td>
      Esc
    </td>
  </tr>
  <tr>
    <td>
      left_commend + space
    </td>
    <td>
      Enter
    </td>
  </tr>
  
  <tr>
    <td colspan=2>
      カーソル等の移動系（あると便利なキー）
    </td>
  </tr>
  <tr>
    <td>
      left_commend + right_option + h
    </td>
    <td>
      option + ←（単語単位でカーソル左）
    </td>
  </tr>
  <tr>
    <td>
      left_commend + right_option + j
    </td>
    <td>
      page up
    </td>
  </tr>
  <tr>
    <td>
      left_commend + right_option + k
    </td>
    <td>
      page down
    </td>
  </tr>
  <tr>
    <td>
      left_commend + right_option + l
    </td>
    <td>
      option + →（単語単位でカーソル右）
    </td>
  </tr>
  <tr>
    <td colspan=2>
      記号系
    </td>
  </tr>
  <tr>
    <td>
      right_option + a
    </td>
    <td>
      _
    </td>
  </tr>
  <tr>
    <td>
      right_option + s
    </td>
    <td>
      +
    </td>
  </tr>
  <tr>
    <td>
      right_option + d
    </td>
    <td>
      delete(カーソル右の文字を削除)
    </td>
  </tr>
  <tr>
    <td>
      right_option + f
    </td>
    <td>
      -
    </td>
  </tr>
  <tr>
    <td>
      right_option + g
    </td>
    <td>
      =
    </td>
  </tr>
  <tr>
    <td>
      right_option + z
    </td>
    <td>
      {
    </td>
  </tr>
  <tr>
    <td>
      right_option + x
    </td>
    <td>
      }
    </td>
  </tr>
  <tr>
    <td>
      right_option + c
    </td>
    <td>
      [
    </td>
  </tr>
  <tr>
    <td>
      right_option + v
    </td>
    <td>
      ]
    </td>
  </tr>
  <tr>
    <td>
      right_option + b
    </td>
    <td>
      `
    </td>
  </tr>
  <tr>
    <td>
      right_option + n
    </td>
    <td>
      /
    </td>
  </tr>
  <tr>
    <td>
      right_option + m
    </td>
    <td>
      ~
    </td>
  </tr>
  <tr>
    <td>
      right_option + ,
    </td>
    <td>
      \
    </td>
  </tr>
  <tr>
    <td>
      right_option + .
    </td>
    <td>
      |
    </td>
  </tr>
  <tr>
    <td>
      right_option + /
    </td>
    <td>
      ?
    </td>
  </tr>
  <tr>
    <td>
      right_option + q
    </td>
    <td>
      !
    </td>
  </tr>
  <tr>
    <td>
      right_option + w
    </td>
    <td>
      @
    </td>
  </tr>
  <tr>
    <td>
      right_option + e
    </td>
    <td>
      #
    </td>
  </tr>
  <tr>
    <td>
      right_option + r
    </td>
    <td>
      $
    </td>
  </tr>
  <tr>
    <td>
      right_option + t
    </td>
    <td>
      %
    </td>
  </tr>
  <tr>
    <td>
      right_option + y
    </td>
    <td>
      ^
    </td>
  </tr>
  <tr>
    <td>
      right_option + u
    </td>
    <td>
      &
    </td>
  </tr>
  <tr>
    <td>
      right_option + i
    </td>
    <td>
      *
    </td>
  </tr>
  <tr>
    <td>
      right_option + o
    </td>
    <td>
      (
    </td>
  </tr>
  <tr>
    <td>
      right_option + p
    </td>
    <td>
      )
    </td>
  </tr>
  
  <tr>
    <td colspan=3>
      Function Key
    </td>
  </tr>
  <tr>
    <td>
      right_option + 1
    </td>
    <td>
      F1
    </td>
  </tr>
  <tr>
    <td>
      right_option + 2
    </td>
    <td>
      F2
    </td>
  </tr>
  <tr>
    <td>
      right_option + 3
    </td>
    <td>
      F3
    </td>
  </tr>
  <tr>
    <td>
      right_option + 4
    </td>
    <td>
      F4
    </td>
  </tr>
  <tr>
    <td>
      right_option + 5
    </td>
    <td>
      F5
    </td>
  </tr>
  <tr>
    <td>
      right_option + 6
    </td>
    <td>
      F6
    </td>
  </tr>
  <tr>
    <td>
      right_option + 7
    </td>
    <td>
      F7
    </td>
  </tr>
  <tr>
    <td>
      right_option + 8
    </td>
    <td>
      F8
    </td>
  </tr>
  <tr>
    <td>
      right_option + 9
    </td>
    <td>
      F9
    </td>
  </tr>
  <tr>
    <td>
      right_option + 0
    </td>
    <td>
      F12
    </td>
  </tr>
  <tr>
    <td colspan=2>
      ブラウザ等のコントロール
    </td>
  </tr>
  <tr>
    <td>
      right_option + h
    </td>
    <td>
      command + ← (戻る)
    </td>
  </tr>
  <tr>
    <td>
      right_option + j
    </td>
    <td>
      shift + control + tab (前のタブ)
    </td>
  </tr>
  <tr>
    <td>
      right_option + k
    </td>
    <td>
      control + tab (次のタブ)
    </td>
  </tr>
  <tr>
    <td>
      right_option + l
    </td>
    <td>
      command + → (進む)
    </td>
  </tr>
</table>


## US
<table>
  <tr>
    <th>
      キーバインド
    </th>
    <th>
      置き換え後
    </th>
  </tr>

  <tr>
    <td colspan=2>
      キーバインドの変更
    </td>
  </tr>
  <tr>
    <td>
      caps lock
    </td>
    <td>
      left_control
    </td>
  </tr>
  <tr>
    <td>
      space 長押し
    </td>
    <td>
      right_option
    </td>
  </tr>

  <tr>
    <td colspan=2>
      カーソル移動
    </td>
  </tr>
  <tr>
    <td>
      left_commend + h
    </td>
    <td>
      ←（カーソル左）
    </td>
  </tr>
  <tr>
    <td>
      left_commend + j
    </td>
    <td>
      ↓（カーソル下）
    </td>
  </tr>
  <tr>
    <td>
      left_commend + k
    </td>
    <td>
      ↑（カーソル上）
    </td>
  </tr>
  <tr>
    <td>
      left_commend + l
    </td>
    <td>
      →（カーソル右）
    </td>
  </tr>
  <tr>
    <td>
      left_commend + n
    </td>
    <td>
      left_command + ← (Home)
    </td>
  </tr>
  <tr>
    <td>
      left_commend + m
    </td>
    <td>
      left_command + → (End)
    </td>
  </tr>


  <tr>
    <td colspan=2>
      よく使うキー
    </td>
  </tr>
  <tr>
    <td>
      left_commend + d
    </td>
    <td>
      delete(back space)
    </td>
  </tr>  
  <tr>
    <td>
      left_commend + f
    </td>
    <td>
      Esc
    </td>
  </tr>
  <tr>
    <td>
      left_commend + space
    </td>
    <td>
      Enter
    </td>
  </tr>
  <tr>
    <td colspan=2>
      英数・かな 変換
    </td>
  </tr>
  <tr>
    <td>
      left_commend (単押し)
    </td>
    <td>
      英数
    </td>
  </tr>
  <tr>
    <td>
      right_commend (単押し)
    </td>
    <td>
      かな
    </td>
  </tr>
  <tr>
    <td colspan=2>
      カーソル等の移動系（あると便利なキー）
    </td>
  </tr>
  <tr>
    <td>
      left_commend + right_command + h
    </td>
    <td>
      option + ←（単語単位でカーソル左）
    </td>
  </tr>
  <tr>
    <td>
      left_commend + right_command + j
    </td>
    <td>
      page up
    </td>
  </tr>
  <tr>
    <td>
      left_commend + right_command + k
    </td>
    <td>
      page down
    </td>
  </tr>
  <tr>
    <td>
      left_commend + right_command + l
    </td>
    <td>
      option + →（単語単位でカーソル右）
    </td>
  </tr>
  <tr>
    <td colspan=2>
      記号系
    </td>
  </tr>
  <tr>
    <td>
      right_option + a
    </td>
    <td>
      _
    </td>
  </tr>
  <tr>
    <td>
      right_option + s
    </td>
    <td>
      +
    </td>
  </tr>
  <tr>
    <td>
      right_option + d
    </td>
    <td>
      delete(カーソル右の文字を削除)
    </td>
  </tr>
  <tr>
    <td>
      right_option + f
    </td>
    <td>
      -
    </td>
  </tr>
  <tr>
    <td>
      right_option + g
    </td>
    <td>
      =
    </td>
  </tr>
  <tr>
    <td>
      right_option + v
    </td>
    <td>
      /
    </td>
  </tr>
  <tr>
    <td>
      right_option + b
    </td>
    <td>
      `
    </td>
  </tr>
  <tr>
    <td>
      right_option + q
    </td>
    <td>
      !
    </td>
  </tr>
  <tr>
    <td>
      right_option + w
    </td>
    <td>
      @
    </td>
  </tr>
  <tr>
    <td>
      right_option + e
    </td>
    <td>
      #
    </td>
  </tr>
  <tr>
    <td>
      right_option + r
    </td>
    <td>
      $
    </td>
  </tr>
  <tr>
    <td>
      right_option + t
    </td>
    <td>
      %
    </td>
  </tr>
  <tr>
    <td>
      right_option + y
    </td>
    <td>
      ^
    </td>
  </tr>
  <tr>
    <td>
      right_option + u
    </td>
    <td>
      &
    </td>
  </tr>
  <tr>
    <td>
      right_option + i
    </td>
    <td>
      *
    </td>
  </tr>
  <tr>
    <td>
      right_option + o
    </td>
    <td>
      (
    </td>
  </tr>
  <tr>
    <td>
      right_option + p
    </td>
    <td>
      )
    </td>
  </tr>
  <tr>
    <td colspan=3>
      Function Key
    </td>
  </tr>
  <tr>
    <td>
      right_option + 1
    </td>
    <td>
      F1
    </td>
  </tr>
  <tr>
    <td>
      right_option + 2
    </td>
    <td>
      F2
    </td>
  </tr>
  <tr>
    <td>
      right_option + 3
    </td>
    <td>
      F3
    </td>
  </tr>
  <tr>
    <td>
      right_option + 4
    </td>
    <td>
      F4
    </td>
  </tr>
  <tr>
    <td>
      right_option + 5
    </td>
    <td>
      F5
    </td>
  </tr>
  <tr>
    <td>
      right_option + 6
    </td>
    <td>
      F6
    </td>
  </tr>
  <tr>
    <td>
      right_option + 7
    </td>
    <td>
      F7
    </td>
  </tr>
  <tr>
    <td>
      right_option + 8
    </td>
    <td>
      F8
    </td>
  </tr>
  <tr>
    <td>
      right_option + 9
    </td>
    <td>
      F9
    </td>
  </tr>
  <tr>
    <td>
      right_option + 0
    </td>
    <td>
      F12
    </td>
  </tr>
  <tr>
    <td colspan=3>
      ブラウザ等のコントロール
    </td>
  </tr>
  <tr>
    <td>
      right_option + h
    </td>
    <td>
      command + ← (戻る)
    </td>
  </tr>
  <tr>
    <td>
      right_option + j
    </td>
    <td>
      shift + control + tab (前のタブ)
    </td>
  </tr>
  <tr>
    <td>
      right_option + k
    </td>
    <td>
      control + tab (次のタブ)
    </td>
  </tr>
  <tr>
    <td>
      right_option + l
    </td>
    <td>
      command + → (進む)
    </td>
  </tr>
</table>











