# AI-Powered Calculation Plugin (Google Sheets)

## Mục lục
- [I. Giới thiệu chung](#i-giới-thiệu-chung)
- [II. Cài đặt](#ii-cài-đặt)
- [III. Hướng dẫn sử dụng](#iii-hướng-dẫn-sử-dụng)

## I. Giới thiệu chung

Đây là 1 add-in trên Google Sheets sẽ cho phép người dùng xử lý dữ liệu bảng tính bằng mô hình AI (Gemini) trực tiếp trong giao diện Google Trang tính. (Không dùng được hàm Gemini_SUMMARIZE)

## II. Cài đặt

> Vì cần đăng ký tài khoản Google Developer (5$) nên không thể đưa add-in này lên Google Workspace để có thể tải về và sử dụng một cách thuận tiện. Hiện tại chỉ có cách thủ công:

### a. Test tính năng của Plugin

Có thể vào đường link sao để có thể test tính năng của add-in:

[Google Sheets](https://docs.google.com/spreadsheets/d/1OQBjOCZEZ-EAeHSiHLpXlE5puu37XR22lyFTejeVOes/edit?usp=sharing)

Phần hướng dẫn sẽ ở dưới.

### b. Tự cài đặt

Sau khi tạo một 1 Sheet trong Google Doc, bạn hãy bấm:

![Extension menu](https://drive.google.com/uc?export=view&id=1KScNITy-6KlMQ2m3XfotIU1L2TvFIQFy)

Sau đó cài đặt phần source code tôi gửi, ngoài ra nếu muốn nhấn thêm file có thể bấm vào đây:

![Add files](https://drive.google.com/uc?export=view&id=1vE0W6s8rT6BKg6cNI_z-1veSMGsEA_oh)

Kế tiếp hãy bấm **triển khai**, bạn chọn **tủy chọn triển khai mới:**

![Deployment options](https://drive.google.com/uc?export=view&id=1ilmTBcdCEQ8oaFDF3FQz-nwbAE0AiKBE)

Chọn loại hình là **Ứng dụng Web**:

![Web app selection](https://drive.google.com/uc?export=view&id=1YxVU9oUQCND0sQy0_PWiJySQ9477lqwN)

Cuối cùng chỉ cần bấm **triển khai** là xong:

![Deploy button](https://drive.google.com/uc?export=view&id=1pTe1iZ5YhVuVapN4Eaw9mWIPVxhVju3F)

## III. Hướng dẫn sử dụng

### a. Cấp ủy quyền

Khi vào Sheet, bạn sẽ thấy plugin hiện ở thanh công cụ:

![Plugin in toolbar](https://drive.google.com/uc?export=view&id=1Pj40bZq_ifR0V9IMexF-vVumRDIatDpE)

Bấm vào nó, bạn sẽ gặp thông báo sau:

![Authorization message](https://drive.google.com/uc?export=view&id=17PCGBBCu9nbw_Y8TP_t8YD3yVARszo75)

Bấm Ok, sau đó đăng nhập bằng tài khoản Google bạn đang dùng. Khi hoàn tất việc đăng nhập, bạn sẽ gặp cảnh báo:

![Warning message](https://drive.google.com/uc?export=view&id=1O-odiYe43ps4Do9Q9jraseARqKJUcj5d)

Hãy bấm vào Đi tới AI Translation Plugin, sau đó bấm **Cho Phép**, thế là hoàn tất. Từ giờ bạn có thể dùng mọi lúc bạn muốn.

### b. Cách sử dụng

![Usage instructions](https://drive.google.com/uc?export=view&id=1eFSS6hRXUMDfMYlH8qYjERcrFn1Sroh0)

- **1: Hàng Tiêu Đề (Header Row): Trường này cho phép bạn chỉ định hàng nào chứa tiêu đề cột của bảng tính. Giá trị mặc định là 1, có nghĩa là hàng đầu tiên của bảng tính chứa các tiêu đề.**
- **2:Lựa Chọn Hàng Bắt Đầu (Start Row Selection): Tùy chọn này cho phép bạn chọn cách xác định hàng bắt đầu xử lý. Đang chọn "Auto" (Tự động), nghĩa là hệ thống sẽ tự động bắt đầu xử lý từ hàng ngay sau hàng tiêu đề**
- **3: Số Hàng Cần Xử Lý (Number of Rows to Process): Khi sử dụng chế độ Auto, trường này xác định số hàng sẽ được xử lý. Hiện tại đang đặt là 3, vậy hệ thống sẽ xử lý 3 hàng bắt đầu từ hàng sau hàng tiêu đề**
- **4: Xác định cột nào sẽ chứa kết quả do AI tạo ra.**
- **5: Mẫu Lệnh (Prompt Template): Đây là nơi bạn định nghĩa điều bạn muốn AI thực hiện với dữ liệu của mình. Bạn có thể sử dụng cú pháp {{A}} để tham chiếu đến giá trị từ các cột cụ thể**
- **6: Temperature: Điều chỉnh mức độ sáng tạo/ngẫu nhiên trong câu trả lời của AI. Thanh trượt hiện tại đặt ở mức 0.3, cung cấp câu trả lời tương đối nhất quán nhưng vẫn có một chút biến đổi. Giá trị cao hơn (gần 1.0) tạo ra câu trả lời sáng tạo hơn nhưng có thể ít nhất quán hơn**
- **7: Mô Hình (Model): Cho phép bạn chọn mô hình AI để sử dụng. Hiện tại đang cài đặt có thể cài đặt "Gemini 1.5 Pro" và "Gemini 1.5 Flash", đây là các mô hình ngôn ngữ tiên tiến của Google dành cho các tác vụ phức tạp**
- **8: Xử Lý Dữ Liệu (Process Data): Sau khi đã cấu hình tất cả các cài đặt, nhấn nút này sẽ bắt đầu xử lý dữ liệu bảng tính của bạn bằng AI Gemini theo thông số bạn đã chỉ định**

Ngoài ra, ở tính năng số 3 nếu bạn không chọn Auto có thể chọn Fixed range:

![Usage instructions 2](https://drive.google.com/uc?export=view&id=1K5IRXs-LvP8a7fa3ksVZtBqau6jaya1G)

- **1: Lựa Chọn Hàng Bắt Đầu (Start Row Selection): Khác với hình trước, giờ đây tùy chọn này đã được chuyển sang "Fixed range" (Phạm vi cố định). Điều này có nghĩa là bạn sẽ tự chỉ định chính xác hàng bắt đầu và kết thúc mà không để hệ thống tự động xác định.**
- **2: Lựa Chọn Hàng Bắt Đầu (Start Row Selection): Hàng Bắt Đầu (Start Row): Đây là nơi bạn xác định chính xác hàng nào sẽ là hàng đầu tiên để xử lý.**
- **3: Hàng Kết Thúc (End Row): Đây là nơi bạn xác định hàng cuối cùng sẽ được xử lý.**


### c. Ví dụ

#### Dùng Auto:

**Trước**

![Before auto](https://drive.google.com/uc?export=view&id=1yAUuo8bS2aeWjwL9ApzuZlB9gFIzm11K)

**Sau**

![After auto](https://drive.google.com/uc?export=view&id=1iBvr23AZNJU16w3uT1X4xZE2j84P6gnp)

#### Dùng Fixed range:

**Trước**

![Before fixed range](https://drive.google.com/uc?export=view&id=1TPrssZwYOMWd8co6HZBdb4ba__oRJAdc)

**Sau**

![After fixed range](https://drive.google.com/uc?export=view&id=1_knHpPlXwbe7MECh4QlYV0GIKDas2z19)


