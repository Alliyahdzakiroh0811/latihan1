 Cara membuat file readme.md
1.	Download Git Bashhttps://git-scm.com/downloads Download sesuai OS masing-masing
  
![image](https://user-images.githubusercontent.com/56861575/67495501-358d4c00-f6a5-11e9-8fc2-5806bf4a9d5b.png)

2.	Setelah download dan di install, langkah selanjutnya buka aplikasi Git Bashyang tadi sudah di download
 
![image](https://user-images.githubusercontent.com/56861575/67495521-3e7e1d80-f6a5-11e9-8989-e6e21c13c63a.png)

3.	Lalu Git Bash akan terbuka, dan ketik perintah git –version
 
![image](https://user-images.githubusercontent.com/56861575/67495879-c5cb9100-f6a5-11e9-999e-1af278e7df95.png)


4.	Langkah selanjutnya ketik perintah user.namedan user.email
 
![image](https://user-images.githubusercontent.com/56861575/67495882-c6fcbe00-f6a5-11e9-81e1-279c688a10e0.png)

5.	Lalu untuk membuat folder yg bernama latihan1ketik perintah mkdir latihan1
 
![image](https://user-images.githubusercontent.com/56861575/67495900-cbc17200-f6a5-11e9-89eb-131feb90aaa5.png)

6.	Lalu akan muncul folder bernama latihan1
 
![image](https://user-images.githubusercontent.com/56861575/67495982-eb589a80-f6a5-11e9-9f90-e7e1d944531e.png)

7.	Setelah itu kembali kedalam aplikasi Git Bash lalu ketik cd latihan1 untuk masuk ke dalam direktori tersebut

8.	Selanjutnya untuk membuat file README.md lalu d isikian dengan text latihan 1 dengan menjalankan perintah $  echo “#latihan 1” >> README.md
 
![image](https://user-images.githubusercontent.com/56861575/67496072-0b885980-f6a6-11e9-8ecf-0d39e0930f57.png)


9.	Jika berhasil maka akan muncul file README.md di dalam folder latihan1 yang pertama kali di buat di awal
 
![image](https://user-images.githubusercontent.com/56861575/67496089-117e3a80-f6a6-11e9-86bb-7e353526b43f.png)

10.	Jalankan perintah gitinit, untuk membuat repository local
 
![image](https://user-images.githubusercontent.com/56861575/67496104-1e029300-f6a6-11e9-98cf-e96249c73cdd.png)

11.	Jika berhasil maka akan muncul direktori hidden .git
 
![image](https://user-images.githubusercontent.com/56861575/67496116-235fdd80-f6a6-11e9-9ab1-22cd21cc9996.png)

12.	Lalu untuk langkah selanjutnya ketik perintah git add README.md
 
![image](https://user-images.githubusercontent.com/56861575/67496134-278bfb00-f6a6-11e9-99a3-5316abe20e3a.png)

13.	Selanjutnya ketik perintah git commit –m “first commit” 

![image](https://user-images.githubusercontent.com/56861575/67496150-2d81dc00-f6a6-11e9-9ff3-345f18a5e0f4.png)

TURTORIAL MEMBUAT REPOSITORY SERVER
1.	Buatlah repisiory di Github.comdengan nama latihan 1, lalu klik create repository
 
![image](https://user-images.githubusercontent.com/56861575/67496166-35418080-f6a6-11e9-98d2-8bc14bb0fa40.png)

2.	setelah itu kembali ke Git Bash dengan mengetik perintah git remote add origin [url]
 
![image](https://user-images.githubusercontent.com/56861575/67496196-3f637f00-f6a6-11e9-80b9-07b4ad2bc7ac.png)

3.	lalu untuk menaruh file README.md yang tadi sudah di buat, dengan cara mengetik perintah git push -u origin master
 
![image](https://user-images.githubusercontent.com/56861575/67496211-44c0c980-f6a6-11e9-9db6-35dba51ed15b.png)

4.	jika berhasil akan seperti gambar di bawah, dan file README.md sudah berada di reposiory latihan 1 di Github.com yang tadi di buat
 
![image](https://user-images.githubusercontent.com/56861575/67496234-4c806e00-f6a6-11e9-9ed5-68c94538f41b.png)

