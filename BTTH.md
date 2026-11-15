# [BTTH] Bài tập thực hành tổng hợp
## Yêu cầu :
> Thiết lập chuỗi prompt liên kết (Prompt Chaining) chạy tuần tự khép kín để giải quyết bài toán lớn.
### Giải quyết bài toán
**Chuỗi Prompt Thực thi**
```text
[Bước 1] Đọc biên bản và xuất Raw JSON (không markdown code block):
{
  "vendor_name": "String",
  "discount_rate": "Float",
  "payment_term_days": "Integer",
  "supports_rma_direct": "Boolean",
  "core_product_lines": ["Array"],
  "risk_assessment": "String"
}
```
[Bước 2] Lấy JSON từ Bước 1 chuyển thành bảng Markdown gồm 3 cột: | Nhà cung cấp | Chiết khấu & Công nợ | Đánh giá rủi ro |.
#### 3. Kết quả Test Output
| Nhà cung cấp | Chiết khấu & Công nợ | Đánh giá rủi ro |
| :--- | :--- | :--- |
| Viễn Thông Tân Phát |  |  |
