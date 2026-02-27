# BUỔI 6: Cơ sở dữ liệu, Tìm kiếm và Đánh giá Độ tin cậy của Thông tin

**Môn học:** Cơ sở dữ liệu (hoặc Tin học đại cương / môn liên quan)  
**Trường:** Đại học Cần Thơ  
**Khoa:** Hệ thống thông tin  
**Năm học:** 2025-2026  

## Thông tin sinh viên

- **Thành viên**: Nguyễn Phát Đạt B2504789 Dương Văn Thành Hiệu B2504794 Nguyễn Ngọc Diệp B2504786 Nguyễn Tuấn Anh B2504784 
- **Lớp**: DI2595A11  
- **Giảng viên hướng dẫn**:ThS.Nguyễn Minh Trung  
- **Thời gian hoàn thành**: Tháng 02/2026  

## Mô tả bài thực hành

Bài thực hành Buổi 6 nhằm giúp sinh viên:  
- Làm quen với Microsoft Excel để tổ chức và truy vấn dữ liệu đơn giản.  
- Xây dựng cơ sở dữ liệu quan hệ bằng Microsoft Access (tạo bảng, thiết lập mối quan hệ, viết query).  
- Thực hiện các truy vấn lọc dữ liệu theo yêu cầu cụ thể.  
- Tìm kiếm, đánh giá nguồn thông tin về hệ quản trị cơ sở dữ liệu SQL và NoSQL bằng phương pháp **CRAAP Test** (Currency, Relevance, Authority, Accuracy, Purpose).  

Bài tập bao gồm 4 phần chính:  
1. Tạo bảng dữ liệu sinh viên, điểm số và môn học trên Excel.  
2. Thực hiện truy vấn/filter trên Excel để trả lời 4 yêu cầu.  
3. Chuyển dữ liệu sang Access, thiết lập bảng và query tương ứng.  
4. Nghiên cứu so sánh SQL vs NoSQL, áp dụng CRAAP test và viết báo cáo.  

## Cấu trúc thư mục dự án

## Nội dung chi tiết từng file

### 1. BUOI06_B2504786_NguyenNgocDiep.xlsx
- **Worksheet 1**: Danh sách sinh viên (MSSV, Họ tên, Lớp).  
- **Worksheet 3**: Bảng điểm (MSSV, Mã môn học, Điểm) và bảng môn học (Mã môn, Tên môn, Số tín chỉ).  
- Sử dụng Filter hoặc công cụ tìm kiếm để kiểm tra các yêu cầu ở Bài 2.

### 2. BUOI06_B2504786_NguyenNgocDiep.accdb
- **Bảng chính**:  
  - SinhVien (MSSV – Primary Key, HoTen, Lop)  
  - MonHoc (MaMH – Primary Key, TenMH, TinChi)  
  - KetQua (MSSV, MaMH, Diem)  
- **Relationship**: Đã thiết lập 1-nhiều giữa SinhVien ↔ KetQua và MonHoc ↔ KetQua.  
- **Query** (đã tạo sẵn):  
  - Q_a_DI_lop: Sinh viên lớp DI1296A1 và DI1296A2  
  - Q_b_CT178: Sinh viên học môn CT178  
  - Q_c_CP_CT178: Sinh viên lớp CP1296C1 học CT178  
  - Q_d_CP_CT178_C: Sinh viên lớp CP1296C1 học CT178 điểm C  

### 3. BUOI06_B2504786_NguyenNgocDiep.docx
- Báo cáo ≥ 2 trang, bao gồm:  
  - Câu hỏi nghiên cứu và từ khóa tìm kiếm.  
  - Bảng đánh giá CRAAP (4-6 nguồn, thang điểm 1-5 + nhận xét).  
  - Tóm tắt ưu/nhược điểm SQL vs NoSQL trong IT (scalability, consistency, big data, ứng dụng web/doanh nghiệp).  
  - Suy ngẫm về thiên kiến (bias) từ nhà cung cấp (ví dụ: MongoDB thiên về NoSQL, Oracle/IBM thiên về SQL).  
  - Danh sách tài liệu tham khảo (kiểu IEEE).  

## Kết quả truy vấn chính (tóm tắt)

- **a.** Sinh viên lớp DI1296A1 và DI1296A2: 1 sinh viên (B1204052 – Nguyễn Thanh Phong, DI1296A2).  
- **b.** Sinh viên học môn CT178: 4 sinh viên (A1200014, B1204052, B1209103, B1302016).  
- **c.** Sinh viên lớp CP1296C1 học CT178: 1 sinh viên (A1200014 – Võ Đông Triều).  
- **d.** Sinh viên lớp CP1296C1 học CT178 điểm C: 1 sinh viên (A1200014 – Võ Đông Triều, điểm C).  

## Công cụ và nguồn tham khảo

- **Phần mềm**: Microsoft Excel 2016+, Microsoft Access 2016+.  
- **Nguồn tìm kiếm**: Google, Google Scholar, IBM, MongoDB, Coursera, GeeksforGeeks (cập nhật 2024–2025).  
- **Phương pháp đánh giá**: CRAAP Test.  

## Hướng dẫn xem và kiểm tra

1. Mở file **.xlsx** bằng Excel → kiểm tra dữ liệu và filter.  
2. Mở file **.accdb** bằng Access → mở các Query → Run để xem kết quả.  
3. Mở file **.docx** bằng Word → đọc báo cáo đầy đủ.  

Repo này dùng để nộp bài thực hành Buổi 6. Mọi nội dung là kết quả tự thực hiện của sinh viên.

**Cập nhật lần cuối**: 27/02/2026  

Cảm ơn giảng viên đã hướng dẫn và đánh giá!  
