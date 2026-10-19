# [MINI PROJECT] XÂY DỰNG PRODUCT BACKLOG VÀ KẾ HOẠCH SPRINT CHO DỰ ÁN MOTOGO

**Họ và tên:** [Họ tên sinh viên]

**Lớp:** [Lớp học]

**Link bảng Trello công khai:** [Chèn link Trello tại đây, ví dụ: https://trello.com/b/example_link_motogo_hoten_lop]

---

## Hạng mục 1: Phân rã Epic – Feature

Dự án MotoGo được phân rã thành các Epic và Feature như sau. Tên các Epic tập trung vào giá trị nghiệp vụ mang lại, tránh đặt tên theo module kỹ thuật.

### Cấu trúc trên Trello (mô tả)

Bảng Trello có tên `MotoGo – [Họ tên] – [Lớp]` với chế độ công khai. Các list bao gồm:

*   **Epic:** Chứa các thẻ Epic.
*   **Feature:** Chứa các thẻ Feature.
*   **Product Backlog:** Chứa toàn bộ User Story đã được xếp thứ tự ưu tiên.
*   **Sprint 1 Backlog:** Chứa các User Story đã chọn cho Sprint 1.

Hệ thống nhãn sử dụng:

*   **Cấp độ:** `Epic`, `Feature`, `User Story`
*   **Ưu tiên:** `Must`, `Should`, `Could`, `Won't`

Quan hệ phân cấp được thể hiện qua mô tả thẻ (ví dụ: thẻ User Story ghi mã Feature cha trong phần mô tả). Quan hệ truy vết về FR/BR được ghi trong mô tả thẻ User Story.

![Trello Screenshot Placeholder](https://via.placeholder.com/600x400?text=Ch%E1%BB%A5p+m%C3%A0n+h%C3%ACnh+b%E1%BA%A3ng+Trello)

### Danh sách Epic và Feature

*   **Epic 1: Tăng cường trải nghiệm đặt xe liền mạch**
    *   **Giá trị nghiệp vụ:** Giúp khách hàng dễ dàng tìm kiếm, chọn và đặt xe mà không gặp trở ngại, tăng tỷ lệ chuyển đổi khách hàng.
    *   **Feature 1.1: Tìm kiếm và đặt giữ chỗ xe**
        *   **Bao phủ mã FR:** FR-01 (Tìm kiếm xe), FR-02 (Lọc kết quả tìm kiếm), FR-03 (Xem chi tiết xe), FR-10 (Giữ chỗ xe tạm thời)
    *   **Feature 1.2: Hoàn tất quy trình thanh toán**
        *   **Bao phủ mã FR:** FR-04 (Thanh toán cọc online), FR-05 (Xác nhận thanh toán)

*   **Epic 2: Nâng cao hiệu quả quản lý vận hành cửa hàng**
    *   **Giá trị nghiệp vụ:** Hỗ trợ chủ cửa hàng và nhân viên quản lý đơn hàng, kho xe một cách hiệu quả và minh bạch, giảm thiểu sai sót và tối ưu hóa nguồn lực.
    *   **Feature 2.1: Quản lý đơn hàng thuê xe**
        *   **Bao phủ mã FR:** FR-06 (Xem danh sách đơn hàng), FR-07 (Cập nhật trạng thái đơn hàng)
    *   **Feature 2.2: Quản lý thông tin và kho xe**
        *   **Bao phủ mã FR:** FR-08 (Xem lịch sử thuê của xe), FR-09 (Quản lý thông tin xe và dòng xe)

*   **Epic 3: Đảm bảo quy trình giao nhận xe minh bạch**
    *   **Giá trị nghiệp vụ:** Cung cấp bằng chứng rõ ràng về tình trạng xe trước và sau khi thuê, giảm thiểu tranh chấp và xây dựng niềm tin giữa khách hàng và cửa hàng.
    *   **Feature 3.1: Biên bản giao xe điện tử**
        *   **Bao phủ mã FR:** FR-11 (Tạo biên bản giao xe có ảnh), FR-12 (Khách hàng xác nhận biên bản giao xe)
    *   **Feature 3.2: Biên bản nhận xe điện tử**
        *   **Bao phủ mã FR:** FR-13 (Tạo biên bản nhận xe có ảnh), FR-14 (Ghi nhận hư hại và tính phí phát sinh)

## Hạng mục 2: Danh sách User Story

Đây là danh sách các User Story đã được xây dựng, bao phủ các nhóm nghiệp vụ cốt lõi:

| Mã Story | User Story | Truy vết | Mức ưu tiên | Story Point | Acceptance Criteria |
| :------- | :--------- | :------- | :---------- | :---------- | :------------------ |
| US-01 | Là khách thuê, tôi muốn tìm xe còn trống theo thời gian và địa điểm mong muốn để chọn được xe phù hợp. | FR-01, FR-02 | Must | 5 | - |
| US-02 | Là khách thuê, tôi muốn giữ chỗ chiếc xe vừa chọn để không bị người khác đặt mất trong lúc tôi thanh toán. | FR-10, BR-05 | Must | 3 | AC-01, AC-02, AC-03 |
| US-03 | Là khách thuê, tôi muốn thanh toán tiền cọc online để hoàn tất việc đặt xe mà không cần đến cửa hàng. | FR-04, FR-05 | Should | 8 | - |
| US-04 | Là chủ cửa hàng, tôi muốn xem danh sách đơn đặt xe mới để kịp thời xác nhận và chuẩn bị xe. | FR-06 | Must | 2 | - |
| US-05 | Là chủ cửa hàng, tôi muốn cập nhật trạng thái đơn hàng để quản lý tiến độ và thông báo cho khách. | FR-07 | Should | 3 | - |
| US-06 | Là chủ cửa hàng, tôi muốn xem lịch sử thuê của từng chiếc xe để biết tình trạng sử dụng và bảo dưỡng. | FR-08 | Could | 5 | - |
| US-07 | Là nhân viên cửa hàng, tôi muốn tạo biên bản giao xe có hình ảnh để ghi nhận tình trạng xe trước khi giao cho khách. | FR-11, FR-12 | Must | 8 | AC-04, AC-05, AC-06 |
| US-08 | Là khách thuê, tôi muốn xem biên bản giao xe điện tử để xác nhận tình trạng xe và thông tin thuê. | FR-11 | Could | 2 | - |
| US-09 | Là nhân viên cửa hàng, tôi muốn tạo biên bản nhận xe có hình ảnh để ghi nhận tình trạng xe sau khi khách trả. | FR-13, FR-14 | Must | 8 | AC-07, AC-08, AC-09 |
| US-10 | Là chủ cửa hàng, tôi muốn quản lý thông tin các dòng xe đang có để hiển thị cho khách thuê. | FR-09 | Should | 5 | - |
| US-11 | Là khách thuê, tôi muốn thanh toán bằng điểm thưởng tích lũy để tiết kiệm chi phí thuê xe. | FR-20 | Won't | - | - |

*Lưu ý: Các User Story US-04, US-05, US-06, US-07, US-09, US-10 được viết cho các nhóm người dùng không phải khách thuê (chủ cửa hàng, nhân viên cửa hàng).* 

## Hạng mục 3: Bảng tự đánh giá INVEST

Chọn 3 User Story bất kỳ để đánh giá theo tiêu chí INVEST. Tối thiểu 1 story được viết lại.

### Bảng đánh giá INVEST

| Story | Tiêu chí | Đạt/Chưa đạt | Lý do | Gợi ý sửa đổi (nếu có) |
| :---- | :------- | :----------- | :---- | :--------------------- |
| US-02 | **I**ndependent | Đạt | Không phụ thuộc quá chặt chẽ vào các story khác để bắt đầu hoặc hoàn thành. | - |
| | **N**egotiable | Đạt | Có thể thương lượng về chi tiết triển khai (ví dụ: thời gian giữ chỗ). | - |
| | **V**aluable | Đạt | Mang lại giá trị rõ ràng cho khách hàng (tránh bị mất xe) và cửa hàng (tăng khả năng đặt thành công). | - |
| | **E**stimable | Đạt | Có thể ước lượng được độ lớn công việc. | - |
| | **S**mall | Đạt | Đủ nhỏ để hoàn thành trong một Sprint. | - |
| | **T**estable | Đạt | Có thể kiểm thử được bằng cách đặt xe và chờ thời gian giữ chỗ. | - |
| US-06 | **I**ndependent | Đạt | Có thể triển khai độc lập. | - |
| | **N**egotiable | Đạt | Có thể thương lượng về cách hiển thị lịch sử hoặc các thông tin chi tiết. | - |
| | **V**aluable | Đạt | Cung cấp thông tin hữu ích cho chủ cửa hàng để quản lý và bảo dưỡng xe. | - |
| | **E**stimable | Đạt | Có thể ước lượng được. | - |
| | **S**mall | Đạt | Đủ nhỏ để hoàn thành trong một Sprint. | - |
| | **T**estable | Đạt | Có thể kiểm thử bằng cách xem lịch sử sau khi có dữ liệu thuê. | - |
| US-12 (Bản trước) | **I**ndependent | Chưa đạt | Story này quá rộng và có thể phụ thuộc vào việc xây dựng hệ thống khuyến mãi phức tạp trước. | Tách thành 