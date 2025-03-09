Installing ESP32 and ESP8266 Boards in Arduino IDE
==================================================

**Prerequisite**: Arduino IDE is already installed on your computer.

To set up ESP32 and ESP8266 boards in Arduino IDE, follow the detailed steps below.

* * * * *

1\. Add Board Manager URLs to Arduino IDE
-----------------------------------------

1.  Open Arduino IDE and go to **File > Preferences**.
2.  In the **Additional Board Manager URLs** field, enter the following links:

    text

    CollapseWrapCopy

    `https://dl.espressif.com/dl/package_esp32_index.json, https://arduino.esp8266.com/stable/package_esp8266com_index.json`

    -   **Note**: Separate the URLs with a **comma** (,).
3.  Click **OK** to save the changes.

* * * * *

2\. Install ESP32 and ESP8266 Boards
------------------------------------

1.  Go to **Tools > Board > Boards Manager**.
2.  In the search bar, type **"ESP32"**.
    -   Find **"ESP32 by Espressif Systems"** and click **Install**.
3.  Next, search for **"ESP8266"**.
    -   Find **"ESP8266 by ESP8266 Community"** and click **Install**.
4.  Wait a few seconds for the installation to complete.

* * * * *

3\. Verify and Configure After Installation
-------------------------------------------

1.  **Connect the board**:
    -   Plug your ESP32 or ESP8266 board into your computer via a USB cable.
2.  **Open Arduino IDE**:
    -   Go to **Tools > Board**.
    -   Check if the board list now includes options like **DOIT ESP32 DEVKIT V1** (for ESP32) or **NodeMCU** (for ESP8266).
    -   Select the appropriate board for your hardware (e.g., **DOIT ESP32 DEVKIT V1**).
3.  **Select Port**:
    -   Go to **Tools > Port** and choose the COM port corresponding to your board (e.g., COM3).
    -   **Note**: If no COM port appears:
        -   Open **Device Manager** to check if your board uses a **CH340** or **CP210x** chip.
        -   Download and install the appropriate driver:
            -   **CH340 Driver**: [Download here](https://www.arduined.eu/files/windows10/CH341SER.zip)
            -   **CP210x Driver**: [Download here](https://www.silabs.com/documents/public/software/CP210x_Windows_Drivers.zip)
        -   Restart Arduino IDE and recheck the COM port after installing the driver.

* * * * *

4\. Completion
--------------

Once the steps above are complete:

-   The ESP32 and ESP8266 boards are successfully installed in Arduino IDE.
-   You're ready to start programming and uploading code to your board.

If you encounter any issues, double-check the USB connection, driver installation, or refer to official documentation from [Espressif](https://docs.espressif.com) or [ESP8266 Community](https://arduino-esp8266.readthedocs.io).

**Thank you for following along!** Happy coding with your ESP32 and ESP8266 projects!



--------------
--------------


Hướng Dẫn Cài Đặt ESP32 và ESP8266 Board cho Arduino IDE
========================================================

Yêu cầu: Bạn đã cài đặt sẵn **Arduino IDE** trên máy tính.

Để tích hợp board ESP32 và ESP8266 vào Arduino IDE, hãy làm theo các bước chi tiết dưới đây.

* * * * *

1\. Thêm URL Quản Lý Board vào Arduino IDE
------------------------------------------

1.  Mở Arduino IDE, vào menu **File > Preferences** (Tệp > Tùy chọn).
2.  Trong phần **Additional Board Manager URLs** (URL Trình quản lý Board bổ sung), nhập các liên kết sau:

    text

    CollapseWrapCopy

    `https://dl.espressif.com/dl/package_esp32_index.json, https://arduino.esp8266.com/stable/package_esp8266com_index.json`

    -   **Lưu ý**: Các URL cần được phân tách bằng **dấu phẩy** (,).
3.  Nhấn **OK** để lưu thay đổi.

* * * * *

2\. Cài Đặt Board ESP32 và ESP8266
----------------------------------

1.  Vào menu **Tools > Board > Boards Manager** (Công cụ > Bảng > Trình quản lý Board).
2.  Trong thanh tìm kiếm, nhập từ khóa **"ESP32"**.
    -   Tìm mục **"ESP32 by Espressif Systems"** và nhấn **Install** (Cài đặt).
3.  Tiếp tục tìm từ khóa **"ESP8266"**.
    -   Tìm mục **"ESP8266 by ESP8266 Community"** và nhấn **Install** (Cài đặt).
4.  Chờ vài giây để quá trình cài đặt hoàn tất.

* * * * *

3\. Kiểm Tra và Cấu Hình Sau Khi Cài Đặt
----------------------------------------

1.  **Kết nối board**:
    -   Cắm board ESP32 hoặc ESP8266 vào máy tính qua cáp USB.
2.  **Mở Arduino IDE**:
    -   Vào menu **Tools > Board** (Công cụ > Bảng).
    -   Kiểm tra xem danh sách board đã hiển thị các tùy chọn như **DOIT ESP32 DEVKIT V1** (cho ESP32) hoặc **NodeMCU** (cho ESP8266) chưa.
    -   Chọn board phù hợp với phần cứng của bạn (ví dụ: **DOIT ESP32 DEVKIT V1**).
3.  **Chọn Port**:
    -   Vào menu **Tools > Port** (Công cụ > Cổng) và chọn cổng COM tương ứng với board của bạn (ví dụ: COM3).
    -   **Lưu ý**: Nếu không thấy cổng COM:
        -   Kiểm tra trong **Device Manager** (Trình quản lý thiết bị) để xác định board dùng chip **CH340** hay **CP210x**.
        -   Tải và cài đặt driver tương ứng:
            -   **CH340 Driver**: [Tải tại đây](https://www.arduined.eu/files/windows10/CH341SER.zip)
            -   **CP210x Driver**: [Tải tại đây](https://www.silabs.com/documents/public/software/CP210x_Windows_Drivers.zip)
        -   Sau khi cài driver, khởi động lại Arduino IDE và kiểm tra lại cổng COM.

* * * * *

4\. Hoàn Thành
--------------

Sau khi hoàn tất các bước trên:

-   Board ESP32 và ESP8266 đã được cài đặt thành công trong Arduino IDE.
-   Bạn có thể bắt đầu lập trình và tải code lên board.

Nếu gặp vấn đề, hãy kiểm tra lại kết nối USB, driver, hoặc tham khảo tài liệu chính thức từ [Espressif](https://docs.espressif.com) hoặc [ESP8266 Community](https://arduino-esp8266.readthedocs.io).

**Cảm ơn bạn đã theo dõi!** Chúc bạn thành công với dự án của mình!