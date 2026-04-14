# Industrial SCADA & IIoT Integration Project (Schneider Electric Ecosystem)

## 📝 Giới thiệu
Dự án tập trung vào thiết kế và triển khai hệ thống SCADA toàn diện, tích hợp giải pháp điều khiển với các nền tảng quản lý dữ liệu hiện đại. Hệ thống giải quyết bài toán đồng bộ hóa dữ liệu từ tầng thiết bị (Field) lên tầng quản lý (Cloud/IIoT).

## 🚀 Tính năng cốt lõi
- **Control Logic:** Lập trình điều khiển quy trình công nghiệp trên **Unity Pro (Schneider Electric)**, tích hợp bộ điều khiển **PID** để ổn định thông số hệ thống.
- **Advanced SCADA:** Thiết kế giao diện giám sát trên **CitectSCADA** sử dụng **Genies & SuperGenies**, giúp tối ưu hóa quản lý đối tượng và khả năng mở rộng hệ thống.
- **System Integration:** Sử dụng **KEPServerEX (OPC DA)** làm Gateway trung gian để kết nối mượt mà giữa PLC Simulator và phần mềm giám sát.
- **Data & IIoT:** - Lưu trữ dữ liệu lịch sử (Historical Data) qua **SQL/ODBC**.
    - Triển khai giao thức **MQTT** để đẩy dữ liệu vận hành lên Cloud, hỗ trợ giám sát từ xa.

## 🛠 Công nghệ sử dụng
- **PLC Software:** Unity Pro.
- **SCADA Software:** CitectSCADA 2016.
- **Connectivity:** KEPServerEX, MQTT Broker, MySQL/SQL Server.
- **Protocols:** Modbus TCP, OPC DA, MQTT.

## 📺 Demo
- [🎥 Xem Video Demo vận hành 1](https://drive.google.com/file/d/1RmHBvMWUq2vxMay4524icWQktTTmQMTd/view?usp=sharing)
- [🎥 Xem Video Demo vận hành 2](https://drive.google.com/file/d/10tO0DYcYLqrm7h78CkScgLoEreJAWxCp/view?usp=sharing)
- 
## 🏗 Kiến trúc hệ thống
![System Architecture](Technical_Report.pdf)

---
**Author:** Hoàng Lưu An Thái  
**Field:** Automation & Control Engineering
