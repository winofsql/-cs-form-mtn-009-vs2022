# cs-form-mtn-009-vs2022

### 入れ子機能( Web ) を使用した機能のソース分割( partial )

![image](https://github.com/winofsql/cs-form-mtn-009-vs2022/assets/1501327/e68c31c7-8b00-4e8c-9f7f-75ed0a0b058e)

- ### 構成
  - Form1.cs 
    - グローバルメソッド
  - Form1.Action.cs
    - ボタンによる処理イベント
  - Form1.Taskbar.cs
    - Validating によるチェック
  - Form1.Events.cs
    - 特殊なイベント処理( キーボード 関係等 )
  - Form1.Taskbar.cs
    - ステータスバーのメッセージ処理
