![Main_User](https://github.com/user-attachments/assets/3c0135ee-5b1a-4f45-b4c0-683769477423)# 🎧 Customer Service
Project Customer Service adalah project yang dibuat dengan tujuan untuk belajar dan mengembangkan aplikasi Customer Service yang optimal. Project ini dirancang untuk meningkatkan efisiensi layanan pelanggan. Sistem ini mencakup fitur seperti manajemen sistem tiket, live chat, dan panggilan. Sistem ini dibuat dengan fokus pada skalabilitas dan antarmuka yang ramah pengguna, solusi kami adalah bertujuan untuk menyederhanakan operasional layanan dukungan dan meningkatkan kepuasan pelanggan.

# Fitur Utama
## 🎫 Sistem Tiket
Sistem tiket yang memudahkan pengguna dalam melacak status permintaan mereka, baik yang sedang diproses maupun yang masih dalam progres. Pengguna juga memiliki opsi untuk menutup tiket jika permasalahan telah terselesaikan. Bagi staf, sistem ini membantu dalam mengatur tiket dengan lebih efisien, mengelola prioritas, serta menetapkannya kepada staf lain yang bertanggung jawab. Selain itu, tiket yang ditampilkan kepada staf disesuaikan dengan departemen tempat mereka bekerja, sehingga setiap permintaan dapat ditangani oleh tim yang paling relevan.

## 📴 Status Aktif dan Nonaktif
Fitur ini dibuat untuk Customer Service agar mereka dapat menentukan status mereka, apakah sedang aktif atau tidak. Saat status aktif, mereka dapat menerima pesan dari pengguna. Namun, saat status nonaktif, mereka tidak akan menerima panggilan atau pesan dari pengguna.

## 📞 Panggilan dari Staf
Staf juga dapat melakukan panggilan kepada pengguna. Pengguna akan menerima notifikasi pop-up yang memungkinkan mereka untuk menerima atau menolak panggilan tersebut.

## 📱 Chat
Pengguna dapat menghubungi Customer Service melalui chat jika mereka tidak ingin melakukan panggilan.

# Mockup and link
### User
![Main_User](https://github.com/user-attachments/assets/cb256b06-5e38-4443-9b6f-a949c69407e3)

### Staff
![Main_Staff](https://github.com/user-attachments/assets/d4549e14-ba9b-44eb-baff-1e8664f443fa)

https://www.figma.com/design/VKJSIXUnaQw4XzC1S3JnIJ/Mockup-Customer-Service---6?node-id=1-7611&t=S7xeOmVqRJ63iTen-1

# ERD
This is are database design, subject to change to follow user needs
For now :
### One-to-Many (1:M) Relationships:

    User → Ticket
    Employee → Ticket
    Ticket → Messages
    Messages → File
    Departement → Employee

### Many-to-One (M:1) Relationships:

    Ticket → User
    Ticket → Employee
    Messages → Ticket
    File → Messages
    Employee → Departement
    
![ERD Image](https://github.com/NayakanW/Customer-Service/blob/main/ERD%20CS.png?raw=true)


# Referensi Website
- [osTicket](https://osticket.com/) - An Open Source Supporting Ticket Software  
- [Open Support](https://github.com/opensupportapp/opensupport) - Simple Open Source Ticket System, made with React and Ruby  
- [Jira Service Management](https://www.atlassian.com/software/jira/service-management) - Automation for ticketing software  
