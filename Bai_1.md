# BÀI 1: TÌM KIẾM TÀI LIỆU HỌC TẬP CHÍNH THỐNG BẰNG GOOGLE

#### ***Sinh viên: Võ Xuân Thịnh – Lớp CNTT2-K26***

## 1. Mục tiêu

Sử dụng phối hợp các toán tử tìm kiếm nâng cao để tìm kiếm tài liệu chính thống, tránh mã độc.

## 2. Bối cảnh (Roleplay)

Là sinh viên cần tìm giáo trình "Nhập môn Công nghệ Thông tin" bản PDF của Học viện để ôn thi, nhưng kết quả Google toàn trả về trang bắt nạp thẻ hoặc quảng cáo bài viết không liên quan.

## 3. Yêu cầu nghiệp vụ

### 3.1. Query dùng `filetype:`, `site:` và dấu ngoặc kép

```
"Nhập môn Công nghệ Thông tin" filetype:pdf site:ptit.edu.vn -site:scribd.com -site:123docz.net -site:doc.edu.vn
```


| Toán tử          | Tác dụng                                                               |
| ------------------ | ------------------------------------------------------------------------ |
| `" "`              | Chỉ lấy kết quả chứa đúng cụm từ tên giáo trình              |
| `filetype:pdf`     | Chỉ trả về file PDF, bỏ trang bài viết, blog                       |
| `site:ptit.edu.vn` | Chỉ tìm trên máy chủ của Học viện, nên là nguồn chính thống |

### 3.2. Toán tử trừ (`-`) loại ít nhất 2 trang web "rác"


| Toán tử           | Lý do loại                                      |
| ------------------- | ------------------------------------------------- |
| `-site:scribd.com`  | Đòi nạp thẻ / đăng nhập mới cho tải      |
| `-site:123docz.net` | Quảng cáo, tài liệu không rõ nguồn         |
| `-site:doc.edu.vn`  | Tổng hợp tài liệu, bắt tải kèm quảng cáo |

## 4. Yêu cầu đầu ra

### 4.1. Vì sao `filetype:` tiết kiệm thời gian hơn gõ "tải sách…"?

* Gõ "tải sách…" khiến Google trả về đủ loại trang web, blog, quảng cáo; phải mở từng trang để kiểm tra.
* `filetype:pdf` lọc sẵn đúng định dạng cần tìm, bấm vào là ra tài liệu ngay.
* Kết hợp `site:` của trường nên file an toàn, ít nguy cơ dính mã độc hoặc bị bắt nạp thẻ.

### 4.2. Ảnh chụp 3 kết quả đầu tiên sau khi áp dụng "Combo toán tử"

![3 kết quả đầu tiên sau khi áp dụng combo toán tử](ket-qua-google.png)
