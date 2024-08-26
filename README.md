Cài đặt ESP32, ESP8266 Board,
cho Arduino IDE

1.	Yêu cầu: đã cài đặt sẵn Arduino IDE

2.	Để cài đặt board ESP32, ESP8266 cho Arduino IDE của bạn, hãy làm theo các hướng dẫn tiếp theo sau

2.1 Trong Arduino IDE của bạn, đi tới File > Preferences
 
-Nhập https://dl.espressif.com/dl/package_esp32_index.json , https://arduino.esp8266.com/stable/package_esp8266com_index.json
vào chỗ “Additional Board Manager URLs” như hình bên dưới. Kế đó, click nút “OK”:
 
-Lưu ý:  tách các URL bằng dấu phẩy như sau:
3.	https://dl.espressif.com/dl/package_esp32_index.json , https://arduino.esp8266.com/stable/package_esp8266com_index.json









2.2  Mở Manager, Đi tới Tools > Board > Boards Manager…
 



- Search từ khóa “ESP32” và nhấn nút cài đặt (install) cho “ESP32 by Espressif Systems”:
 


-	Tiếp tục với esp8266
 
4.	5. Vậy đó, nó sẽ được cài đặt sau một vài giây.


Kiểm tra sau khi cài đặt
Cắm board mạch ESP32 vào máy tính của bạn. Mở sẵn Arduino IDE của bạn và làm theo các bước sau:
1.	Chọn Board của bạn trong menu Tools > Board (trong trường hợp của tôi, đó là DOIT  ESP32 DEVKIT V1)
2.	Board esp32, esp8266 đã hiện lên
 
2. Chọn Port (nếu bạn không tìm thấy COM Port trong Arduino IDE của mình, bạn cần cài đặt thêm CP210x USB to UART Bridge VCP Drivers , hoặc CH340):
 

Lưu ý : modul esp32 hay esp8266 sài ic CH340 hay CP210x thì ta cài driver đó để nhận được COM ( vào device manager để kiểm tra COM đã nhận chưa)
5.	https://www.arduined.eu/files/windows10/CH341SER.zip
https://www.silabs.com/documents/public/software/CP210x_Windows_Drivers.zip



THANK YOU SO MUCH

