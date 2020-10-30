# Fashion-MNIST
Fashion-MNIST with SVM, Multilayer Perceptron and ResNet

# 1. SVM và PCA
Mô hình SVM có rất nhiều loại kernel khác nhau. Ở đây, tôi chọn dùng Polynominal kernel.
Trước khi đưa vào mô hình học, chúng ta cần giảm số chiều dữ liệu (ban đầu là 28×28=784 chiều). Qua nhiều lần thực nghiệm, tôi nhận thấy rằng, số chiều dữ liệu ta giữ lại sau khi PCA có ảnh hưởng nhiều đến độ chính xác của bộ phân lớp SVM, cụ thể như sau:
