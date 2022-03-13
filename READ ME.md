<ol>
  <h3>Instalasi Windows Server 2022</h3>
  <li>Ketika file instalasi berhasil masuk, maka muncul untuk memilih bahasa untuk sistem</li>
  <img src="https://github.com/agisx/Web-Werver-On-Windows-Server/blob/main/assets/windows%20server/1.%20Pilih%20Bahasa%20Pada%20Sistem.PNG?raw=true" alt="">
  <li>Kemudian memilih tipe os yang disediakan, untuk datacenter pilihlah datacenter evaluation</li>
  <img src="https://github.com/agisx/Web-Werver-On-Windows-Server/blob/main/assets/windows%20server/2.%20Pilih%20OS%20yang%20Tersedia.PNG?raw=true" alt="">
  <li>Setting disk dengan klik New kemudian atur ukuran penyimpanan, lalu klik Apply</li>
  <img src="https://github.com/agisx/Web-Werver-On-Windows-Server/blob/main/assets/windows%20server/3.1%20Atur%20Penyimpanan.PNG?raw=true" alt="">
  <img src="https://github.com/agisx/Web-Werver-On-Windows-Server/blob/main/assets/windows%20server/3.2%20Contoh%20Pengatuan%20Penyimpanan.PNG?raw=true" alt="">
  <li>Tunggu instalasi selesai</li>
  <img src="https://github.com/agisx/Web-Werver-On-Windows-Server/blob/main/assets/windows%20server/4.%20Menunggu%20Instalasi%20Windows%20Server%20Selesai.PNG?raw=true" alt="">
  <li>Sesudah selesai akan diminta untuk memasukkan kata sandi sebagai Administrator, kata sandi harus kuat</li>
  <img src="https://github.com/agisx/Web-Werver-On-Windows-Server/blob/main/assets/windows%20server/5.%20Set%20Password.PNG?raw=true" alt="">
  <li>Ketika berhasil, klik ctrl+alt+del untuk unlock Di Virtual box, dapat melakukan cara ini</li>
  <img src="https://github.com/agisx/Web-Werver-On-Windows-Server/blob/main/assets/windows%20server/6.%20Unlock%20dan%20Masukkan%20Kata%20Sandi.png?raw=true" alt="">
  <li>Setelah selesai unlock dan memasukkan kata sandi Windows server siap digunakan</li>
  <img src="https://github.com/agisx/Web-Werver-On-Windows-Server/blob/main/assets/windows%20server/7.%20Windows%20Server%20Telah%20Terinstall.PNG?raw=true" alt="">
</ol>

<ol>
  <h3>Add Roles and Features</h3>
  <li>Klik bar manage, kemudian klik Add Roles Features</li>
  <img src="https://github.com/agisx/Web-Werver-On-Windows-Server/blob/main/assets/setting%20server/Add%20roles%20and%20features/1.%20Masuk%20Setting%20Start%20Lokal%20Server.png?raw=true" alt="">
  <li>Ip harus bersifat static, password kuat, dan memiliki security terbaru dari windows</li>
  <img src="https://github.com/agisx/Web-Werver-On-Windows-Server/blob/main/assets/setting%20server/Add%20roles%20and%20features/2.%20Rules%20Server%20Pada%20Umumnya.PNG?raw=true" alt="">
  <li>Lalu tentukan server yang berjalan, apakah difisik komputer itu sendiri atau bersifat virtual</li>
  <img src="https://github.com/agisx/Web-Werver-On-Windows-Server/blob/main/assets/setting%20server/Add%20roles%20and%20features/3.%20Pilih%20Role%20based.PNG?raw=true" alt="">
  <li>Setelah itu memilih destination server untuk tempat memasang roles and features</li>
  <img src="https://github.com/agisx/Web-Werver-On-Windows-Server/blob/main/assets/setting%20server/Add%20roles%20and%20features/4.%20Server%20Selection.PNG?raw=true" alt="">
  <li>Kemudian pilih roles dengan menyentangnya</li>
  <li>Jika telah selesai dinext maka akan muncul features yang ada</li>
  <li>Jika roles yang dicentang memiliki pengaturan lanjutan maka akan muncul menu lagi untuk konfigurasi </li>
  <li>Klik install untuk konfirmasi</li>
  <img src="https://github.com/agisx/Web-Werver-On-Windows-Server/blob/main/assets/setting%20server/Add%20roles%20and%20features/5.%20Install.PNG?raw=true" alt="">
  <li>Restart jika dibutuhkan</li>
  <li>Untuk menjalankan segala tool masuk bar Tools</li>
  <img src="https://github.com/agisx/Web-Werver-On-Windows-Server/blob/main/assets/setting%20server/Add%20roles%20and%20features/1.1%20Tools.png?raw=true" alt="">
</ol> 
<q>Cara ini digunakan selama ingin menambahkan Roles dan Features pada windows server</q>
 
<ol>
  <h3>.Net</h3>
  <li>Masuk Add Roles and features</li>
  <li>Centang Net ketika dimenu Features</li>
  <img src="https://github.com/agisx/Web-Werver-On-Windows-Server/blob/main/assets/setting%20server/NET/1.%20Pilih%20NET.PNG?raw=true" alt="">
  <li>Install</li>
</ol>
 
<ol>
  <h3>DNS Server</h3>
  <li>Masuk Add Roles and features</li>
  <li>Centang DNS server ketika dimenu Roles lalu install</li>
  <img src="https://github.com/agisx/Web-Werver-On-Windows-Server/blob/main/assets/setting%20server/DNS%20Server/1.%20Pilih%20DNS%20erver.PNG?raw=true" alt="">
  <li>Warning akan muncul ketika ip masih DHCP, rubah ip ke statik setelah pemasangan selesai dapat dilakukan</li>
  <img src="https://github.com/agisx/Web-Werver-On-Windows-Server/blob/main/assets/setting%20server/DNS%20Server/1.1%20Jika%20ip%20tidak%20static%20maka%20muncul%20seperti%20ini.PNG?raw=true" alt="">
  <li>Ketika merubah ip ke statik, jika perlu, matikan ipv6</li>
</ol> 

<ol>
  <h3>Active Directory Tools</h3>
  <li>Masuk Add Roles and features</li>
  <li>Centang Active Directory Tools ketika dimenu Roles lalu install</li>
  <img src="https://github.com/agisx/Web-Werver-On-Windows-Server/blob/main/assets/setting%20server/Active%20Directory%20Tools/0.%20Pilih%20Active%20Directory%20Domain%20Services.PNG?raw=true" alt="">
  <li>Masuk menu tools lalu pilih Active Directory Tools</li>
  <li><ol type='a'>
    <li>Pilih Add a new forest ketika ingin memberi domain ke server</li>
    <img src="https://github.com/agisx/Web-Werver-On-Windows-Server/blob/main/assets/setting%20server/Active%20Directory%20Tools/1.%20Pilih%20Add%20Forest.PNG?raw=true" alt="">
    <li>Contoh vm.local</li> 
  </ol></li>
  <li>Masukkan Password</li>
  <img src="https://github.com/agisx/Web-Werver-On-Windows-Server/blob/main/assets/setting%20server/Active%20Directory%20Tools/2.%20Masukkan%20password.PNG?raw=true" alt="">
  <li>Kemudian next hingga proses instalasi jika ingin default</li> 
  <img src="https://github.com/agisx/Web-Werver-On-Windows-Server/blob/main/assets/setting%20server/Active%20Directory%20Tools/3.%20Install.PNG?raw=true" alt="">
  <li>Masuk menu tools dan pilih DNS untuk masuk DNS management</li> 
  <li>Klik kanan bagian Reverse Lookup zone, pilih add zone</li>
  <img src="https://github.com/agisx/Web-Werver-On-Windows-Server/blob/main/assets/setting%20server/Active%20Directory%20Tools/4.1%20Add%20Zone.PNG?raw=true" alt="">
  <li>Masukkan network ID lalu next hingga pemasangan</li>
  <img src="https://github.com/agisx/Web-Werver-On-Windows-Server/blob/main/assets/setting%20server/Active%20Directory%20Tools/4.2%20Add%20zone%20Reverse%20Lookup%20in%20Vm.local.png?raw=true" alt="">
</ol>

<ol>
  <h3>IIS</h3>
  <li>Masuk Add Roles and features</li>
  <li>Centang IIS ketika dimenu Roles lalu install</li>
  <img src="https://github.com/agisx/Web-Werver-On-Windows-Server/blob/main/assets/setting%20server/Web%20Server%20IIS/1.%20Install.PNG?raw=true" alt="">
  <li>Didalam menu IIS, centang sesuai kebutuhan</li>
  <li>Domain vm.local telah berjalan</li>
  <li>Cek vm.local default page</li>
  <img src="https://github.com/agisx/Web-Werver-On-Windows-Server/blob/main/assets/setting%20server/Web%20Server%20IIS/3.%20Check%20VM%20vm.local.png?raw=true" alt="">
  <li>Custom diweb, dengan memberi index.html dan sumber daya website lainnya</li>
  <img src="https://github.com/agisx/Web-Werver-On-Windows-Server/blob/main/assets/setting%20server/Web%20Server%20IIS/4.%20Create%20a%20index%20file.PNG?raw=true" alt="">
  <li>Cek vm.local custom</li>
  <img src="https://github.com/agisx/Web-Werver-On-Windows-Server/blob/main/assets/setting%20server/Web%20Server%20IIS/5.%20Ceck%20on%20Windows's%20Browser.PNG?raw=true" alt="">
</ol>

<ol>
  <h3>Setting di Windows Jika Server Berjalan di VM</h3>
  <li>Masuk notepad dengan administrator</li>
  <li>Buka host file di c:\Windows\System32\Drivers\etc\hosts</li>
  <li>Tambahkan ip dan domain</li>
  <img src="https://github.com/agisx/Web-Werver-On-Windows-Server/blob/main/assets/setting%20server/Web%20Server%20IIS/2.%20Edit%20host%20file.PNG?raw=true" alt="">
</ol>
