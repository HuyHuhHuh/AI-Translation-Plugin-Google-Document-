# AI Translation Plugin (Google Document)

## Mục lục
- [I. Giới thiệu chung](#i-giới-thiệu-chung)
- [II. Cài đặt](#ii-cài-đặt)
- [III. Hướng dẫn sử dụng](#iii-hướng-dẫn-sử-dụng)

## I. Giới thiệu chung

Đây là 1 add-in trên Google Document sẽ tự động phát hiện đó là ngôn ngữ gì và cho phép bạn dịch sang ngôn ngữ mà mình muốn, hiện đang hỗ trợ 20 loại ngôn ngữ. Bạn có thể chọn dịch 1 đoạn ngắn hoặc toàn bộ văn bản. Add-in này sử dụng Gemini AI cho phần dịch thuật.

## II. Cài đặt

> Vì cần đăng ký tài khoản Google Developer (5$) nên không thể đưa add-in này lên Google Workspace để có thể tải về và sử dụng một cách thuận tiện. Hiện tại chỉ có cách thủ công:

### a. Test tính năng của Plugin

Có thể vào đường link sao để có thể test tính năng của add-in:

[Google Document](https://docs.google.com/document/d/1FAzCk661hdXfR2xU648oQv6LYFZT0vxzCVbVz9lVaks/edit?usp=sharing)

Phần hướng dẫn sẽ ở dư

### b. Tự cài đặt

Sau khi tạo một 1 Document trong Google Doc, bạn hãy bấm:

![Extension menu](https://drive.google.com/uc?export=view&id=1GorVVeZoQon5xTh41FC3sG6qTx7X0rLs)

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

Khi vào Doc, bạn sẽ thấy plugin hiện ở thanh công cụ:

![Plugin in toolbar](https://drive.google.com/uc?export=view&id=11EzUpT9N0wxjBQPDWUTjmpq_oRfWyh5U)

Bấm vào nó, bạn sẽ gặp thông báo sau:

![Authorization message](https://drive.google.com/uc?export=view&id=17PCGBBCu9nbw_Y8TP_t8YD3yVARszo75)

Bấm Ok, sau đó đăng nhập bằng tài khoản Google bạn đang dùng. Khi hoàn tất việc đăng nhập, bạn sẽ gặp cảnh báo:

![Warning message](https://drive.google.com/uc?export=view&id=1O-odiYe43ps4Do9Q9jraseARqKJUcj5d)

Hãy bấm vào Đi tới AI Translation Plugin, sau đó bấm **Cho Phép**, thế là hoàn tất. Từ giờ bạn có thể dùng mọi lúc bạn muốn.

### b. Cách sử dụng

![Usage instructions](https://drive.google.com/uc?export=view&id=1SwBtv8ZnsZ4fa9B4doRbvmI9l6GWI3qC)

- **1: Ngôn ngữ bạn muốn dịch sang**
- **2: Dịch một đoạn văn bản đã tô đen**
- **3: Dịch toàn bộ văn bản**
- **4: API key của Gemini, bạn có thể tạo API ở [Google AI Studio](https://aistudio.google.com/app/apikey) hoặc lấy của tôi (*AIzaSyB1bKdXjL76I5POlFr6ySyrTdIOY0gLLNs*)**
- **5: Lưu API key lại để sử dụng lâu dài**

### c. Ví dụ

#### Dịch 1 đoạn văn bản:

**Trước**

![Before translation example](https://drive.google.com/uc?export=view&id=1NBuLT2LBhbnbZ7VNx4RcvOVpOFC_dHaQ)

**Sau**

![After translation example](https://drive.google.com/uc?export=view&id=1h3OQZtMeJNwhGVX-cQV4oMp8XTjGp9tV)

#### Dịch toàn bộ văn bản:

**Trước**

![Before full translation](https://drive.google.com/uc?export=view&id=1WGbVobr3EqQBiwynUs9I6fqCfJGGQLlt)

**Sau**

![After full translation](https://drive.google.com/uc?export=view&id=1Pw-t2uB4QkAwENchHzFNEu_2uOFaHfXT)

