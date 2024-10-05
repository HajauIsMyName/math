### **1. Khái niệm chung về phép biến hình**

- **Phép biến hình**: Là quá trình biến đổi một hình trên mặt phẳng thành một hình khác, mà các yếu tố về kích thước, hình dạng có thể thay đổi hoặc giữ nguyên. 
- **Tính chất cơ bản**:
  - Giữ nguyên các quan hệ giữa các điểm như thẳng hàng, tỷ lệ đoạn thẳng, góc, và diện tích (tùy loại biến hình).
  - Biến một hình này thành hình khác nhưng không làm thay đổi bản chất của hình.

---

### **2. Các loại phép biến hình cơ bản**

#### **Phép tịnh tiến**
- **Định nghĩa**: Phép tịnh tiến biến mỗi điểm M của một hình thành điểm M’ sao cho M và M’ nằm trên cùng một đường thẳng, và khoảng cách từ M đến M' bằng một đoạn cố định theo hướng nhất định.
- **Công thức**: 
  \[
  T_{\overrightarrow{v}}: \vec{M'} = \vec{M} + \overrightarrow{v}
  \]
  (với \(\overrightarrow{v}\) là vector tịnh tiến)
- **Ví dụ minh họa**: Dời điểm A(2, 3) theo vector \( \overrightarrow{v} = (4, 1) \), điểm A' sẽ có tọa độ (6, 4).
  
#### **Phép quay**
- **Định nghĩa**: Phép quay biến điểm M thành điểm M' qua một góc quay \(\theta\) quanh một tâm O cố định.
- **Công thức**:
  \[
  R(O, \theta): \vec{M'} = R_{\theta} \times \vec{M}
  \]
  (trong đó \(R_{\theta}\) là ma trận quay với góc \(\theta\))
- **Ví dụ minh họa**: Quay điểm A(1, 0) một góc 90 độ quanh gốc O(0, 0) sẽ đưa A đến tọa độ A'(0, 1).

#### **Phép đối xứng trục**
- **Định nghĩa**: Phép đối xứng trục biến một điểm M thành điểm M’ qua một đường thẳng (trục đối xứng) sao cho đường thẳng nối M và M' vuông góc với trục, và khoảng cách từ M đến trục bằng khoảng cách từ M' đến trục.
- **Công thức**: 
  \[
  D_d(M) = M'
  \]
  (với \(d\) là trục đối xứng)
- **Ví dụ minh họa**: Điểm A(3, 2) đối xứng qua trục \(y = 1\) sẽ thành điểm A'(3, 0).

#### **Phép đối xứng tâm**
- **Định nghĩa**: Phép đối xứng tâm biến một điểm M thành điểm M’ qua một điểm O (tâm đối xứng) sao cho O là trung điểm của đoạn thẳng MM'.
- **Công thức**: 
  \[
  D_O(M) = M'
  \]
  (với O là tâm đối xứng)
- **Ví dụ minh họa**: Điểm A(3, 2) đối xứng qua gốc O(0, 0) sẽ thành điểm A'(-3, -2).

#### **Phép vị tự**
- **Định nghĩa**: Phép vị tự biến một hình thành một hình tương tự nhưng có kích thước thay đổi, với tỷ lệ \(k\) cố định.
- **Công thức**:
  \[
  V_O^k(M) = M'
  \]
  (với O là tâm vị tự và \(k\) là hệ số vị tự)
- **Ví dụ minh họa**: Điểm A(2, 3) sau phép vị tự với tâm O(0, 0) và tỷ lệ \(k = 2\) sẽ thành điểm A'(4, 6).

---

### **3. Ứng dụng của các phép biến hình**

- **Thiết kế đồ họa**: Các phần mềm đồ họa sử dụng các phép quay, tịnh tiến để biến đổi hình ảnh.
- **Kỹ thuật xây dựng**: Trong xây dựng cầu đường, phép đối xứng và phép tịnh tiến được sử dụng để tính toán các kết cấu.
- **Robot học**: Phép biến hình dùng trong các thuật toán điều khiển robot di chuyển trong không gian.

---

### **4. Ví dụ thực tế và bài tập**

#### Ví dụ minh họa:
- **Bài toán**: Cho hình tam giác ABC có các đỉnh A(1, 2), B(4, 5), C(2, 3). Thực hiện phép quay quanh gốc O với góc quay 90 độ. Tìm tọa độ các điểm A’, B’, C’.
- **Lời giải**: Tọa độ mới của A', B', C' sẽ lần lượt là: A'(-2, 1), B'(-5, 4), C'(-3, 2).

#### Bài tập thực hành:
1. Cho điểm P(2, 3). Tịnh tiến P theo vector \( \overrightarrow{v} = (1, -1) \). Tìm tọa độ điểm P’.
2. Quay điểm Q(1, 2) một góc 180 độ quanh gốc O(0, 0). Tìm tọa độ điểm Q’.
3. Điểm D(3, 5) đối xứng qua trục \(x = 0\). Tìm tọa độ điểm D'.
