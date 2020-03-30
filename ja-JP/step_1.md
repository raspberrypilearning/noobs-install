### NOOBSのダウンロード

SDカードにRaspbianをインストールする最も簡単な方法は、NOOBSを使用することです。 NOOBSのコピーを入手するには：

+ リンク先をご覧ください[www.raspberrypi.org/downloads/](https://www.raspberrypi.org/downloads/)

![ダウンロードページ](images/downloads-page.png)

+ NOOBSファイルへのリンクが設定されたボックスが表示されます。 リンクをクリックしてください。

![NOOBSをクリック](images/click-noobs.png)

+ 最も簡単な方法は、ファイルのzipアーカイブをダウンロードすることです。

![Zip形式でダウンロード](images/download-zip.png)

### SDカードのフォーマット

RaspbianをインストールしようとしているSDカードに既に古いバージョンのRaspbianがインストールされている場合、このプロセス中に上書きされるため、SDカードからファイルをバックアップすることをお勧めします。

+ SD Associationのウェブサイトにアクセスし、WindowsまたはMac用に [SDメモリカードフォーマッタ―](https://www.sdcard.org/downloads/formatter_4/index.html) をダウンロードしてください。

+ 指示に従って、ソフトウェアをインストールします。

+ SDカードをコンピュータまたはラップトップのSDカードリーダーに挿入し、割り当てられたドライブレターを書き留めます（例： `F:/`。

+ SDメモリカードフォーマッターで、SDカードのドライブレターを選択してフォーマットします。

### ZipアーカイブからNOOBSを抽出する

次に、Raspberry PiのWebサイトからダウンロードしたNOOBS zipアーカイブからファイルを抽出する必要があります。

+ *ダウンロード* フォルダに移動し、ダウンロードしたzipファイルを探します。

+ ファイルを抽出し、エクスプローラー/ Finderウィンドウを開いたままにしておきます。

### ファイルのコピー

+ 次に、別のエクスプローラー / Finderウィンドウを開き、SDカードに移動します。 2つのウィンドウを並べて配置することをお勧めします。

+ *NOOBS* フォルダからすべてのファイルを選択し、SDカードにドラッグします。

![Windowsでコピー](images/copy3.png)

![MacOSでコピー](images/macos_copy.png)

+ SDカードを取り出します。

### NOOBSから起動する

+ ファイルがコピーされたら、Raspberry PiにSDカードを挿入し、Raspberry Piに電源を接続します。

+ インストーラがロードされたら、選択肢が表示されます。 **Raspbian**チェックボックスをオンにして、 **Install**クリックします。

![インストール](images/install.png)

+ 警告ダイアログで **Yes** をクリックし、座ってリラックスしてください。 しばらく時間がかかりますが、Raspbianがインストールされます。

![インストール中](images/installing.png)

+ Raspbianがインストールされたら、**OK**ボタンをクリックしてください 。Rasbperry Piが再起動し、Raspbianが起動します。

![インストール完了](images/installed.png)