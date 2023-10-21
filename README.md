<!DOCTYPE html>
<html>
  <head>
    <title>W3.CSS Template</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Montserrat">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <style>
    body, h1,h2,h3,h4,h5,h6 {font-family: "Montserrat", sans-serif}
    .w3-row-padding img {margin-bottom: 12px}
    .bgimg {
      background-position: center;
      background-repeat: no-repeat;
      background-size: cover;
      background-image: url('https://png.pngtree.com/background/20211215/original/pngtree-indonesian-batik-parang-picture-image_1455668.jpg');
      min-height: 100%;
    }
    </style>
  </head>
<body>

<!-- Sidebar with image -->
<nav class="w3-sidebar w3-hide-medium w3-hide-small" style="width:40%">
  <div class="bgimg"></div>
</nav>

<!-- Hidden Sidebar (reveals when clicked on menu icon)-->
<nav class="w3-sidebar w3-brown w3-animate-right w3-xxlarge" style="display:none;padding-top:150px;right:0;z-index:2" id="mySidebar">
  <a href="javascript:void(0)" onclick="closeNav()" class="w3-button w3-brown w3-xxxlarge w3-display-topright" style="padding:0 12px;">
    <i class="fa fa-remove"></i>
  </a>
  <div class="w3-bar-block w3-center">
    <a href="#" class="w3-bar-item w3-button w3-text-white w3-hover-black" onclick="closeNav()">Home</a>
    <a href="#motifbatik" class="w3-bar-item w3-button w3-text-white w3-hover-black" onclick="closeNav()">Motif Batik</a>
    <a href="#unsurmatematika" class="w3-bar-item w3-button w3-text-white w3-hover-black" onclick="closeNav()">Unsur Matematika</a>
    <a href="#kuis" class="w3-bar-item w3-button w3-text-white w3-hover-black" onclick="closeNav()">Kuis</a>
  </div>
</nav>

