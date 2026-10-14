# Vehicle Image Annotation Practice with CVAT

## 1. Giới thiệu

Dự án thực hành gán nhãn ảnh phương tiện giao thông bằng CVAT nhằm làm quen với quy trình image annotation, tạo bounding box, quản lý nhãn và xuất dữ liệu.

## 2. Thông tin dự án

- **Dataset:** Top-View Vehicle Detection Image Dataset
- **Số lượng ảnh đã gán nhãn:** Hơn 30 ảnh
- **Công cụ:** CVAT
- **Phương pháp:** Bounding box annotation
- **Định dạng nhãn:** YOLO

## 3. Quy trình thực hiện

1. Tạo task và tải ảnh lên CVAT.
2. Thiết lập các lớp đối tượng theo dataset.
3. Vẽ bounding box và gán class label cho từng đối tượng.
4. Kiểm tra, điều chỉnh các nhãn có lỗi dễ nhận thấy.
5. Export dữ liệu và kiểm tra cấu trúc file nhãn.

## 4. Kiểm tra chất lượng nhãn

Các tiêu chí tự kiểm tra gồm:
- Đối tượng được gán nhãn đúng lớp.
- Bounding box bao phủ đối tượng phù hợp.
- Không bỏ sót đối tượng thuộc phạm vi gán nhãn.
- Không tạo nhãn trùng lặp cho cùng một đối tượng.
- Định dạng file nhãn phù hợp với cấu trúc YOLO.

## 5. Kết quả

- Hoàn thành gán nhãn hơn 30 ảnh bằng CVAT.
- Thực hành chỉnh sửa bounding box và class label.
- Xuất dữ liệu nhãn theo định dạng YOLO.

## 6. Minh chứng

Xem thư mục `screenshots/` để tham khảo giao diện CVAT và một số ảnh đã gán nhãn.
