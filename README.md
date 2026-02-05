##🖋️ Poem Generator (Google Colab Version)
Dự án này sử dụng mô hình AI để tự động tạo thơ, được thiết kế để chạy trực tiếp trên Google Colab mà không cần cài đặt phức tạp trên máy tính cá nhân.

##🚀 Cách chạy dự án
Bạn có thể chạy toàn bộ chương trình chỉ với một cú click chuột:

Mở Notebook: Click vào biểu tượng dưới đây để mở file trong môi trường Colab:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1CjIZpHNCT_b6lItdwtIgQbrq9sv807nH#scrollTo=_7gwXkaPQOhZ)

Thiết lập GPU (Nếu cần):

Vào menu Runtime (Thời gian chạy) -> Change runtime type (Thay đổi loại thời gian chạy).

Chọn Hardware accelerator là T4 GPU để mô hình chạy nhanh hơn.

Chạy tất cả: Nhấn Ctrl + F9 hoặc vào Runtime -> Run all.

##🛠️ Quy trình hoạt động (Workflow)
Dự án bao gồm các bước chính trong file Notebook:

Cài đặt thư viện: Tự động cài đặt các thư viện cần thiết (transformers, torch, v.v.).

Tải mô hình: Load pre-trained model (ví dụ: GPT-2 hoặc các mô hình ngôn ngữ tiếng Việt).

Xử lý dữ liệu: Tokenize đầu vào từ người dùng.

Tạo thơ: Thuật toán giải mã (Decoding) để sinh ra các câu thơ có vần điệu.

##📝 Lưu ý
File notebook này yêu cầu kết nối internet để tải mô hình từ Hugging Face.

Nếu bạn sử dụng dữ liệu riêng, hãy đảm bảo đã upload file dữ liệu lên Google Drive và mount Drive trong notebook.

##👤 Tác giả
Tên: [Phạm Thanh Tùng]
