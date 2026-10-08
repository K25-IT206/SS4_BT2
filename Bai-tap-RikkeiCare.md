# Viết User Story, Acceptance Criteria và theo dõi trên Trello — RikkeiCare

## Bước 1. Viết User Story cho R5

**R5:** Là một quản lý phòng khám, tôi muốn tự cập nhật giá các gói khám trên RikkeiCare, để giá được điều chỉnh kịp thời mà không phải gửi email nhờ admin cập nhật hộ.

Chọn **quản lý phòng khám** làm vai trò vì đây là người đề xuất và trực tiếp cần thực hiện việc cập nhật giá. Admin RikkeiCare hiện đang thao tác thay, nhưng không phải người dùng được yêu cầu trao quyền tự cập nhật; lấy admin làm vai trò sẽ mô tả giải pháp hiện tại thay vì nhu cầu của phòng khám.

## Bước 2. Viết phần Then cho 2 AC của R5

- **AC 1 (thành công):** Given quản lý phòng khám đã đăng nhập, **When** nhập giá mới cho một gói khám rồi nhấn “Lưu”, **Then** hệ thống lưu giá mới cho đúng gói khám và hiển thị giá đã cập nhật trên thông tin gói khám.
- **AC 2 (thất bại):** Given quản lý để trống ô giá, **When** nhấn “Lưu”, **Then** hệ thống không lưu thay đổi, hiển thị thông báo giá là bắt buộc và giữ quản lý ở màn hình chỉnh sửa để nhập lại.

## Bước 3. Thẻ R5 đã sẵn sàng chưa?

**Chưa.** Thẻ đã có User Story đủ ba vế và tiêu chí nghiệm thu, nhưng thông tin hiện có chưa cho biết thẻ đã được **ước lượng** hay chưa, cũng chưa xác nhận phạm vi đủ nhỏ để hoàn thành trong một Sprint. Theo Definition of Ready của nhóm, cần ước lượng và kiểm tra kích thước/phạm vi trước khi chuyển sang “Ready for Sprint”. Nếu refinement xác nhận story quá lớn, cần chia nhỏ story trước.

## Bước 4. Hoàn thiện thẻ R5 trên Trello

- **Nhãn:** Xanh dương — Feature.
- **Người phụ trách:** Gán cho thành viên nhóm thực hiện phần cập nhật giá (**điền tên thành viên được nhóm phân công**); không có danh sách thành viên nên không tự giả định tên.
- **Checklist:**
  1. Xây dựng chức năng nhập và lưu giá mới cho gói khám.
  2. Kiểm tra giá đã lưu được hiển thị trên thông tin gói khám.
  3. Kiểm thử trường hợp bỏ trống giá và thông báo xác thực.
- **Hạn hoàn thành:** Ngày kết thúc Sprint (ngày thứ 10; nhập ngày lịch tương ứng khi tạo hạn trên Trello).
- **Vị trí khi ưu tiên cao nhất:** Đặt thẻ ở đầu cột Sprint Backlog, trên các thẻ ưu tiên thấp hơn.

## Bước 5. Đọc Burndown Chart

### a) Ngày 6 nhóm nhanh hay chậm?

Đường lý tưởng giảm 3 point mỗi ngày, nên ở ngày 6 số point lý tưởng còn lại là **30 − (6 × 3) = 12 point**. Thực tế còn **20 point**, tức nhiều hơn đường lý tưởng **8 point**. Nhóm đang **chậm hơn kế hoạch 8 point** tại thời điểm đó.

### b) Có trừ point cho thẻ R5 khi mới “xong 80%” không?

**Không.** Burndown ghi nhận point khi công việc hoàn thành theo quy ước của nhóm (thường là đáp ứng Definition of Done), không ghi nhận phần trăm hoàn thành. R5 còn 20% thì chưa hoàn tất; chưa trừ 3 point khỏi số point còn lại.
