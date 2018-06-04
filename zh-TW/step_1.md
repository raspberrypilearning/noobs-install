### 正在下載NOOBS

使用NOOBS是在您的SD卡上安裝Raspbian的最簡單方法。 拿到一份NOOBS的副本：

+ 訪問 [www.raspberrypi.org/downloads/](https://www.raspberrypi.org/downloads/)

![下載頁面](images/downloads-page.png)

+ 您應該看到一個帶有NOOBS文件鏈接的框。 點擊鏈接。

![點擊NOOBS](images/click-noobs.png)

+ 最簡單的選擇是下載文件的zip存檔。

![下載zip](images/download-zip.png)

### 格式化SD卡

如果您想要安裝Raspbian的SD卡目前已經安裝了較舊版本的Raspbian，則您可能希望首先備份卡上的文件，因為在此過程中它們將被覆蓋。

+ 訪問SD協會的網站並下載適用於Windows或Mac的 [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html)。

+ 按照說明安裝軟件。

+ 將SD卡插入計算機或筆記本電腦的SD卡讀卡器，並記下分配給它的驅動器號，例如 `F：/`。

+ 在SD Formatter中，選擇SD卡的驅動器號並格式化。

### 從zip壓縮文件中提取NOOBS

接下來，您需要從您從Raspberry Pi網站下載的NOOBS zip壓縮文件中提取文件。

+ 轉到您的 *下載* 文件夾並找到您下載的zip文件。

+ 提取文件並保持打開的結果瀏覽器/查找程序窗口。

### 複製文件

+ 現在打開另一個Explorer / Finder窗口並導航到SD卡。 最好將兩個窗口並排放置。

+ 從 *NOOBS* 文件夾中選擇所有文件並將它們拖到SD卡上。

![窗口復制](images/copy3.png)

![馬科斯副本](images/macos_copy.png)

+ 彈出SD卡。

### 從NOOBS啟動

+ 一旦文件被複製完畢，將micro SD卡插入Raspberry Pi，然後將Pi插入電源。

+ 安裝程序加載完成後，您將獲得一個選擇。 您應該勾選 **Raspbian**的框，然後單擊 **Install**。

![安裝](images/install.png)

+ 在警告對話框中點擊 **是** ，然後坐下放鬆。 這將需要一段時間，但Raspbian將安裝。

![安裝](images/installing.png)

+ 當安裝Raspbian時，點擊 **OK** ，你的Raspberry Pi將重新啟動，然後Raspbian將啟動。

![安裝](images/installed.png)