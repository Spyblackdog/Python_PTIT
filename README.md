# Python_code
2/4/2025: NOTE: Trong Python xâu là giá trị bất biến không thể thay đổi bằng cách gán giá trị trực tiếp như list
          -Cách để đổi string trong sang list s = list(input())
          -join là phương thức thuộc str để nối các phần tử trong một list. Ví dụ "".join(s) nối các phần tử trong list s với ""
          -Trong set dùng issubset() để kiểm tra xem một set có là tập con của một tập hợp khác hay không 
          Ví dụ: A.issubset(B) trả về True nếu A là tập con của B ( Tất cả phần tử của A có trong B), False nếu ngược lại
          Hàm str.upper() để in ra một xâu được in hoa tương tự hàm lower() để in ra xâu in thường
          
          
          Bài tập tiêu biểu
          
          PY01003 - LÀM TRÒN SỐ 
          Cho số nguyên dương không quá 9 chữ số. Hãy làm tròn số N theo quy tắc sau:
          Nếu N>10, làm tròn đến số hàng chục gần nhất
          Sau đó nếu kết quả lớn hơn 100 thì làm tròn đến số hàng trăm gần nhất
          Sau đó nếu kết quả lớn hơn 1000 thì làm trong đến số hàng nghìn gần nhất
          Cứ tiếp tục như vậy …
          Chú ý: Giá trị 5 sẽ được làm tròn lên.
          Input:
          Dòng đầu ghi số bộ test (không quá 100)
          Mỗi bộ test ghi số N trên một dòng (N nguyên dương và không quá 9 chữ số)
          Output:
          Với mỗi test, ghi ra kết quả làm tròn tương ứng trên một dòng.
          Ví dụ
          Input                  Output
          7                      20
          15                     10
          14                     5
          5                      100
          99                     10000000
          12345678               50000000
          44444445               2000
          1445
          Cách giải: 
          Chuyển input sang list vì string không thể thay đổi trực tiếp giá trị 
          Duyệt từ cuối về đầu nếu giá trị >= 5 và không phải giá trị đầu tiên ta đổi thành 0 và cộng thêm 1 vào giá trị trước đó

2/6/2025 : Để lấy index của một phần tử xuất hiện trong một chuỗi ta có thể dùng s.index(x)
           Lưu ý trong Python để chuyển 1 ký tự sang ASCII ta dùng ord() vì phép " - " không thể thực hiện trong str
