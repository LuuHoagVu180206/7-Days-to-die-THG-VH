# 7 Days to die VH
Vietnamese transaltion for 7 days to die + some mods

How to do?
- Mỗi folder là 1 mod (Perkmastery của mod cùng tên, đặc biệt là 7days VH, nơi chứa mod Việt hóa cho game)
- Trong các folder có 1 folder con là config, trong đó chứa file localization của mod (đối với mod việt hóa thì chính là localize của game chính)
- Các file dưới dạng txt, sắp xếp theo 1 file csv (các cột là các dấu phẩy, xếp theo từng hàng)
- Có 2 cách để sửa các file việt hóa này
+ Cách 1: mở file bằng excel, chọn delimiter, chọn comma và finish, sẽ thành các hàng. Ta sẽ sửa trên hàng English. ĐIỂM TRỪ: khó track progress và kiểm tra commit do phải xuất từ trong excel ra csv rồi về text và lặp lại
+ Cách 2: Sửa thẳng trong txt, hơi đau mắt nhưng hiệu quả nhất vì có các phím tắt của vscode giúp rất nhiều, dễ commit hơn và dễ track progress cũng như conflict khi push hoặc pull