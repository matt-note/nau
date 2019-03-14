## nau
* 現在の天気の状況を閲覧するbashスクリプト。(Ubuntu用)
* 画像はナウキャストの画像を使用。
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
![201808132140-00](https://user-images.githubusercontent.com/39484102/54285086-9c616780-45e4-11e9-9282-a55681ecb786.png)
* 画像サイズは 25kB ほど。  
![img-size](https://user-images.githubusercontent.com/39484102/54285089-9e2b2b00-45e4-11e9-82e1-888d1b4021ce.png)

## 補足事項
* 9:10 や 9:20 など、1ケタが 0 の時に実行すると、そもそも画像引用元で画像が作られていない場合がある。  
その場合は、画像の取得に失敗する。  
その時は、少し待ってから実行すれば、問題なく画像を取得できる。
