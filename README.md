# Book Rental Library

## Thành viên
1. Đỗ Đình Trường 
2. Nguyễn Đức Thắng
3. Đinh Quang Vũ
4. Trần Nguyễn Khánh Ninh
5. Đỗ Hồng Phong

## Demo website:
[Demo](http://3.1.80.54)

[Swagger UI](http://3.1.80.54:5000)

## Github

Phần hướng dẫn cài đặt từng phần sẽ trong readme của Frontend và Backend

[Frontend](https://github.com/truongdo619/UET_BookRentalLibrary)

[Backend](https://github.com/dhphong/UET_BookRentalLibrary_Backend)

[Search Engine - Recommender System](https://github.com/thanglegons/Porg)

## Tổng quan về hệ thống

### SRS-Document

[Software requirements specification](/SRS_Web.pdf)

### Back-End

Flask, Flask-RESTPlus, Swagger UI

![alt Flash](https://miro.medium.com/max/438/1*0G5zu7CnXdMT9pGbYUTQLQ.png)

### Front-End

VueJS + Element UI

![alt Vue](https://zendvn.com/wp-content/uploads/2019/09/Vue.js-cta-main.jpg)

### Database-Schema

![alt db](/db.png)


## Các chức năng chính

### Homepage
![alt homepage](/version2/Homepage.png)

- Trang chủ của hệ thống bao gồm thanh tìm kiếm, danh sách sách gợi ý cho người dùng.
- Các quyển sách, tác giả, thể loại phổ biến.

### Search Page
![alt searchpage](/version2/SearchPage.PNG)

- Sách được hiển thị bao gồm bìa sách, tên sách, tên tác giả, năm xuất bản, số lượng sách còn lại và đánh giá.
- Hệ thống tìm kiếm những quyển sách có tên giống hoặc gần giống với từ khóa của user (ưu tên giống tên).
- Có thể sử dụng các filter genre để tìm sách ở các Category khác nhau.
- Gợi ý cho User về các thể loại sách liên quan tới từ khóa và số lượng sách của từng thể loại.

### Book Detail
![alt bookdetail](/version2/BookDetail.png)

- Hiển thị các thông tin cơ bản của sách, lựa chọn thuê sách và review của các khách hàng khác.
- Đánh giá sách qua comment chi tiết và hệ thống đánh giá theo sao (1 - 5 sao)

### User Page
![alt bookdetail](/version2/UserPage.png)

- Trang hiển thị các thông tin cơ bản của người dùng, danh sách sách đang mượn, đang cho mượn và đã mượn.
ví tiền của người dùng, các hoạt động gần đây (thuê sách, đánh giá sách, ...)

### Log In Page
![alt bookdetail](/version2/SignIn.png)

### Sign Up Page
![alt bookdetail](/version2/SignUp.png)
