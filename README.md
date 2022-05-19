vector.ipynb: demo về vector cơ bản trong numpy  

vector trong python là một mảng 1 chiều:  
 1 dòng, n cột - horizontal vector (vector ngang) hoặc  
 1 cột, n dòng - vertical vector (vector dọc)

vector không được rỗng  
Độ dài của một vector trong python: số lượng phần tử cấp cao nhất (nhưng phải cùng cấp) của vector (mảng) đó

Khái niệm vector:  
https://www.journaldev.com/46432/vectors-in-python

Ma trận  
 Là mảng 2 chiều trở lên  
 Chứa số hoặc chuỗi hoặc cả hai

Truy vấn theo chỉ mục (indexing) trong ma trận numpy:  
    start: chỉ số bắt đầu  
    stop: chí số kết thúc (sẽ không được tính)  
    step: bước nhảy  

    Ex: 2d matrix
        [0:2, :] -> Từ dòng 0 đến 1 (dừng ở 2) và tất cả các cột của matrix

    Tham khảo thêm trong mục Indexing: https://numpy.org/doc/stable/user/quickstart.html

Xác định ma trận theo chỉ số của dòng, cột:

Để nhân ma trận, số lượng cột trong ma trận thứ nhất phải bằng số lượng hàng trong ma trận thứ hai  
Nhân hai ma trận dùng numpy  
https://www.geeksforgeeks.org/python-program-multiply-two-matrices/

Tạo ma trận 2d ngẫu nhiên với kích thước cho trước:  
https://www.codespeedy.com/how-to-create-matrix-of-random-numbers-in-python-numpy/