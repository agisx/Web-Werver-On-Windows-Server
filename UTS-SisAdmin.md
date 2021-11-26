
<h1>Web Server IIS Menggunakan Windows Server 2022</h1>
<ol>
  <h3>Instalasi Windows Server 2022</h3>
  <li>Ketika file instalasi berhasil masuk, maka muncul untuk memilih bahasa untuk sistem</li>
  <li>Kemudian memilih tipe os yang disediakan, untuk datacenter pilihlah datacenter evaluation</li>
  <li>Setting disk dengan klik New kemudian atur ukuran penyimpanan, lalu klik Apply</li>
  <li>Tunggu instalasi selesai</li>
  <li>Sesudah selesai akan diminta untuk memasukkan kata sandi sebagai Administrator, kata sandi harus kuat</li>
  <li>Ketika berhasil, klik ctrl+alt+del untuk unlock Di Virtual box, dapat melakukan cara ini</li>
  <li>Setelah selesai unlock dan memasukkan kata sandi Windows server siap digunakan</li> 
</ol>

<ol>
  <h3>Add Roles and Features</h3>
  <li>Klik bar manage, kemudian klik Add Roles Features</li>
  <li>Ip harus bersifat static, password kuat, dan memiliki security terbaru dari windows</li>
  <li>Lalu tentukan server yang berjalan, apakah difisik itu sendiri atau bersifat virtual</li>
  <li>Setelah itu memilih server itu sendiri Apakah dalam virtual hard disk atau dalam server itu sendiri</li>
  <li>Kemudian pilih roles dengan menyentangnya</li>
  <li>Jika telah dinext maka akan muncul features yang ada</li>
  <li>Jika roles yang dicentang memiliki pengaturan lanjutan maka akan muncul menu lagi untuk konfigurasi </li>
  <li>Klik install untuk konfirmasi</li>
  <li>Restart jika dibutuhkan</li>
  <li>Untuk menjalankan segala tool masuk bar Tools</li>
</ol> 
<q>Cara ini digunakan selama ingin menambahkan Roles dan Features pada windows server</q>
 
<ol>
  <h3>.Net</h3>
  <li>Masuk Add Roles and features</li>
  <li>Centang Net ketika dimenu Features</li>
  <li>Install</li>
</ol>
 
<ol>
  <h3>DNS Server</h3>
  <li>Masuk Add Roles and features</li>
  <li>Centang DNS server ketika dimenu Roles lalu install</li>
  <li>Warning akan muncul ketika ip masih DHCP, rubah ip ke statik setelah pemasangan selesai dapat dilakukan</li>
  <li>Jika perlu, matikan ipv6</li>
</ol> 

<ol>
  <h3>Active Directory Tools</h3>
  <li>Masuk Add Roles and features</li>
  <li>Centang Active Directory Tools ketika dimenu Roles lalu install</li>
  <li>Masuk menu tools lalu pilih Active Directory Tools</li>
  <li><ol type='a'>
    <li>Pilih Add a new forest ketika ingin memberi domain ke server</li>
    <li>Contoh vm.local</li> 
  </ol></li>
  <li>Masukkan Password</li>
  <li>Kemudian next hingga proses instalasi jika ingin default</li> 
  <li>Masuk menu tools dan pilih DNS untuk masuk DNS management</li>
  <li>Klik kanan bagian Reverse Lookup zone, pilih add zone</li>
  <li>Masukkan network ID lalu next hingga pemasangan</li>
</ol>

<ol>
  <h3>IIS</h3>
  <li>Masuk Add Roles and features</li>
  <li>Centang IIS ketika dimenu Roles lalu install</li>
  <li>Didalam menu IIS, centang sesuai kebutuhan</li>
  <li>Domain vm.local telah berjalan</li>
  <li>Cek vm.local default page</li>
  <li>Custom diweb, dengan memberi index.html dan sumber daya website lainnya</li>
  <li>Cek vm.local custom</li>
</ol>

<ol>
  <h3>Setting di Windows Jika Server Berjalan di VM</h3>
  <li>Masuk notepad dengan administrator</li>
  <li>Buka host file di c:\Windows\System32\Drivers\etc\hosts</li>
  <li>Tambahkan ip dan domain</li>
</ol>
