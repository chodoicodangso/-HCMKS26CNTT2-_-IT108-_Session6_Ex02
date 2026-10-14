Phần 1: Phân tích  
**Sự nhầm lẫn của An:** An bị nhầm lẫn giữa tư duy **tìm kiếm tệp tin** (tên/vị trí tệp) và **tìm kiếm nội dung** bên trong tệp.  
**Sự khác biệt:**  
Get-ChildItem: Dùng để **liệt kê và tìm kiếm tệp/thư mục** dựa trên tên hoặc đường dẫn (không đọc nội dung bên trong).  
Select-String: Dùng để **tìm kiếm chuỗi văn bản/nội dung** cụ thể nằm bên trong các tệp tin.  
Phần 2: Hoàn thiện  
Select-String \-Path "access.log" \-Pattern "error"  
