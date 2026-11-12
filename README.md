# Corel Automation Panel

Bộ cài và nguồn cập nhật cho Corel Automation Panel trên **CorelDRAW 2021 64-bit**.

## Tải và cài đặt

[Tải bộ cài mới nhất tại GitHub Releases](https://github.com/o962274908-bit/toolcorel/releases/latest).

1. Máy cần cài CorelDRAW Graphics Suite 2021 64-bit và .NET Framework 4.8 trở lên.
2. Tải tệp `CorelAutomationPanel-Setup-<phiên bản>.exe` trong phần Assets.
3. Lưu bản vẽ, đóng CorelDRAW và Chrome đang dùng Saban ChatGPT.
4. Chạy bộ cài, đồng ý yêu cầu quyền Administrator của Windows và chọn đúng thư mục CorelDRAW.
5. Mở lại CorelDRAW, vào Window > Dockers > Corel Automation Panel.

CorelDRAW không được kèm trong bộ cài. Hướng dẫn chi tiết nằm trong tệp
`HUONG-DAN-CAI-DAT.txt` tại mỗi Release.

## Cập nhật

Từ bản 1.1.0, nút **Cập nhật** nằm ở góc dưới bảng công cụ. Tool kiểm tra bản
ổn định mới nhất khi mở, tối đa một lần mỗi ngày; có thể tắt tự kiểm tra.
Khi có bản mới, bấm tải và mở bộ cài. Tệp tải về phải khớp kích thước và SHA256
do GitHub cung cấp trước khi tool cho phép mở.

Máy dùng bản 1.0.0 cần cài bản 1.1.0 hoặc mới hơn một lần để có chức năng này.
Lưu bản vẽ và đóng CorelDRAW trước khi tiếp tục cài đặt bản cập nhật.

## Saban ChatGPT

Nếu dùng chức năng Saban ChatGPT, mở `chrome://extensions`, bật Developer mode,
chọn Load unpacked và chọn thư mục:

```text
<Thư mục CorelDRAW>\Programs64\Addons\MyCorelPlugin\BrowserExtension
```

ID tiện ích: `hneobfodalipfmjpeocjkpooejcdnpbe`. Đăng nhập ChatGPT bằng tài khoản
của bạn và bấm Kết nối với Corel trong tiện ích. Sau khi cập nhật tool, tải lại
tiện ích trong Chrome.

## Gỡ cài đặt

Gỡ Corel Automation Panel trong Windows Settings > Apps, hoặc mở `Uninstall.exe`
trong thư mục plugin. Bản vẽ, thiết lập cá nhân và tệp riêng được giữ lại.
