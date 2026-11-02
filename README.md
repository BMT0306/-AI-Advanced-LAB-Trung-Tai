# AI-Advanced-LAB-Trung-Tai

Kho lưu trữ bài tập thực hành nhóm môn **Trí Tuệ Nhân Tạo Nâng Cao** (Advanced Artificial Intelligence).

- **Thành viên nhóm:** 
  - Bùi Minh Trung (MSSV: 3124720074)_VaiTrò: Người code, chạy test notebook
  - Nguyễn Thành Tài (MSSV: 3124720062)_Vai Trò: Người làm báo cáo

---

## Cấu trúc thư mục

### 1. `Lab01_Agent`
- **Mục tiêu:** Xây dựng và mô phỏng các Agent thông minh trong môi trường xác định và ngẫu nhiên.
- **Notebooks:**
  - `robot_vacuum_b2.ipynb`: Mô phỏng agent robot hút bụi lau sàn.
  - `gridhunt_mini_assignment_b3.ipynb`: Mini assignment Gridhunt tìm đường trên lưới.
  - `gridhunt_multiagent_mini_assignment_b4.ipynb`: Mở rộng Gridhunt cho môi trường đa tác tử (Multi-agent).
  - `lunar_lander_b5.ipynb`: Điều khiển hạ cánh tàu vũ trụ Lunar Lander.

### 2. `Lab02_Search`
- **Mục tiêu:** Thuật toán tìm kiếm theo không gian trạng thái (BFS, DFS, Uniform Cost Search, Greedy, A* và Heuristics) giải quyết bài toán mê cung (Maze).
- **Files chính:**
  - `01_trees.ipynb`, `02_Maze_Example.ipynb`, `03_Maze_Example_Animation.ipynb`, `04_Maze_BFS_vs_A_Star.ipynb`, `05_Maze_Example-Animation_Cycle_checking.ipynb`, `06_Explore_heuristics.ipynb`
  - Các bài tập mở rộng: `Ex1_Maze.ipynb`, `Ex2_Maze_simplified.ipynb`, `Ex3_Show_all_mazes.ipynb`
  - Dữ liệu mê cung: `empty_maze.txt`, `large_maze.txt`, `L_maze.txt`, `medium_maze.txt`, `small_maze.txt`,...
  - Module hỗ trợ: `maze_helper.py`, kết quả thực nghiệm `results_all_algorithms.csv`.

### 3. `Lab03_LocalSearch`
- **Mục tiêu:** Các kỹ thuật tìm kiếm cục bộ (Local Search): Hill Climbing, Simulated Annealing (tôi luyện mô phỏng), áp dụng cho bài toán Traveling Salesman Problem (TSP) và N-Queens.
- **Files chính:**
  - `notebooks/traveling_salesman_problem.ipynb`: Bài toán người bán hàng TSP qua Simulated Annealing.
  - `notebooks/Simulated_Annealing_Schedules.ipynb`: Thử nghiệm các hàm giảm nhiệt độ (Cooling Schedules).
  - `notebooks/n_queens.ipynb`: Bài toán N quân hậu qua tìm kiếm cục bộ.
  - `notebooks/n_queens_fast_conflict_calculation_with_numba.ipynb`: Tối ưu tính toán xung đột nhanh bằng Numba.
  - `notebooks/Maze_Example_LocalSearch.ipynb`: Ứng dụng leo đồi trên mê cung.
  - `requirements.txt`, thư mục `hinh_minh_hoa/`.

### 4. `Lab04_CSP`
- **Mục tiêu:** Bài toán thỏa mãn ràng buộc (Constraint Satisfaction Problems - CSP) với kỹ thuật quay lui, kiểm tra trước (Forward Checking), lan truyền ràng buộc (AC-3), và Heuristics (MRV, Degree, LCV).
- **Notebooks:**
  - `CSP_graph_coloring_example.ipynb`: Bài toán tô màu bản đồ/đồ thị.
  - `n_queens.ipynb`: Giải bài toán N-Queens dưới dạng bài toán CSP.

---
*Ghi chú: File tài liệu báo cáo (.docx/.pdf) của các buổi Lab được phân chia commit và cập nhật riêng bởi thành viên trong nhóm.*
