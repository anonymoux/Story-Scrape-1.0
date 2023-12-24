# Story-Scrape-1.0

Chức năng:
- Get truyện trên các trang lớn như: truyenfull, dtruyen, tangthuvien, wattpad. Hiện hoạt động tốt với truyenfull
- Tự động phân biệt nguồn lấy truyện và chạy scrape tất cả các chương
- Định dạng lại văn bản (xoá dòng thừa, thụt đầu dòng)
- Đóng gói lại file Word (.docx), tạo Heading cho từng chương để tạo mục lục tự động.
Có file .docx rồi thì ném sang Calibre để convert sang các định dạng khác như EPUB, AMZW, PDF...

**Hướng dẫn:**
1. Cài chrome bản mới nhất
2. Tải chromdriver về giải nén lấy file .exe rồi copy vào C:\Windows\System32
   Link: [https://edgedl.me.gvt1.com/edgedl/chrome/chrome-for-testing/120.0.6099.71/win64/chrome-win64.zip](https://googlechromelabs.github.io/chrome-for-testing/#stable)
   Nhớ chọn đúng win32 hoặc 64, và phiên bản Stable mới nhất.
3. Tải file Story Scraper 1.0.1 by Phat.exe
4. Chạy tool, ở phần url dán vào đường dẫn đến chương 1 của truyện
5. Nhấn Scrape để lấy toàn bộ nội dung chương, lưu ý khi ấn vào scrape xong thì buông chuột và bàn phím ra, để tool tự động get. Nhìn vào màn hình đen để biết tiến trình tới đâu rồi.
6. Sau khi đã get xong các chương, nhấn nút tạo file .docx. Xong
