# Lab03 – Tìm kiếm cục bộ (Local Search)

## Nội dung gói nộp
- `Bao_cao_Lab03_Tim_kiem_cuc_bo.docx`: báo cáo có trang bìa, mục lục, bảng kết quả, hình minh họa, câu hỏi thảo luận và phần nhận xét tổng hợp.
- `notebooks/n_queens.ipynb`: các biến thể Hill Climbing, Random Restart, Simulated Annealing, benchmark 100 lần, hội tụ, khả năng mở rộng và phân tích toán tử di chuyển nâng cao.
- `notebooks/traveling_salesman_problem.ipynb`: Steepest HC, Random Restart, Stochastic HC, First-choice HC, SA; benchmark 20 lần cho mỗi thuật toán/kích thước.
- Các notebook minh họa mê cung, lịch nhiệt và tối ưu đếm xung đột Numba.
- `notebooks/L_maze.txt` và `notebooks/maze_helper.py` được đặt cạnh notebook mê cung để tránh phụ thuộc đường dẫn máy cá nhân.

## Cách chạy
1. Giải nén toàn bộ gói và mở thư mục `notebooks`.
2. Cài Python 3.10+ và các thư viện: `numpy`, `matplotlib`, `pandas`, `scipy`, `numba`, `ipython`, `jupyter`.
3. Mở Jupyter Notebook/JupyterLab, chọn kernel Python và chạy từng notebook từ trên xuống.
4. Với `n_queens.ipynb`, các benchmark 100 lần và phân tích toán tử nâng cao có thể mất thêm thời gian.
5. Các kết quả thời gian phụ thuộc máy và phiên bản thư viện. Seed đã được thiết lập để tăng khả năng tái lập; thời gian chạy vẫn có thể dao động.

## Lưu ý
- Điền họ tên, mã sinh viên, lớp và bảng thành viên/mức đóng góp trên trang bìa trước khi nộp.
- Các phần Genetic Algorithm được ghi rõ là bài bonus tùy chọn; không thuộc các yêu cầu cốt lõi của báo cáo này.
