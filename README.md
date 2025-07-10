# 🎓🎓🎓 **ĐỒ ÁN TỐT NGHIỆP**

## 🛠️ **Đề tài: Băng tải phân loại sản phẩm lỗi**

---

## 🔄 **Tiến độ thực hiện**

### ✅ Đã hoàn thành
#### ⚡ Phần mạch PCB - Code STM32F411CEU6 
- ✅ ⚡ **PCB** - Bản thử đầu hoạt động tốt với các chức năng:
  - Điều chỉnh động cơ băng tải.
  - Cảm biến tiệm cận x3 - đã test
  - Màn hình LCD hiện thông số
  - Điều khiển 2 Servo MG966R. 
  - Thuật toán xử lý mảng error[100] UART gửi char lỗi qua.
 
- ✅   **Code servo MG996R** 
- ✅ 🔍 **ADC** – Đọc giá trị từ chiết áp  
- ✅ ⏱️ **Timer1 - Fast PWM** – Gửi xung điều khiển duty cycle cho L293D  
- ✅ ⏰ **Timer2 - Interrupt 1s**  
  - Cập nhật tốc độ **Speed**  
  - Đếm xung từ **encoder**  
  - Tính RPM theo công thức:
    ```
    Speed (RPM) = (Số xung trong 1 giây * 60) / (Số xung mỗi vòng)
    ```
- ✅ 📡 **UART** – Giao tiếp UART hoạt động ổn định  
- ✅ ⚙️ **Động cơ** – Đã kiểm tra, hoạt động tốt  
- ✅ 🟢 **Cảm biến tiệm cận 1,2,3** – Hoạt động tốt
- ✅ **Băng tải** đã lắp xong

#### 🤖 Jetson Nano
- ✅ **UART** - Đã giao tiếp được qua USB TTL CP2102
- ✅ **Thư viện cần thiết**: ttkbootstrap, torch, torchvision, sqlite3, ultralytics, tkinter, deep-sort-realtime, serial,..
- ✅ Model với 2 loại lỗi (chưa tối ưu lắm khiến fps hơi thấp)
- ✅ Phân loại ID với DeepSort

### ❌ Chưa hoàn thành

#### ⚡ Phần mạch PCB - Code STM32F411CEU6 
---
#### 🤖 Jetson Nano

- ❌ 🧠 **Huấn luyện tối ưu lại mô hình AI**
- ❌ 🚀 **Tối ưu bằng TensorRT**
- ❌ 🖼️ **Ứng dụng giao diện với Tkinter**
- ❌ 🌐 **IoT (MQTT/HTTP)**
- ❌ 💾 **Kết nối cơ sở dữ liệu (SQL)**

---
- ❌ Hoàn thiện phần cứng và đặt mạch final từ JLCPCB.
---

