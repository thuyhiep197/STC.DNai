# Quản lý An sinh Xã hội — Sở Tài chính Đồng Nai

Form nhập liệu báo cáo thực hiện các chính sách An sinh Xã hội năm 2025.  
Căn cứ Công văn số 3993/BTC-NSNN ngày 01/4/2026 của Bộ Tài chính.

## Danh sách biểu mẫu

| File | Biểu | Mô tả |
|---|---|---|
| `bieu_01a_form.html` | 01a | Hỗ trợ chi phí học tập và cấp bù học phí (NĐ 238/2025) |
| `bieu_01b_form.html` | 01b | Phát triển giáo dục mầm non (NĐ 105/2020) |
| `bieu_01c_form.html` | 01c | Chế độ giáo viên mầm non lớp ghép (NĐ 105/2020) |
| `bieu_01d_form.html` | 01d | Hỗ trợ học sinh khuyết tật (TTLT 42/2013) |
| `bieu_01e_form.html` | 01e | Hỗ trợ học sinh và trường PTDT bán trú (NĐ 66/2025) |
| `bieu_01f_form.html` | 01f | Hỗ trợ chi phí học tập SV người DTTS (QĐ 66/2013) |
| `bieu_01g_form.html` | 01g | Chính sách nội trú HS/SV trường CĐ, TC (QĐ 53/2015) |
| `bieu_01h_form.html` | 01h | Hỗ trợ học bổng HS dân tộc nội trú (NĐ 84/2020) |
| `bieu_01i_form.html` | 01i | Hỗ trợ HS/SV DTTS rất ít người (NĐ 57/2017) |
| `bieu_01j_form.html` | 01j | Hỗ trợ tiền đóng học phí SV sư phạm (NĐ 116/2020 + NĐ 60/2025) |

## Hướng dẫn sử dụng

Mỗi file HTML là một form độc lập, chạy trực tiếp trên trình duyệt (không cần server).

1. Chọn **Kỳ báo cáo** (tháng/năm) — hệ thống tự hiển thị kỳ học tương ứng
2. Nhập số liệu vào các ô nhập liệu
3. Các ô tổng tự tính realtime
4. Nhấn **Lưu** — payload JSON xuất ra console (sẵn sàng kết nối API)
5. Nhấn **Xem trước** — xem tóm tắt số liệu trước khi lưu

## Kỳ báo cáo

| Tháng | Kỳ học |
|---|---|
| T1–T5 | Kỳ II năm học 2024–2025 |
| T6–T8 | Hè (ngoài kỳ học) |
| T9–T12 | Kỳ I năm học 2025–2026 |

## Ghi chú kỹ thuật

- Thuần HTML/CSS/JavaScript, không phụ thuộc framework
- Định dạng số: dấu chấm ngàn, dấu phẩy thập phân (chuẩn Việt Nam)
- Payload JSON chuẩn sẵn cho tích hợp backend/API
