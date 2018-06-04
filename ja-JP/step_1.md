### NOOBSのダウンロード

SDカードにRaspbianをインストールする最も簡単な方法は、NOOBSを使用することです。 NOOBSのコピーを入手するには：

+ [訪問www.raspberrypi.org/downloads/](https://www.raspberrypi.org/downloads/)

![ダウンロードページ](images/downloads-page.png)

+ NOOBSファイルへのリンクがあるボックスが表示されます。 リンクをクリックしてください。

![NOOBSをクリック](images/click-noobs.png)

+ 最も簡単な方法は、ファイルのzipアーカイブをダウンロードすることです。

![zipをダウンロード](images/download-zip.png)

### SDカードのフォーマット

RaspbianをインストールするSDカードに現在Raspbianの古いバージョンがある場合は、このプロセス中に上書きされるため、カードからファイルをバックアップすることをお勧めします。

+ SD Associationのウェブサイトにアクセスし、WindowsまたはMac用に [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html) をダウンロードしてください。

+ 指示に従って、ソフトウェアをインストールします。

+ SDカードをコンピュータまたはラップトップのSDカードリーダーに挿入し、割り当てられたドライブ文字を書き留めます（例： `F：/`。

+ SDフォーマッタで、SDカードのドライブ文字を選択してフォーマットします。

### zipアーカイブからNOOBSを抽出する

次に、Raspberry PiのWebサイトからダウンロードしたNOOBS zipアーカイブからファイルを抽出する必要があります。

+ *Downloads* フォルダに移動し、ダウンロードしたzipファイルを探します。

+ ファイルを抽出し、エクスプローラ/ Finderウィンドウを開いたままにしておきます。

### ファイルのコピー

+ 次に、別のExplorer / Finderウィンドウを開き、SDカードに移動します。 2つのウィンドウを並べて配置することをお勧めします。

+ *NOOBS* フォルダからすべてのファイルを選択し、SDカードにドラッグします。

![ウィンドウコピー](images/copy3.png)

![macosコピー](images/macos_copy.png)

+ SDカードを取り出します。

### NOOBSから起動する

+ ファイルがコピーされたら、Raspberry PiにマイクロSDカードを挿入し、Piを電源に差し込みます。

+ インストーラがロードされたら、選択肢が表示されます。 **Raspbian**チェックボックスをオンにして、 **Install**クリックします。

![インストール](images/install.png)

+ 警告ダイアログで **** してから、座ってリラックスしてください。 それはしばらく時間がかかりますが、Raspbianがインストールされます。

![インストールする](images/installing.png)

+ Raspbianがインストールされている場合は、クリックしてください **OK** 、あなたラズベリーパイが再起動し、Raspbianは、その後起動します。

![インストール済み](images/installed.png)