<h1>Dự án Khoa Học Kĩ Thuật 2022 - Hệ thống phát hiện việc sử dụng Vape trong trường học</h1>
<img src="https://i.ibb.co/0qHVHjg/Initial-Letter-D-Digital-Logo-Design-Template.png" style="height: 200px; width: 200px;">
<h3>🔗 > Mô tả chung dự án</h3>
<p>Hệ thống phát hiện việc sử dụng Vape trong trường học hay còn gọi là Vaping Detection System (VDS) là một dự án kết hợp của Hệ thống nhúng, Lưu trữ đám mây và Lập trình Web.</p>
<h3>💻 > Các công nghệ được sử dụng</h3>
<p>
Có 2 phần chính trong dự án này: Bộ cảm biến và Website
<ul>
  <li>Bộ cảm biến sử dụng Raspberry Pi và Arduino Nano. Hoạt động bằng cách mỗi khi phát hiện được các thông số bất thường, Module Arduino Nano sẽ đưa thông tin về Raspberry Pi qua phương thức pyFirmata và sau đó dữ liệu được đưa lên MongoDB dưới dạng JSON.</li>
  <li>Phần Website sử dụng framework Flask của Python để tạo nên một Website có phần backend có thể lấy dữ liệu từ MongoDB và hiển thị. Website được host trên Heroku với URL là: <a href="https://khkt2022.herokuapp.com">khkt2022.herokuapp.com</a></li>
</ul>
</p>
<h3>⌨️ > Các hình ảnh</h3>
<p>
<h5>CLI Cảm biến</h5>
<img src="https://i.ibb.co/XsJZsx7/Screenshot-2022-10-26-215542.png"><br>
<h5>Lời nhắn trên Discord</h5>
<img src="https://i.ibb.co/wLYKpzm/Screenshot-2022-10-26-215746.png"><br>
<h5>Trang Web</h5>
<img src="https://i.ibb.co/BfCgCZM/Screenshot-2022-10-26-215900.png"><br>
</p>
<h3>Tóm tắt lại</h3>
<p>
<ul>
  <li>Các công nghệ đã được sử dụng: Python, Flask (Framework), Arduino C</li>
  <li>Phần cứng: Raspberry Pi, Arduino Nano, Flying Fish MQ2 Gas Detector</li>
  <li>Webhook: Discord</li>
</ul>
</p>
