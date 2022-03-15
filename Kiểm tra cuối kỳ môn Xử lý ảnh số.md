# Kiểm tra cuối kỳ môn Xử lý ảnh số

### 1. Tham số nào liên quan đến số lượng ảnh khi xử lý video?

- [x]  FPS
- [ ]  Độ sáng
- [ ]  Độ tương phản
- [ ]  Kích thước video

### 2. Ảnh xám (grayscale image) sử dụng bao nhiêu bit/byte để biểu diễn mức xám?

- [ ]  1 bit
- [ ]  1 byte
- [ ]  255 bit
- [ ]  255 byte

### 3. Một không gian màu (color space) mô tả thông tin gì?

- [ ]  Các thành phần tạo nên màu
- [ ]  Số lượng kênh màu
- [ ]  Số lượng màu sắc có thể biểu diễn
- [x]  Tất cả các ý trên

### 4. Lý do sự tồn tại của nhiều hệ màu?

- [ ]  Nhu cầu sử dụng
- [ ]  Nhiều loại thiết bị
- [ ]  Sự chính xác khi so sánh trong các hệ màu
- [x]  Tất cả ý trên

### 5. Hệ màu nào mang lại sự so sánh màu phù hợp với con người hơn khi sử dụng? (so sánh sử dụng khoảng cách và biểu diễn điểm màu trong không gian)

- [ ]  RGB
- [ ]  HSV
- [ ]  Lab
- [ ]  CYMK

### 6. Hệ màu HSV được sử dụng thay cho RGB vì:

- [ ]  Dễ lựa chọn màu theo cách của con người
- [ ]  So sánh màu chính xác hơn
- [ ]  Tiết kiệm băng thông hơn
- [ ]  Tất cả đều đúng

### 7. Độ phân giải (resolution) của ảnh là 800x600, có nghĩa là:

- [x]  Rộng: 800, Cao: 600
- [ ]  Cao: 600, Rộng: 800
- [ ]  Tỉ lệ chiều rộng và và cao là 800:600
- [ ]  Độ tương phản:800 và độ sáng: 600

### 8. Ảnh vector (đồ họa vector - vector graphics) có đặc điểm gì?

- [ ]  Lưu trữ từng điểm ảnh để xử lý, phù hợp vẽ đối tượng đơn giản
- [ ]  Lưu trữ từng điểm ảnh để xử lý, phù hợp vẽ đối tượng phức tạp
- [x]  Lưu trữ mô hình đối tượng để xử lý, phù hợp vẽ đối tượng không quá phức tạp
- [ ]  Lưu trữ mô hình đối tượng để xử lý, phù hợp vẽ đối tượng tương đối phức tạp

### 9. Thông tin của ảnh nào không được thể hiện trong histogram?

- [ ]  Số lượng điểm ảnh
- [x]  Vị trí các điểm ảnh
- [ ]  Mức xám
- [ ]  Tất cả các ý trên

### 10. Cân bằng historgram (histogram equalization) là kỹ thuật dùng để:

- [ ]  Điều chỉnh độ sáng của ảnh
- [ ]  Điều chỉnh độ tương phản của ảnh
- [ ]  Giảm nhiễu trong ảnh
- [ ]  Thống kê điểm ảnh

### 11. Ứng dụng của histogram?

- [ ]  Ước lượng độ sáng của ảnh
- [ ]  Ước lượng độ tương phản của ảnh
- [ ]  Xác định vùng mức xám nổi trội nhất
- [x]  Tất cả ý trên

### 12. Tham số cần thiết khi thực hiện các phép xử lý hình thái là gì (morphological operations)

- [ ]  Kích thước ảnh
- [ ]  Bộ lọc (filter)
- [ ]  Độ phân giải
- [ ]  Phần tử cấu trúc

### 13. Lĩnh vực nghiên cứu thuật toán để vẽ một đường thẳng ra màn hình máy tính?

- [ ]  Xử lý ảnh số
- [ ]  Thị giác máy tính
- [x]  Đồ họa máy tính
- [ ]  Phân tích dữ liệu

### 14. Nén ảnh thuộc lĩnh vực nào?

- [x]  Xử lý ảnh số
- [x]  Thị giác máy tính
- [ ]  Đồ họa máy tính
- [ ]  Phân tích dữ liệu

### 15. Phép xử lý hình thái nào sau đây có thể dùng để khử nhiễu ảnh?

