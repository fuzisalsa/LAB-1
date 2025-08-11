# LAB-1 
tanggal 11 agustus 2025

logging in mikrotik

![topologi](topologi1.jpeg)

Lakukan logging in ke mikrotik dengan beberapa cara :
   
Tuliskan langkah-langkah nya :

# 1. winbox 
   
      Cara Pertama yaitu menggunakan aplikasi winbox yang dapat didownload di mikrotik.com,

      berikut langkah nya:

      a. Buka Winbox,

      b. Klik Tab Neighbors lalu Refresh

      c. Setelah muncul, pilih MAC Address

      d. Login: admin

      Password:

      e. Klik Connect

   ![topologi](scwinbox.PNG)

      f. jika sudah berhasil login, maka akan muncul tampilan seperti ini:

   ![topologi](scwinbox1.PNG)

# 2. webfig 
   
      Cara kedua menggunakan webfig (menggunakan web browser)

      berikut ini langkah nya:

      a. Buka chrome (aplikasi web browser)

      b. Pada URL ketik IP Address: 192.168.88.1 (ip default mikrotik)

      c. Setelah itu, maka akan muncul tampilan mikrotik dalam mode GUI pada web
      browser

![topologi](scwebfig.PNG)

# 3. Telnet 

      Cara ketiga menggunakan telnet pada aplikasi putty.

      berikut ini langkah nya:

      a. Buka putty

      b. Klik Tab Telnet

      c. Ketik IP Address: 192.168.88.1 (ip default mikrotik)

      d. Ketik Port: 23 (port default telnet)

      e. Klik Open 

![topologi](scpty.PNG)

      f. Login: admin

      Password:

      Tekan Enter

![topologi](scpty1.PNG)

      g. Setelah berhasil login, maka akan muncul tampilan mikrotik dalam mode CLI

![topologi](scpty2.PNG)


# 4. SSH 

      Cara keempat menggunakan SSH pada aplikasi putty

      berikut ini langkah nya:

      a. Buka putty

      b. Klik Tab SSH

      c. Ketik IP Address: 192.168.88.1 (ip default mikrotik)

      d. Ketik Port: 22 (port default telnet)

      e. Klik Open 

![topologi](scssh1.PNG)

      f. Login: admin

      password:

      Tekan Enter

![topologi](scssh2.PNG)

      g. Setelah berhasil login, maka akan muncul tampilan mikrotik dalam mode CLI

![topologi](scssh3.PNG)

# 5. FTP (filezilla) 

      Akses mikrotik via FTP (filezilla) bermanfaat untuk upload dan download file ke router mikrotik.

      a. Buka filezilla

      b. Isi Host: 192.168.88.1 (ip default mikrotik)
      
      c. Login: admin dan without password:
         
      e. Ketik Port: 21 (port default ftp)
      
      f. Klik Quickconnect


