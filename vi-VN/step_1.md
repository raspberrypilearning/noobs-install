### Tải xuống NOOBS

Sử dụng NOOBS là cách dễ nhất để cài đặt Raspbian trên thẻ SD của bạn. Để tải một bản sao của NOOBS:

+ Truy cập [www.raspberrypi.org/downloads/](https://www.raspberrypi.org/downloads/)

![Trang tải xuống](images/downloads-page.png)

+ Bạn sẽ thấy một khung có liên kết đến các file NOOBS. Nhấp vào đường dẫn.

![Nhấp vào NOOBS](images/click-noobs.png)

+ Tùy chọn đơn giản nhất là tải xuống file nén zip của các tệp tin.

![Tải xuống file nén zip](images/download-zip.png)

### Định dạng thẻ SD

Nếu thẻ SD mà bạn muốn dùng để cài đặt Raspbian đang có phiên bản cũ hơn của Raspbian, bạn có thể muốn sao lưu các tệp từ thẻ trước khi tiếp tục, vì chúng sẽ bị ghi đè trong quá trình này.

+ Truy cập trang web của SD Association và tải xuống [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html) cho Windows hoặc Mac.

+ Làm theo hướng dẫn để cài đặt phần mềm.

+ Lắp thẻ SD của bạn vào đầu đọc thẻ SD của máy tính hoặc máy tính xách tay và ghi chú ký tự ổ đĩa được cấp cho nó, ví dụ: `F:/`.

+ Trong SD Formatter, chọn ký tự ổ đĩa cho thẻ SD của bạn và định dạng nó.

### Trích xuất NOOBS từ file nén zip

Tiếp theo, bạn sẽ cần giải nén các tệp từ file nén zip NOOBS mà bạn đã tải xuống từ trang web Raspberry Pi.

+ Chuyển tới thư mục *Tải xuống* của bạn và tìm tệp zip bạn đã tải xuống.

+ Giải nén các tập tin và giữ cửa sổ Explorer/Finder mở.

### Sao chép các tập tin

+ Bây giờ mở một cửa sổ Explorer / Finder khác và điều hướng đến thẻ SD. Tốt nhất nên đặt hai cửa sổ cạnh nhau.

+ Chọn tất cả các tệp từ thư mục *NOOBS* và kéo chúng vào thẻ SD.

![windows copy](images/copy3.png)

![macos copy](images/macos_copy.png)

+ Eject thẻ SD bằng Explorer/Finder.

### Khởi động từ NOOBS

+ Một khi các tập tin đã được sao chép, đưa thẻ micro SD vào Raspberry Pi của bạn, và cắm Pi vào nguồn điện.

+ Bạn sẽ được cung cấp một lựa chọn khi trình cài đặt đã được khởi động. Bạn nên tích vào lựa chọn **Raspbian**, sau đó bấm **Install**.

![cài đặt](images/install.png)

+ Nhấp vào **Yes** tại hộp thoại cảnh báo, sau đó ngồi và thư giãn. Nó sẽ mất một lúc, nhưng Raspbian sẽ cài đặt.

![cài đặt](images/installing.png)

+ Khi Raspbian đã được cài đặt, nhấp vào **OK** và Raspberry Pi của bạn sẽ khởi động lại và Raspbian sau đó sẽ khởi động.

![Cài đặt](images/installed.png)