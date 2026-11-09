# PyMOL & AutoDock Vina Automation Scripts

Bộ công cụ kịch bản hỗ trợ chuẩn hóa cấu trúc Protein và Ligand phục vụ mô phỏng docking phân tử trong tính toán Hóa dược.

## 📂 Thư mục dự án
- `target_protein.pdb`: Cấu trúc không gian enzyme mục tiêu.
- `ligand_structure.sdf`: Cấu trúc phối tử hoạt chất thử nghiệm.
- `docking_config.txt`: Tệp thiết lập thông số lưới tọa độ Grid Box.

## 💻 Hướng dẫn chạy kịch bản trên PyMOL
```bash
pymol -c run_binding_site.pml
