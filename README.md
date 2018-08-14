## Linux用? CLI ナウキャスト
* CLIからナウキャストで天気の現在の状況を閲覧するスクリプト。
* 場所は関東地方周辺のみ。
* 画像ビューアに [eog](https://help.gnome.org/users/eog/stable/index.html.ja) を使用。
* 10分ほどの誤差は存在する、という仕様。

### How to use?

```bash
1. $ git clone git@github.com:matt-note/nau.git
2. $ chmod +x nau/nau
3. $ sudo cp nau/nau /usr/local/bin
4. $ nau
```
* 例:  
![201808132140-00.png](https://github.com/matt-note/nau/blob/master/201808132140-00.png)
* 画像サイズは 25kB ほど。  
![img-size.png](https://github.com/matt-note/nau/blob/master/img-size.png)

## 補足事項
* 9:10 や 9:20 など、1ケタが 0 の時に実行した時に、そもそも画像引用元で画像が作られていない場合がある。  
その場合は、画像の取得に失敗する。  
その時は、1分ほど待ってから実行すれば、問題なく画像を取得できる。
