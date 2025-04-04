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

![Extension menu](https://i.imgur.com/nCj0IQN.jpg)

Sau đó cài đặt phần source code tôi gửi, ngoài ra nếu muốn nhấn thêm file có thể bấm vào đây:

![Add files](https://i.imgur.com/uJWlqjy.jpg)

Kế tiếp hãy bấm **triển khai**, bạn chọn **tủy chọn triển khai mới:**

![Deployment options](https://i.imgur.com/d5Qh1Tw.jpg)

Chọn loại hình là **Ứng dụng Web**:

![Web app selection](https://i.imgur.com/d5Qh1Tw.jpg)

Cuối cùng chỉ cần bấm **triển khai** là xong:

![Deploy button](https://i.imgur.com/5KYJ75j.jpg)

## III. Hướng dẫn sử dụng

### a. Cấp ủy quyền

Khi vào Doc, bạn sẽ thấy plugin hiện ở thanh công cụ:

![Plugin in toolbar](https://i.imgur.com/HzgTYI2.jpg)

Bấm vào nó, bạn sẽ gặp thông báo sau:

![Authorization message](https://i.imgur.com/GQ03rvS.jpg)

Bấm Ok, sau đó đăng nhập bằng tài khoản Google bạn đang dùng. Khi hoàn tất việc đăng nhập, bạn sẽ gặp cảnh báo:

![Warning message](https://i.imgur.com/n9jBQrS.jpg)

Hãy bấm vào Đi tới AI Translation Plugin, sau đó bấm **Cho Phép**, thế là hoàn tất. Từ giờ bạn có thể dùng mọi lúc bạn muốn.

### b. Cách sử dụng

![Usage instructions](https://i.imgur.com/5vZGbqr.jpg)

- **1: Ngôn ngữ bạn muốn dịch sang**
- **2: Dịch một đoạn văn bản đã tô đen**
- **3: Dịch toàn bộ văn bản**
- **4: API key của Gemini, bạn có thể tạo API ở [Google AI Studio](https://aistudio.google.com/app/apikey) hoặc lấy của tôi (*AIzaSyB1bKdXjL76I5POlFr6ySyrTdIOY0gLLNs*)**
- **5: Lưu API key lại để sử dụng lâu dài**

### c. Ví dụ

#### Dịch 1 đoạn văn bản:

**Trước**

![Before translation example](https://i.imgur.com/2edhDwY.jpg)

**Sau**

![After translation example](https://i.imgur.com/M7U7pQA.jpg)

#### Dịch toàn bộ văn bản:

**Trước**

![Before full translation](https://i.imgur.com/lQ4wM7J.jpg)

**Sau**

![After full translation](https://i.imgur.com/9A8LuSa.jpg)

![Full document translation](https://i.imgur.com/h3kOQGy.jpg)
