# Tugas1-web
Tugas pemograman web dasar ke-1


<!DOCTYPE html>
<html>
<head>
        
        <title>Tugas Topic 1 by Omar</title>	
        <link rel ="icon" href="assets/img/icon.png">
        <font face="iosevka Nerd font" color="#e7e8eb">	
        <style>
            body{			background-image: url("assets/img/wp.jpg");		
									}		
								h1{			
													width: 940px;			
													height: 40px;			
													margin-left: : 30px;		
									}		
								nav{			
													margin-bottom: 50px;		
									}		
								aside, nav li{			
																								display: inline;			
																								margin-right: 40px;		
									}						
								nav li a, a{			
																								color: #e7e8eb;			
																								text-decoration: none;		
									}	
								aside{			
																float: right;		
									}		
								img{			
																margin-left: 30px;		
																margin-right: 20px;		
									}
							</style>
</head>
<body>
    <header>		
        <table>			
            <thead>				
                <th><img src="assets/img/logo.png" width="50" height="50"></th>				
                <th><h1 align="left"> Masochist Desktoper </h1></th>			
            </thead>		
    </table>
        <nav>			
            <ul>			
                <h3> ~ How to modding your linux desktop ~ </h3>				
                <li><a href=""> Home </a></li>				
                <li><a href=""> Tutorial </a></li>				
                <li><a href=""> Dotfiles </a></li>				
                <li><a href=""> Help </a></li>				
                <li><a href=""> About </a></li>			
                <input class="form-control mr-sm-2" placeholder="Type Something...." type="text" list="programming">					
                <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>				
                </input>			
            </ul>		
        </nav>
    </header>
    <section>		
        <article><!--			
            <figure>				
            <img src="assets/img/de.png" width="390" height="240">				
            <hgroup>					
                <h2>Desktop Environment (DE)</h2>					
                <h3>Kenali Desktop Environment yang anda gunakan</h3>				
            </hgroup>				
            <p>					
                OS Ubuntu pada umumnya menggunakan Unity sebagai Desktop Environment dan juga menggunakan compiz sebagai Window Manager.<br>					
                Pada Elementary OS, DE yang digunakan adalah Pantheon.				
            </p>			
        </figure>-->
        <table>				
            <thead>				
                <th>						
                    <img src="assets/img/de.png" width="300" height="200">					
                </th>					
                <th>						
                    <hgroup>							
                        <h2 align="left">Desktop Environment (DE)</h2>							
                        <h3 align="left">Kenali Desktop Environment yang anda gunakan</h3>					
                    </hgroup>						
                    <p align="left">						
                        OS Ubuntu pada umumnya menggunakan Unity sebagai Desktop Environment.<br>						
                        Pada Elementary OS, DE yang digunakan adalah Pantheon.<br><br>							
                        <a href="">Lihat Selengkapnya...</a>						
                    </p>					
                </th>				
            </thead>
            <aside>					
                <section>						
                    <h3> Social Media </h3>							
                    <a href="https://github.com/fikriomar16"> > Github</a><br><br>						
                    <a href="https://plus.google.com/+FikriOmar"> > Google+</a><br><br>							
                    <a href="https://fikriomar16.deviantart.com"> > DeviantArt</a><br><br>					
                </section>				
            </aside>				
            <table>				
                <thead>					
                    <th>						
                        <img src="assets/img/wm.png" width="300" height="200">					
                    </th>					
                    <th>						
                        <hgroup>							
                            <h2 align="left">Window Manager (WM)</h2>							
                            <h3 align="left">Apakahkah WM itu?</h3>						
                        </hgroup>						
                        <p align="left">							
                            Window Manager bertugas menyediakan 'Window' bagi aplikasi yang di jalankan. <br>							
                            'Window' yang dimaksud disini adalah exterior dari aplikasi yang dapat berupa border, <br>						
                            title bar, system menu, dan behavior-nya.<br><br>							
                            <a href="">Lihat Selengkapnya...</a>						 
                        </p>					
                    </th>				
                </thead>			
            </table>		
        </article>	
    </section>
    <footer>	
        <address>			
            <center><p><a href="https://github.com/fikriomar16" title="">@Fikri Omar</a></p></center>		
        </address>	
    </footer>
</body>
    </html>
    
Penjelasan :
» Pertama html ini diberikan judul "Topic 1 by omar".
» Kemudian ada tag link dengan atribut rel dan value icon serta atribut href.
» Selanjutnya menentukan format huruf dan warna dengan tag font serta value face untuk jenis huruf dan color untuk warna.
» Tag style untuk membuat informasi style untuk dokumen yang tedapat di dalamnya format width, height, margin, color, dll. untuk tampilan halaman web
» Bagian kedua yaitu membuat judul pada halaman web, dengan menggunakan tag header, lalu membuat tabel yang isinya mencakup tag thead untuk mengelompokan isi header dalam sebuah tabel, kemudian tag th yang diisi dengan gambar lengkap dengan formatnya.
  Tag th kedua diisi dengan h1 atau heading untuk judul besar dengan value align. Kemudian ditutup oleh tag thead dan tag table.
» Selanjutnya disambung dengan tag nav, kemudian tag ul yang berarti membuat list/daftar selain nomor.
» Dilanjutkan dengan tag h3/ heading 3 yang kemudian disambung dengan tag untuk item list (home, tutorials, dotfiles, help, dan about)
» Setelah itu tag input untuk membuat sebuah control input dan tag button, Tag untuk membuat sebuah tombol yang dapat diklik.
» Pada baris selanjutnya setelah tag penutup, terdapat tag section Tag untuk membuat bagian dalam dokumen dan tag artikel tentunya untuk membuat artikel.
» Terdapat tanda (</!--...-->), dimana ini adalah komentar yang didalamnya terdapat tag figure yakni tag untuk membuat konten mandiri, tag img untuk memasukan gambar didalamnya.
  Kemudian tag hgroup untuk pengelompokan elemen heading dan tag p untuk membuat paragraf disambung dengan tag penutup.
» Setelah komentar selanjutnya terdapat tag table lagi yang diikuti dengan tag thead dan tag th yang berisi gambar.
» Kemudian masih menggunakan tag th kali ini isinya adalah tag hgroup (h2 & h3) lalu tag p yang membuat paragraf ditambah dengan tag a yakni untuk membuat hyperlink dengan value href(menentukan lokasi file)
» Selanjutnya ada tag aside yakni Tag untuk membuat konten lain selain dari konten halaman, disambung tag section untuk membuat bagian dalam konten.
» Tag h3 digunakan untuk judul(sosial media), kemudian ada tag a dengan value href untuk hyperlink ke media sosial lainnya, setelah itu tag penutup.
» Sama seperti sebelumnya, sebelum konten sosial media, terdapat format yang sama dengan bagian akhir ini yakni dari elemennya. Dimana yang sebelumnya itu memuat elemen tentang desktop environment sementara bagian akhir memuat elemen tentang Window Manager.
» Terakhir adalah tag penutup. 