<!-- Page Content -->
<div class="w3-main w3-padding-large" style="margin-left:40%">

  <!-- Menu icon to open sidebar -->
  <span class="w3-button w3-top w3-white w3-xxlarge w3-text-grey w3-hover-text-black" style="width:auto;right:0;" onclick="openNav()"><i class="fa fa-bars"></i></span>

  <!-- Header -->
  <header class="w3-container w3-center" style="padding:128px 16px" id="home">
    <h1 class="w3-jumbo"><font color="#7B3F00">Matebatika</font></h1>
    <h3><font color="#834333">Etnomatematika pada Batik Yogyakarta.</font></h3>
    <img src="https://png.pngtree.com/background/20211215/original/pngtree-indonesian-batik-parang-picture-image_1455668.jpg" class="w3-image w3-hide-large w3-hide-small w3-round" style="display:block;width:60%;margin:auto;">
    <img src="https://png.pngtree.com/background/20211215/original/pngtree-indonesian-batik-parang-picture-image_1455668.jpg" class="w3-image w3-hide-large w3-hide-medium w3-round" width="1000" height="1333">
  </header>

  <!-- Portfolio Section -->
  <div class="w3-padding-32 w3-content" id="motifbatik">
    <h2 class="w3-text-black">Motif Batik</h2>
    <hr class="w3-opacity">
    <p>Yogyakarta memiliki banyak kebudayaan, salah satunya adalah batik. Motif Batik Yogyakarta memiliki beberapa ciri khas, anatara lain:
      1) warna yang cenderung gelap, 2) setiap warna memiliki makna filosofis masing-masing, 3) pola motif umumnya 
      geometris dan non-geometris, 4) terdapat seret dipinggiran kain.  Batik Yogyakarta memiliki motif yang
      sangat beragam, dua diantaranya adalah Motif Batik Ceplok dan Motif Batik Parang.
    </p>

    <!-- Grid for photos -->
    <div class="w3-row-padding" style="margin:0 -16px">
      <div class="w3-half">
        <h3 class="w3-padding-16">A. Motif Ceplok</h3>
        <img src="https://i.pinimg.com/564x/52/d2/a0/52d2a0d0d53b71199870ad182bbdac8e.jpg" style="width:100%">
        <img src="https://i.pinimg.com/564x/10/9b/47/109b473d7bca663a78bad023e172f88a.jpg" style="width:100%">
      </div>

      <div class="w3-half">
        <h3 class="w3-padding-16">B. Motif Parang</h3>
          <img src="https://i.pinimg.com/564x/86/4c/fa/864cfaee1e681500936ab9ce7c8d73e2.jpg" style="width:100%">
          <img src="https://i.pinimg.com/564x/49/c7/0e/49c70e97ed0f99f7f30661cd046d86da.jpg" style="width:100%">
          <img src="https://i.pinimg.com/564x/e4/b9/b5/e4b9b594caa3b8929fc24c9bca9ec31b.jpg" style="width:100%">
        
      </div>
    <!-- End photo grid -->
    </div>
  <!-- End Portfolio Section -->
  </div>

  <!-- About Section -->
  <div class="w3-content w3-justify w3-text-black w3-padding-32" id="unsurmatematika">
    <h2>Unsur Matematika</h2>
    <hr class="w3-opacity">
    <p>Pada motif batik Yogyakarta terdapat beberapa unsur dan konsep Matematika yang dapat kita pelajari.
      Salah satu dari konsep Matematika tersebut adalah konsep mengenai transfomrasi geometri, yaitu translasi,
      refleksi, rotasi, dan dilatasi.</p>
    <h3 class="w3-padding-16">Translasi</h3>
    <p> Berikut adalah contoh translasi pada batik motif Parang khas Yogyakarta.</p>
    <p>Keterangan:</p>
    <p>- A: Obyek asli</p>
    <p>- A': Obyek hasil translasi</p>
    <p>- v: vektor translasi</p>
    <iframe scrolling="no" title="Translasi" src="https://www.geogebra.org/material/iframe/id/m94papaa/width/698/height/500/border/888888/sfsb/true/smb/false/stb/false/stbh/false/ai/false/asb/false/sri/false/rc/false/ld/false/sdz/false/ctl/false" width="698px" height="500px" style="border:0px;"> </iframe>
    <p>Untuk lebih memahami mengenai konsep translasi, Anda dapat mengerjakan aktivitas berikut!</p>
    <a href="https://www.geogebra.org/m/m94papaa", target="_blank"><strong>Aktivitas 1: Translasi</strong></a>

    <h3 class="w3-padding-16">Rotasi</h3>
    <p>Di bawah ini adalah contoh rotasi yang terdapat pada batik motif Ceplok khas Yogyakarta. Pada contoh di
      bawah obyek asli (c) dirotasi dengan titik rotasi adalah titik berwarna biru dengan sudut rotasi &alpha;. 
      Anda bisa melihat perubahan hasil rotasinya dengan menggerakan <em> slider</em> yang tersedia.
    </p>
    <iframe scrolling="no" title="Rotasi" src="https://www.geogebra.org/material/iframe/id/vnwu2gau/width/698/height/500/border/888888/sfsb/true/smb/false/stb/false/stbh/false/ai/false/asb/false/sri/false/rc/false/ld/false/sdz/false/ctl/false" width="698px" height="500px" style="border:0px;"> </iframe>
    <p>Untuk lebih memahami mengenai konsep rotasi, Anda dapat mengerjakan aktivitas berikut!</p>
    <a href="https://www.geogebra.org/m/vnwu2gau", target="_blank"><strong>Aktivitas 2: Rotasi</strong></a>
    
    <h3 class="w3-padding-16">Refleksi</h3>
    <p>Berikut adalah contoh pencerminan atau refleksi pada batik motif Parang khas Yogyakarta. Pada contoh ini 
      obyek asli, yaitu p, dicerminkan terhadap garis <em>g</em> dan menghasilkan bayangan yaitu p'.
    </p>
    <iframe scrolling="no" title="Refleksi" src="https://www.geogebra.org/material/iframe/id/b3zfpegx/width/698/height/500/border/888888/sfsb/true/smb/false/stb/false/stbh/false/ai/false/asb/false/sri/false/rc/false/ld/false/sdz/false/ctl/false" width="698px" height="500px" style="border:0px;"> </iframe>
    <p>Untuk lebih memahami mengenai konsep refleksi, Anda dapat mengerjakan aktivitas berikut!</p>
    <a href="https://www.geogebra.org/m/b3zfpegx", target="_blank"><strong>Aktivitas 3: Refleksi</strong></a>

    <h3 class="w3-padding-16">Dilatasi</h3>
    <p>Di bawah ini adalah contoh dilatasi yang terdapat pada batik motif Ceplok khas Yogyakarta. Pada contoh di
      di bawah obyek asli, yaitu q, dilitasikan dengan pusat dilatasi adalah titik C dan faktor dilatasinya adalah k, dimana k adalah suatu
      bilangan. Hasil dilatasinya adalah obyek q'.
    </p>
    <iframe scrolling="no" title="Dilatasi" src="https://www.geogebra.org/material/iframe/id/qsjpduhd/width/698/height/500/border/888888/sfsb/true/smb/false/stb/false/stbh/false/ai/false/asb/false/sri/false/rc/false/ld/false/sdz/false/ctl/false" width="698px" height="500px" style="border:0px;"> </iframe>
    <p>Untuk lebih memahami mengenai konsep dilatasi, Anda dapat mengerjakan aktivitas berikut!</p>
    <a href="https://www.geogebra.org/m/qsjpduhd", target="_blank"><strong>Aktivitas 4: Dilatasi</strong></a>

  <!-- End About Section -->
  </div>

  <!-- Contact Section -->
  <div class="w3-padding-32 w3-content w3-text-black" id="kuis" style="margin-bottom:64px">
    <h2>Kuis</h2>
    <p>Setelah kamu mengikuti semua aktivitas di atas kamu dapat mengerjakan kuis berikut ini untuk menguji pemahamanmu!</p>
    <div style="width:100%;display:flex;flex-direction:column;gap:8px;min-height:635px;"><iframe src="https://quizizz.com/embed/quiz/5e840c915a52fe001e430579" title=" - Quizizz" style="flex:1;" frameBorder="0" allowfullscreen></iframe><a href="https://quizizz.com/admin?source=embedFrame" target="_blank">Explore more at Quizizz.</a></div>
    <hr class="w3-opacity">

  <!-- End Contact Section -->
  </div>  
  
  <!-- Footer. This section contains an ad for W3Schools Spaces. You can leave it to support us. -->
  <footer class="w3-container w3-padding-64 w3-light-grey w3-center w3-opacity w3-xlarge" style="margin:-24px">
    <i class="fa fa-facebook-official w3-hover-opacity"></i>
    <i class="fa fa-instagram w3-hover-opacity"></i>
    <i class="fa fa-snapchat w3-hover-opacity"></i>
    <i class="fa fa-pinterest-p w3-hover-opacity"></i>
    <i class="fa fa-twitter w3-hover-opacity"></i>
    <i class="fa fa-linkedin w3-hover-opacity"></i>
    <p class="w3-small">This website was made with W3schools Spaces. Make your own free website today!</p>
    <a class="w3-button w3-round-xxlarge w3-small w3-dark-grey" href="https://www.w3schools.com/spaces" target="_blank">Start now</a>  
    <!-- End footer -->
  </footer>
<!-- END PAGE CONTENT -->
</div>

<script>
// Open and close sidebar
function openNav() {
  document.getElementById("mySidebar").style.width = "60%";
  document.getElementById("mySidebar").style.display = "block";
}

function closeNav() {
  document.getElementById("mySidebar").style.display = "none";
}
</script>

</body>
</html>
