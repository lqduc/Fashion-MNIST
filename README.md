# Fashion-MNIST
Fashion-MNIST with SVM, Multilayer Perceptron and ResNet

# 1. SVM và PCA
Mô hình SVM có rất nhiều loại kernel khác nhau. Ở đây, tôi chọn dùng Polynominal kernel.
Trước khi đưa vào mô hình học, chúng ta cần giảm số chiều dữ liệu (ban đầu là 28×28=784 chiều). Qua nhiều lần thực nghiệm, tôi nhận thấy rằng, số chiều dữ liệu ta giữ lại sau khi PCA có ảnh hưởng nhiều đến độ chính xác của bộ phân lớp SVM, cụ thể như sau:
| Số chiều PCA giữ lại | Độ chính xác trên tập test |
| ------------- | ------------- |
| 30  | 0.869  |
| 50  | 0.881  |
| 100 | 0.888  |
| 200	| 0.892  |
| 300	| 0.893  |
| 400	| 0.892  |
| 500	| 0.892  |