- [x]  Erosion, Opening
- [ ]  Dilation, Closing
- [ ]  Erosion, Dilation
- [ ]  Opening, Closing

### 16. Chọn biểu thức mô tả đúng phép xử lý hình thái Opening

- [ ]  Opening = Erosion(Dilation)
- [x]  Opening = Dilation(Erosion)
- [ ]  Opening = Closing(Dilation)
- [ ]  Opening = Dilation(Closing)

### 17. Các thuật toán phát hiện cạnh (edge detection) dựa trên đặc điểm gì của ảnh?

- [ ]  Sự khác biệt về mức xám tại các vùng của ảnh
- [ ]  Sự khác biệt về khoảng cách giữa các điểm ảnh giống nhau
- [ ]  Sự khác biệt về mức xám tại mỗi điểm
- [ ]  Sự khác biệt về đạo hàm cấp 1 của điểm ảnh

### 18. Ý nghĩa của đạo hàm cấp 1 được sử dụng trong phát hiện cạnh (edge detection)

- [ ]  Xác định vị trí tương quan giữa các điểm ảnh
- [ ]  Đo độ biến thiên cường độ sáng tại mỗi điểm
- [ ]  Xác định góc của cạnh tại mỗi điểm
- [ ]  Tất cả đều đúng

### 19. Trong thuật toán phát hiện cạnh (edge detection), các điểm thuộc cạnh có thể được xác định dựa vào đạo hàm nào của mức xám?

- [ ]  Đạo hàm cấp 1
- [ ]  Đạo hàm cấp 2
- [ ]  Đạo hàm cấp 1 hoặc Đạo hàm cấp 2
- [ ]  Đạo hàm cấp 1 và Đạo hàm cấp 2

### 20. Tại sao cần khử nhiễu ảnh trước khi thực hiện phát hiện cạnh?

- [ ]  Phép tích chập (convolution) ảnh hưởng bởi nhiễu
- [ ]  Kết quả đạo hàm bị ảnh hưởng bởi nhiễu
- [ ]  Dễ phát hiện cạnh trên ảnh đã blurred
- [ ]  Tất cả đều đúng

### 21. Chọn phát biểu đúng khi so sánh thuật toán phát hiện cạnh Sobel và Canny (egde detection)

- [ ]  Canny cho kết quả đầu ra là cạnh có độ rộng 1 pixel
- [ ]  Sobel dựa trên ngưỡng đơn, Canny sử dụng ngưỡng thấp và cao
- [ ]  Canny và Sobel đều dựa trên phương pháp xấp xỉ đạo hàm để tính độ mạnh của cạnh (edge strength)
- [x]  Tất cả đều đúng

### 22. Ưu điểm của việc sử dụng Hough Transform

- [ ]  Giới hạn được miền giá trị của không gian tham số
- [x]  Biểu diễn đường thẳng đơn giản hơn
- [ ]  Có thể biểu diễn mọi đường cong
- [ ]  Tất cả đều đúng

### 23. Thuật toán phát hiện đường thẳng bằng Hough Tranform có đặc điểm:

- [ ]  Các pixel thuộc đường thẳng phải liên tục
- [ ]  Số lượng pixel thuộc đường thẳng phải lớn hơn một ngưỡng
- [ ]  Các pixel thuộc đường thẳng phải có mức xám tương tự
- [ ]  Tất cả đều đúng

### 24. Lấy ngưỡng ảnh (thresholding) là kỹ thuật

- [ ]  Nâng cao độ tương phản
- [x]  Nhị phân hóa ảnh
- [ ]  Giảm nhiễu ảnh
- [ ]  Tách kênh màu

### 25. Đề xuất một phương pháp giải quyết cho bài toán lấy ngưỡng bị sai như hình dưới đây (ảnh gốc bên trái, ảnh sau lấy ngưỡng bên phải)

