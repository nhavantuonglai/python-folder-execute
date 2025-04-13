# File and folder transfer (FFT)

(Original Vietnamese below)

_File and folder transfer (FFT) is a Python tool designed to automate the process of copying or moving files and folders between two directories. It compares file and folder names to avoid duplicates and omissions, offering options to copy or move data efficiently. Ideal for organizing and updating file systems with a customizable workflow._

## Installation Guide

To install, clone this repository and run the Python script directly:

```
npm install folder-execute
```

No additional dependencies are required beyond the Python standard library.

## Purpose

– Compare files and folders between an old directory and a new directory.

– Identify unique files and subfolders in the old directory that are not present in the new directory.

– Copy or move unique files and subfolders to the new directory.

– Provide detailed statistics on files, subfolders, and sizes before and after the operation.

## Workflow

1. Specify old directory: Enter the path to the source folder or leave blank to use the current directory (`.`). Input `0` to exit. Defaults to the current directory for convenience.

2. Specify new directory: Enter the path to the target folder or leave blank to use the current directory (`.`). Input `0` to go back to the previous step. Defaults to the current directory.

3. Review and choose display option: The tool displays initial statistics (total files, subfolders, and size in KB for both directories, plus actionable items). Then:

`1`: Display the list of files and subfolders that can be transferred.

`2`: Skip displaying the list and proceed.

`0`: Go back to the previous step.

4. Select action: Choose the operation to perform:

`1`: Copy data from the old directory to the new directory.

`2`: Move data from the old directory to the new directory.

`0`: Go back to the previous step.

After processing, the tool shows final statistics (updated counts and sizes for both directories, successful and failed operations). Users can then choose to restart (`0`), visit the website (`1`), or Instagram (`2`).

Backtracking: At any step, input `0` to return to the previous step.

## Contact & Support

– Email: info@nhavantuonglai.com.

– Website: [nhavantuonglai.com](https://nhavantuonglai.com).

If you have any questions or suggestions, feel free to reach out for the fastest support.

Don’t forget to star this repository if you find it useful.

# Công cụ chuyển tệp và thư mục (FFT)

_Công cụ chuyển tệp và thư mục (FFT) là một tiện ích Python tự động hóa quá trình sao chép hoặc di chuyển tệp và thư mục giữa hai thư mục. Nó so sánh tên tệp và thư mục để tránh trùng lặp và bỏ sót, cung cấp tùy chọn sao chép hoặc di chuyển dữ liệu một cách hiệu quả. Phù hợp để sắp xếp và cập nhật hệ thống tệp với quy trình tùy chỉnh._

## Hướng dẫn cài đặt

Để cài đặt, sao chép repository này và chạy trực tiếp script Python:

```
npm install folder-execute
```

Không yêu cầu thêm thư viện phụ thuộc ngoài thư viện chuẩn của Python.

## Công dụng

– So sánh tệp và thư mục giữa thư mục cũ và thư mục mới.

– Xác định các tệp và thư mục con duy nhất trong thư mục cũ không có trong thư mục mới.

– Sao chép hoặc di chuyển các tệp và thư mục con duy nhất sang thư mục mới.

– Cung cấp thống kê chi tiết về số lượng tệp, thư mục con và kích thước trước và sau khi thao tác.

## Flow thao tác

1. Chỉ định thư mục cũ: Nhập đường dẫn đến thư mục nguồn hoặc để trống để dùng thư mục hiện tại (`.`). Nhập `0` để thoát. Mặc định là thư mục hiện tại để tiện lợi.

2. Chỉ định thư mục mới: Nhập đường dẫn đến thư mục đích hoặc để trống để dùng thư mục hiện tại (`.`). Nhập `0` để quay lại bước trước. Mặc định là thư mục hiện tại.

3. Xem xét và chọn hiển thị: Công cụ hiển thị thống kê ban đầu (tổng số tệp, thư mục con và kích thước tính bằng KB cho cả hai thư mục, cùng với các mục có thể thao tác). Sau đó:

`1`: Hiển thị danh sách tệp và thư mục con có thể chuyển.

`2`: Bỏ qua hiển thị danh sách và tiếp tục.

`0`: Quay lại bước trước.

4. Chọn hành vi: Chọn thao tác cần thực hiện:

`1`: Sao chép dữ liệu từ thư mục cũ sang thư mục mới.

`2`: Di chuyển dữ liệu từ thư mục cũ sang thư mục mới.

`0`: Quay lại bước trước.

Sau khi xử lý, công cụ hiển thị thống kê cuối (số lượng và kích thước cập nhật cho cả hai thư mục, thao tác thành công và thất bại). Người dùng có thể chọn chạy lại (`0`), truy cập website (`1`), hoặc Instagram (`2`).

Quay lại: Tại bất kỳ bước nào, nhập `0` để trở về bước trước.

## Liên hệ & Hỗ trợ

– Email: info@nhavantuonglai.com.

– Website: [nhavantuonglai.com](https://nhavantuonglai.com).

Nếu bạn có câu hỏi hoặc đề xuất, đừng ngần ngại liên hệ để được hỗ trợ nhanh nhất.

Đừng quên star repository này nếu bạn thấy nó hữu ích.
