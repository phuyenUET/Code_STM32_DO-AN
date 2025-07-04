# 🎓🎓🎓 **ĐỒ ÁN TỐT NGHIỆP**

## 🛠️ **Đề tài: Băng tải phân loại sản phẩm lỗi**

---

## 🔄 **Tiến độ thực hiện**

### ✅ Đã hoàn thành
#### ⚡ Phần mạch PCB - Code STM32F411CEU6 

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
- ✅ 🟢 **Cảm biến tiệm cận 1** – Hoạt động tốt

#### 🧑‍💻 YOLO-11n
- ✅ Model với 2 loại lỗi (chưa tối ưu lắm khiến fps hơi thấp)
- ✅ Phân loại ID với DeepSort

### ❌ Chưa hoàn thành

#### ⚡ Phần cứng

- ❌ 🛡️ Thêm **diode zener 3.3V** ổn áp bảo vệ chân **GPIOA (PA5, PA6, PA7)**  
  > ⚠️ Hiện nhận mức áp ~4.1V (cao hơn 3.3V tối đa)
- ❌ 🧭 **Cảm biến tiệm cận 2, 3** – Chưa tích hợp  
- ❌ 🧨 **Piston / Solenoid x2** – Chưa triển khai  
- ❌ 🚚 **Mua băng tải** – Chưa thực hiện  
- ❌ 🧃 **Tạo các mẫu lon nước** – Chưa làm  

---

#### 🤖 Jetson Nano

- ❌ 🔌 **UART giao tiếp với STM32**
- ❌ 🧠 **Huấn luyện tối ưu lại mô hình AI**
- ❌ 🚀 **Tối ưu bằng TensorRT**
- ❌ 🖼️ **Ứng dụng giao diện với Tkinter**
- ❌ 🌐 **IoT (MQTT/HTTP)**
- ❌ 💾 **Kết nối cơ sở dữ liệu (SQL)**

---

