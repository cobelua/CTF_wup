Tải và mở file image

Cài đặt stegseek
<img width="720" height="175" alt="image" src="https://github.com/user-attachments/assets/76f93bd4-76a9-4f64-ade0-1389c268d7ae" />


Sau đó exiftool để kiểm tra metadata
<img width="607" height="428" alt="image" src="https://github.com/user-attachments/assets/a71117bb-4a97-46d8-bd1f-1a8c99ea4993" />


Tìm được đoạn mã
<img width="571" height="22" alt="image" src="https://github.com/user-attachments/assets/8a8f4630-43fe-44ff-97b6-cf9e8fb134f1" />


Vào cyberchef để đổi đoạn mã từ base64
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e2ff1871-b92f-42f5-8b7b-8d5b46af5f0d" />


Đổi tiếp đoạn mã nhận được từ base64.Sẽ thu được passphrase
<img width="1211" height="411" alt="image" src="https://github.com/user-attachments/assets/a1dd41cc-c1f9-4d4f-90ec-e75accf18d6f" />


Sau đó dùng steghide để kiểm tra dữ liệu ẩn trong file. Và nhập passphrase vừa tìm được. Và tìm được file bị ẩn.
<img width="482" height="190" alt="image" src="https://github.com/user-attachments/assets/2b11b15c-97dc-46db-9ab7-94b4a055fa1b" />

Dùng lệnh cat để hiển thị nội dung file bị ẩn đó. Và từ nội dung file tìm được flag
<img width="299" height="71" alt="image" src="https://github.com/user-attachments/assets/9526a2cc-51fa-478e-8801-4fe673851e34" />









