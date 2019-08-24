# Ruby ハードウェアプログラミング体験会

## 資料へのリンク

* [RaspberryPi初期設定](RaspberryPi初期設定.md)
* [RaspberryPiの基本知識](RaspberryPiの基本知識.md)
  * RaspberryPi の PIN 配置図を載せています。回路を作成するときに参考にしてください。
* [プロジェクトフォルダ作成](プロジェクトフォルダ作成.md)
* [用語集](用語集.md)

## 教材

### 1日目

* [Lチカ](Lチカ.md)
* [圧電スピーカー](圧電スピーカー.md)
* [モーターを動かす](モーターを動かす.md)
* [モーターを正転・逆転する](モーターを正転・逆転する.md)

### 2日目

(Coming soon)

* スイッチ入力
* フォトトランジスターとADコンバーターの説明
* フォトトランジスターから値取得
* Railsアプリにセンサーの値を表示

### 3日目

(Coming soon)

* 距離センサーとADコンバーターの説明
* 距離センサーから値を取得
* 戦車を動かす

```bash
ssh pi@r-000.local で ssh ログイン
# pw: raspberry
sudo su -
echo "edu ALL=(ALL) NOPASSWD: ALL" > /etc/sudoers.d/010_edu-nopasswd
exit # pi からログアウト
edu@r-000.local で ssh ログイン
# pw: liberty
```
