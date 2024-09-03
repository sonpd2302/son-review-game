---
title: Chỉ số product + mkt
draft: false
tags:
---
---

# App Quality

## Game ngon

### Định nghĩa

- Chạy ngon, nuột trên nhiều thiết bị, kể cả low end
- Đúng luồng, đúng kịch bản
- Hay không thì còn do game nào nữa =)

### Các chỉ số Product

- Retention : Tỉ lệ giữ chân người dùng qua từng ngày.
- Playtime : Hiểu đơn giản là thời gian trung bình user chơi hằng ngày.
- DAU (Daily Active User) : số người dùng hằng ngày.
- IAA : In-App Advertising
- IAP : In-App Purchases

## Đánh giá người dùng

- Bug --> fix
- Chê nhiều ads --> xem lại kịch bản ads
- Bình luận có tính đóng góp --> tiếp nhận

## Crash Rate , ANR (Application Not Responding) --> DEV

- Test kĩ game trước khi lên store
- Lên firebase check log

**Cần lưu ý** :

|Tên|Benmark|
|---|---|
|Crash Rate|<1%|
|ANR|<0.5%|

## Hiệu quả của các dạng quảng cáo

### Các thông số cơ bản MKT

- CPI (Cost per Install) : Chi phí cho mỗi lượt cài đặt
- CVR (conversion rate) : tỉ lệ chuyển đổi --> CREATIVE + ART + MKT
- eCPM (effective cost per mille ) : Kiếm được bao nhiêu tiền trên 1000 lượt quảng cáo
- ImPDAU (Impressions per Daily Active User ) : là lượt hiển thị quảng cáo trên mỗi user hoạt động hàng ngày.
- IAA : In-App Advertising
- IAP : In-App Purchases
- Các chỉ số show ads ( Impresstion, Click , Show time)
- -> Các chỉ số này đều cần được theo dõi.

### Các định dạng ads công ty đang dùng

|Tên|Giải thích|Mức độ ảnh hưởng|
|---|---|---|
|Inter|- Là loại ads full màn hình xuất hiện giữa game<br>- Phải được đặt ở giữa màn hình khác nhau|- UX : cao<br>- eCPM : trung bình|
|Reward|- Là loại ads full màn hình mà người chơi chủ động ấn vào<br>- Đợi 5-30s tuỳ bên MO setup, xem xong phải có thưởng giá trị cao.|- UX : thấp<br>- eCPM cao|
|Banner|- Là một loại ads hiển thị 1 khoảng nhỏ ở bottom hoặc top.|- UX : thấp<br>- eCPM : thấp|
|Collasible Banner|- Là một loại **Banner** nhưng sẽ show to hơn loại thường. Khi sổ ra sẽ có nút bấm để thu gọn lại như Banner thường.<br>- Tuy nhiên fill rate khá bất ổn|- UX : cao<br>- eCPM : dao động, chưa ổn định|
|Native/Pubscale Banner|- Là một dạng ads type cho phép mình setup để hiển thị trực tiếp ở trong gameplay.<br>- Phù hợp với những tựa game có thời lượng chơi lớn, ít chuyển màn.|- UX : thấp<br>- eCPM : phụ thuộc vào thời lượng show ads|
|Audio Ads|- Thay vì hiển ads full màn hình, sẽ hiển thị icon ở vị trí mà mình setup -> phát âm thanh thay cho âm thanh game. Sau khi hết thì sẽ trả lại bình thường.|- UX : trung bình<br>- eCPM : thấp|
||||