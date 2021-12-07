Giới thiệu Numpy

Numpy là một thư viện Python được sử dụng để làm việc với Mảng (array). Ngoài ra, Numpy còn có một số chức năng làm việc với Linear Algebra, Fourier transform và Matrix. Numpy được viết tắt từ Numerical Python.

Đối tượng quan trọng nhất được định nghĩa trong Numpy là mảng nhiều chiều (N-dimensional array), được gọi là ndarray. Nó được mô tả là tập hợp các item có cùng loại dữ liệu. Mảng (array) được sử dụng rất thường xuyên trong data science. Các item được truy xuất thông qua vị trí (index) của nó, bắt đầu bằng vị trí 0.

Trong Python, chúng ta cũng có kiểu dữ liệu tương tự như array là list. Tuy nhiên, kiểu dữ liệu list xử lý chậm hơn array. Array trong Numpy nhanh gấp 50 lần so với list.

1. Cài đặt thư viện Numpy
pip install numpy

Trong trường hợp sử dụng Anacona thì kg cần cài đặt, vì mặc định thư viện Numpy đã được cài.

2. Sử dụng thư viện Numpy.
Để sử dụng được thư viện Numpy, chúng ta phải import thư viện này vào.
import numpy as np