[https://lh6.googleusercontent.com/ggLTpnBMmUDyrhi9RWNpvd3KMk5nnVxN74ha6wxj-RlSM1tR3oLGuwB_aQt-pX1n_7GgXIOieeYtxBLBlaGwL2cliw7hUIX3IV-q3lbHA-SW68hWF4lb8XLTfbAMewVAtQ=w520](https://lh6.googleusercontent.com/ggLTpnBMmUDyrhi9RWNpvd3KMk5nnVxN74ha6wxj-RlSM1tR3oLGuwB_aQt-pX1n_7GgXIOieeYtxBLBlaGwL2cliw7hUIX3IV-q3lbHA-SW68hWF4lb8XLTfbAMewVAtQ=w520)

- [ ]  Sử dụng phương pháp Otsu
- [x]  Sử dụng phương pháp lấy ngưỡng thích ứng
- [ ]  Tăng độ sáng của ảnh
- [ ]  Tăng độ tương phản của ảnh

### 26. Đề xuất một phương pháp để lấp đầy phần màu đen trong vùng gương mặt màu trắng như hình dưới đây để được hình giống như hình bên phải nhất?

[https://lh4.googleusercontent.com/X141QCubgKbX5IMAQUUpbnjM6oLd5S0bKkBK1H5a6llWbE29ygjwedVZsGdj30UtTQ8tp6wjxX7cCFGUyOVZdkG7vtWbSSz-EQc0CFhVT8e_ZhLS5Idymy6TOvFAejUH9Q=w740](https://lh4.googleusercontent.com/X141QCubgKbX5IMAQUUpbnjM6oLd5S0bKkBK1H5a6llWbE29ygjwedVZsGdj30UtTQ8tp6wjxX7cCFGUyOVZdkG7vtWbSSz-EQc0CFhVT8e_ZhLS5Idymy6TOvFAejUH9Q=w740)

- [ ]  Dilation
- [ ]  Erosion
- [ ]  Opening
- [ ]  Closing

### 27. Cho ảnh nhị phân bên trái với 3 pixel (đen=sáng) như ảnh bên trái. Bảng T là mảng tích lũy (accumulator array) với rho và theta được chia sẵn. Hãy cho biết ô nào có số phiếu cao nhất theo thuật toán Hough Transform phát hiện đường thẳng? (ghi rho và theta)

[https://lh5.googleusercontent.com/0_pW0sofEquSdzDL8RJOJh2ylG7AT4bdrCctpIOtShR6ns5UcnEMymaUV6g3eXb4Q0SaDwGFcE0U_SGPvGwUfY5mLZ-nKTs_3PcoUBxcG7wz5etFtKgrOqipsIJt1ace7A=w740](https://lh5.googleusercontent.com/0_pW0sofEquSdzDL8RJOJh2ylG7AT4bdrCctpIOtShR6ns5UcnEMymaUV6g3eXb4Q0SaDwGFcE0U_SGPvGwUfY5mLZ-nKTs_3PcoUBxcG7wz5etFtKgrOqipsIJt1ace7A=w740)

- [ ]  (theta=pi/4, rho=2)
- [ ]  (theta=pi/4, rho=2sqrt(2))
- [ ]  (theta=3*pi/4, rho=2)
- [ ]  (theta=3*pi/4, rho=2sqrt(2))

### 28. Các tham số có thể thay đổi kết quả của thuật toán Canny?

- [ ]  Ngưỡng thấp và ngưỡng cao
- [ ]  Hệ số làm mờ ảnh
- [ ]  Bộ lọc được sử dụng để tính xấp xỉ đạo hàm
- [x]  Tất cả ý trên

### 29. Thực hiện tích chập (convolution) kernel bên phải lên ảnh bên trái tại vị trí số 6 (dòng 2, cột 2), kết quả trả về là: (không cần flip kernel)

[https://lh3.googleusercontent.com/AiBMU_76CaUx2uyeRULnbzLrRQNIVC946jpbkgZvXtAY_maWbu6DnmoAV657h4Zff9E9zS_HO4SMhsIc1EToqj19IoGGbZMjudGMWQoHprBdJGTIgxoVECW0VIdl08Tmlw=w430](https://lh3.googleusercontent.com/AiBMU_76CaUx2uyeRULnbzLrRQNIVC946jpbkgZvXtAY_maWbu6DnmoAV657h4Zff9E9zS_HO4SMhsIc1EToqj19IoGGbZMjudGMWQoHprBdJGTIgxoVECW0VIdl08Tmlw=w430)

- [ ]  2
- [ ]  4
- [ ]  6
- [x]  8

### 30. Phát hiện mặt người trong ảnh thuộc phạm vi nghiên cứu của:

- [ ]  Đồ họa máy tính
- [x]  Thị giác máy tính
- [ ]  Xử lý ảnh số
- [ ]  Xử lý dữ liệu lớn