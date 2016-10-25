#Bài 4: Dữ liệu kiểu mảng
##1.Khái niệm:
- Mảng được hiểu là một tập hợp các giá trị có cùng kiểu dữ liệu nằm liên tiếp nhau trong bộ nhớ máy tính
- Mảng được coi như một biến mảng và tên mảng được đặt theo quy tắc đặt tên biến 
- Mảng có những thành phần sau:
- Kiểu dữ liệu của các phần tử trong mảng
- Tên mảng
- Số chiều và kích thước của mỗi chiều
##2. Cách khai báo biến mảng
	<kiểu_dl> <tên_mảng>[<ds các chiều của mảng>]
	-VD: 	
  
			int A[10]; 
      
//mảng 1 chiều A gồm 10 phần tử kiểu số nguyên

			float B[2] [3];
      
// Mảng 2 chiều B gồm 2 hàng và 3 cột, các phần tử có kiểu số thực

##3.Cách tổ chức và truy xuất đến phần tử mảng
Phần tử của mảng được xác định thông qua chỉ số. Chỉ số của phần tử trong mảng luôn là một số nguyên không vượt qua kích thước của mảng
Các phần tử của mảng được sắp xếp liền nhau trong bộ nhớ của máy tính và chỉ cho phép truy cập đến địa chỉ trực tiếp của phần tử đối với mảng một chiều. Cách truy cập theo địa chỉ 

  `&tên_biến[i]  `

trong đó i là chỉ số của phần tử

 VD:  	a= &a[0]
 
//Tên mảng chỉ tới địa chỉ phần tử đầu tiên của mảng

##4. Cách xuất nhập dữ liệu trên mảng
Nhập xuất trực tiếp ứng dụng cho mảng một chiều và mảng hai chiều có phần tử kiểu int thông qua địa chỉ 
Nhập dữ liệu cho mảng
	`for( i=0;i<5;i++) {
			printf(“Phan tu thu %d= ”,i);
			scanf(“%d”, &a[i]);
		}` 
-	In các phần tử của mảng ra màn hình

	`for(i=0;i<n;i++)  printf(“%6d”,a[i])`		
  
  ###Nhập xuất dữ liệu gián tiếp thông qua một biến trung gian đối với mảng một chiều và mảng đa chiều
	`for(i=0;i<2;i++)
		for(j=0;j<3;j++) {
			printf(“a[%d,%d]”, i, j);
			scanf(“%f”,&temp);
			a[i] [j] = temp;
		}`
#Kiểu mảng

###Khi làm việc với các cấu trúc dữ liệu dạng dãy hay danh sách các phần tử, ta sử dụng kiểu mảng (array)
- Mảng 1 chiều: một vec-tơ các phần tử
- Mảng nhiều chiều: một bảng các phần tử
###Mảng một chiều
- Dãy các phần tử có cùng kiểu dữ liệu
- Các phần tử được sắp xếp theo trật tự nhất định

##Cú pháp khai báo mảng một chiều
	`kiểu_dữ_liệu tên_mảng[số_phần_tử_của_mảng];` 
Ví dụ
`int ai[10];
float af[100];`
Số phần tử mảng được xác định khi khai báo
Sử dụng toán tử [] để truy cập phân tử của mảng
Ví dụ: ai[2], af[10], …
Chỉ số các phần tử mảng được đánh số từ 0




