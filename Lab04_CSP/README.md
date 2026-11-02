# Lab 04 — Constraint Satisfaction Problems (CSP)

## Nội dung
- `CSP_graph_coloring_example.ipynb`: mô hình hóa CSP tô màu đồ thị; kiểm thử `complete`/`consistent`; Backtracking, MRV, LCV, Forward Checking và Min-Conflicts; benchmark nhiều kích thước và 3/4 màu trên 5 seed; biểu đồ so sánh số nút tìm kiếm.
- `n_queens.ipynb`: mô hình hóa n-Queens; ba biến thể Hill Climbing; Random Restart; Simulated Annealing với hai lịch làm nguội; benchmark 100 lượt tại n=4 và n=8; đồ thị hội tụ và log-log thời gian; phần toán tử di chuyển nâng cao và Genetic Algorithm.
- `Baocao.docx`: báo cáo có bổ sung bảng số liệu từ lần chạy notebook, hình minh họa, nhận xét và giới hạn thực nghiệm.

## Môi trường và thư viện
Python 3; `numpy`, `scipy`, `matplotlib`, `pandas`, `jupyter`.

Cài đặt (nếu môi trường chưa có):
```bash
python -m pip install numpy scipy matplotlib pandas jupyter
```

## Cách chạy
1. Giải nén ZIP vào một thư mục tùy ý.
2. Mở terminal tại thư mục đó và chạy `jupyter notebook` hoặc `jupyter lab`.
3. Mở từng notebook, chọn **Restart Kernel and Run All**.
4. Kiểm tra kết quả và lưu lại notebook sau khi chạy hoàn tất.

Notebook không phụ thuộc đường dẫn Google Drive cá nhân. Kết quả thời gian có thể thay đổi theo phần cứng và phiên bản thư viện.

## Ghi chú về phương pháp
- Tô màu đồ thị: 5 seed cho mỗi tổ hợp kích thước/số màu; đây là đánh giá sơ bộ. Min-Conflicts không tìm được nghiệm trong giới hạn bước không đồng nghĩa đã chứng minh vô nghiệm.
- n-Queens: 100 lượt cho mỗi thuật toán ở n=4 và n=8. Random Restart dùng tối đa 20 lần khởi động lại mỗi lượt (nằm trong giới hạn tối đa 100 lần của đề).
- Biểu đồ log-log dùng 3 lượt mỗi kích thước để giữ thời gian chạy hợp lý; nên tăng số lần lặp nếu cần nghiên cứu hiệu năng chính thức.
- Thời gian đo được là thực nghiệm trên môi trường chạy hiện tại, không phải cam kết về hiệu năng trên mọi máy.
