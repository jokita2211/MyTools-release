# MyTools-release

Bản phát hành MyTools (bộ tool pyRevit cho Revit 2023 và 2025). Repo này chỉ chứa file zip trong mục **Releases**, không chứa mã nguồn.

## Mỗi bản phát hành gồm
| File | Dùng để |
|---|---|
| `MyTools-v<x.y.z>.zip` | Gói tool đầy đủ |
| `latest.json` | Thông tin bản mới nhất (số phiên bản, sha256, danh sách thay đổi) cho nút Cập nhật Tool |
| `cai_dat.ps1` | Cài lần đầu, hoặc cài tay khi Revit đang khóa thư mục tool |

Tải bản mới nhất: [Releases / latest](https://github.com/jokita2211/MyTools-release/releases/latest)

## Cập nhật
Trong Revit: tab **Jokita** (bản trước v2.0.0: tab Sheets) > **Cài Đặt > Cập nhật Tool**. Tool tự tải bản mới, kiểm tra sha256, giữ bản cũ để quay lại khi lỗi.

Nếu tool báo thư mục đang bị khóa: đóng Revit, tải `cai_dat.ps1` ở trang Releases, chuột phải > **Run with PowerShell**.

## Yêu cầu
- pyRevit đã cài.
- Revit 2023 (IronPython 2.7) hoặc Revit 2025 (CPython 3).
