<!DOCTYPE html>
<html lang="en-US">
  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">

<!-- Begin Jekyll SEO tag v2.8.0 -->
<title>peta | maps</title>
<meta name="generator" content="Jekyll v3.9.5" />
<meta property="og:title" content="peta" />
<meta property="og:locale" content="en_US" />
<meta name="description" content="maps" />
<meta property="og:description" content="maps" />
<link rel="canonical" href="https://vitalokaken.github.io/peta/" />
<meta property="og:url" content="https://vitalokaken.github.io/peta/" />
<meta property="og:site_name" content="peta" />
<meta property="og:type" content="website" />
<meta name="twitter:card" content="summary" />
<meta property="twitter:title" content="peta" />
<script type="application/ld+json">
{"@context":"https://schema.org","@type":"WebSite","description":"maps","headline":"peta","name":"peta","url":"https://vitalokaken.github.io/peta/"}</script>
<!-- End Jekyll SEO tag -->

    <link rel="stylesheet" href="/peta/assets/css/style.css?v=fad57c4063c55c787b127a7d021d7ca5fca5825a">
    <!-- start custom head snippets, customize with your own _includes/head-custom.html file -->

<!-- Setup Google Analytics -->



<!-- You can set your favicon here -->
<!-- link rel="shortcut icon" type="image/x-icon" href="/peta/favicon.ico" -->

<!-- end custom head snippets -->

  </head>
  <body>
    <div class="container-lg px-3 my-5 markdown-body">
      
      <h1><a href="https://vitalokaken.github.io/peta/">peta</a></h1>
      

      <html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>KJPP Hari Utomo dan Rekan</title>
  <link rel="stylesheet" href="https://diy.magis.unwahas.ac.id/AdminLTE/plugins/fontawesome-free/css/all.min.css" />
  <link href="https://diy.magis.unwahas.ac.id/css/app.css" rel="stylesheet" />
  <link rel="stylesheet" href="https://unpkg.com/leaflet@1.7.1/dist/leaflet.css" integrity="sha512-xodZBNTC5n17Xt2atTPuE1HxjVMSvLVW9ocqUKLsCC5CXdbqCmblAshOMAS6/keqq/sMZMZ19scR4PsZChSR7A==" crossorigin="" />
  <script src="https://unpkg.com/leaflet@1.7.1/dist/leaflet.js" integrity="sha512-XQoYMqMTK8LvdxXYG3nZ448hOEQiglfqkJs1NOQV44cWnUrBc8PkAOcXy20w0vlaXaVUearIOBhiXZ5V3ynxwA==" crossorigin=""></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/3.5.1/chart.js"></script>
  <!-- jQuery -->
  <script src="https://diy.magis.unwahas.ac.id/AdminLTE/plugins/jquery/jquery.min.js"></script>
  <!-- Bootstrap 4 -->
  <script src="https://diy.magis.unwahas.ac.id/AdminLTE/plugins/bootstrap/js/bootstrap.bundle.min.js"></script>
  <!-- DataTables -->
  <script src="https://diy.magis.unwahas.ac.id/AdminLTE/plugins/datatables/jquery.dataTables.min.js"></script>
  <script src="https://diy.magis.unwahas.ac.id/AdminLTE/plugins/datatables-bs4/js/dataTables.bootstrap4.min.js"></script>
  <script src="https://diy.magis.unwahas.ac.id/AdminLTE/plugins/datatables-responsive/js/dataTables.responsive.min.js"></script>
  <script src="https://diy.magis.unwahas.ac.id/AdminLTE/plugins/datatables-responsive/js/responsive.bootstrap4.min.js"></script>
</head>

<style>
  body {
    font-family: 'Montserrat', 'sans-serif';
  }
</style>
    <div class="content-wrapper">
      <!-- Main content -->
      <div class="content">
<div class="row mx-5 mt-3">
   <div class="col">
    <a href="https://hariutomo.co.id/" class="btn" style="background-color: #84C2D8; border-radius: 10px">Kembali</a>
   </div>
</div>
<div class="row mt-3 mx-5">
  <div class="col-sm-6">
    <div class="card">

      <div class="card-body">
        <h3 class="card-title">
          Peta
        </h3>
        <hr />
        <div id="map" style="width: 100%; height: 550px;"></div>
      </div>
    </div>
  </div>
  <div class="col-sm-6">
    <div class="card">
      <!-- /.card-header -->
      <div class="card-body">
        <h3 class="card-title">
      Gambar
        </h3>
        <hr />
        <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
          <ol class="carousel-indicators">
           <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
          </ol>
          <div class="carousel-inner">
                        <div class="carousel-item active" data-bs-interval="2000">
				<img class="d-block w-100" src="WILKES 1.png" alt="First slide" />
            </div>
                      </div>
          <a class="carousel-control-prev" href="WILKES 2.png" role="button" data-slide="prev">
            <span class="carousel-control-custom-icon" aria-hidden="true">
              <i class="fas fa-chevron-left"></i>
            </span>
            <span class="sr-only">Previous</span>
          </a>
          <a class="carousel-control-next" href="WILKES 3.png" role="button" data-slide="next">
            <span class="carousel-control-custom-icon" aria-hidden="true">
              <i class="fas fa-chevron-right"></i>
            </span>
            <span class="sr-only">Next</span>
          </a>
        </div>
      </div>
     
    </div>
  </div>
</div>
<div class="row mt-3 mx-5">
  <div class="col-md-6 ">
    <div class="card">
      <div class="card-header">
        <h3 class="card-title">Detail Objek</h3>
      </div>
    <!-- /.card-header -->
      <div class="card-body">
        <table class="table table-bordered">
          <tbody>
			 <tr>
              <td> Lokasi  </td>
              <td>:</td>
              <td>Jalan Darmawangsa XII No.6 RT.007 RW.01, Kelurahan Pulo, Kecamatan Kebayoran Baru, Kota Jakarta Selatan, Provinsi DKI Jakarta.																																					
			</td>
            </tr>
			 <tr>
              <td>Basis Nilai</td>
              <td>: </td>
              <td>Nilai Pasar dan Indikasi Nilai Likuidasi</td>
            </tr>
			<tr>
              <td>Tanggal Inspeksi</td>
              <td>: </td>
              <td>26 Januari 2022</td>
            </tr>
			<tr>
              <td>Tanggal Penilaian</td>
              <td>: </td>
              <td>27 Januari 2022</td>
            </tr>
			<tr>
              <td>Tahun Penilaian</td>
              <td>: </td>
              <td> 2022 </td>
            </tr>
			<tr>
              <td>Titik Koordinat</td>
              <td>:</td>
              <td><a href="https://www.google.com/maps/place/6%C2%B015'25.8%22S+106%C2%B047'58.3%22E/@-6.2571477,106.7969431,17z/data=!3m1!4b1!4m4!3m3!8m2!3d-6.257153!4d106.799518?entry=ttu">
   -6.257153, 106.799518 												
                  </a></td>
            </tr>
			<tr>
              <th>Jenis Data</th>
              <th style="width: 10px">:</th>
              <th> Rumah Tinggal</th>
            </tr>
           <tr>
              <td>Luas Tanah Sertipikat</td>
              <td>:</td>
              <td> 626 m2</td>
            </tr>
			<tr>
              <td>Luas Bangunan</td>
              <td>:</td>
              <td> 621 m2</td>
            </tr>
			<tr>
              <td>Nilai Pnwrn/Transaksi</td>
              <td>:</td>
              <td> Rp. 31,023,187,000.-</td>
            </tr>
			<tr>
              <td>Indikasi Nilai Pasar Tanah/m2</td>
              <td>:</td>
              <td>  Rp. 45,170,000.-</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
    <!-- /.card -->

    <div class="card">
      <div class="card-header">
        <h3 class="card-title">DATA Pembanding 1</h3>
      </div>
	   <div class="card-body">
        <table class="table table-bordered">

          <tbody>
<tr>
              <td> Lokasi  </td>
              <td>:</td>
              <td> Jl. Darmawangsa XII No.128 </td>
            </tr>
			<tr>
              <td>Titik Koordinat</td>
              <td>:</td>
              <td><a href="https://www.google.com/maps/place/6%C2%B015'24.8%22S+106%C2%B047'56.2%22E/@-6.2568727,106.7963621,17z/data=!3m1!4b1!4m4!3m3!8m2!3d-6.256878!4d106.798937?entry=ttu">
 -6.256878, 106.798937 							
                  </a></td>
            </tr>
			<tr>
              <th>Jenis Data</th>
              <th style="width: 10px">:</th>
              <th> Rumah tinggal </th>
            </tr>
           <tr>
              <td>Nama Sumber Data</td>
              <td>:</td>
              <td>Agen properti</td>
            </tr>
			<tr>
              <td>No. Telp. Sumber Data </td>
              <td>: </td>
              <td>0821 21010755</td>
            </tr>
			<tr>
              <td>Luas Tanah Sertipikat</td>
              <td>:</td>
              <td>600 m2</td>
            </tr>
			<tr>
              <td>Luas Bangunan</td>
              <td>:</td>
              <td> 370 m2</td>
            </tr>
			<tr>
              <td>Nilai Pnwrn/Transaksi</td>
              <td>:</td>
              <td> Rp. 34,000,000,000.-</td>
            </tr>
			<tr>
              <td>Indikasi Nilai Pasar Tanah/m2</td>
              <td>:</td>
              <td> Rp. 46,128,000.-</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>
  <div class="col-md-6">
    <div class="card">
      <div class="card-header">
        <h3 class="card-title">DATA Pembanding 2</h3>
      </div>
      <!-- /.card-header -->
      <div class="card-body">
        <table class="table table-bordered">
          <tbody>
			<tr>
              <td> Lokasi  </td>
              <td>:</td>
              <td> Jl. Darmawangsa II No.9  	 	
	</td>
            </tr>
			<tr>
              <td>Titik Koordinat</td>
              <td>:</td>
              <td><a href="https://www.google.com/maps/place/6%C2%B015'20.2%22S+106%C2%B047'57.2%22E/@-6.2555917,106.7966451,17z/data=!3m1!4b1!4m4!3m3!8m2!3d-6.255597!4d106.79922?entry=ttu">
 -6.255597, 106.79922 				
                  </a></td>
            </tr>
			<tr>
              <th>Jenis Data</th>
              <th style="width: 10px">:</th>
              <th> Rumah tinggal </th>
            </tr>
			<tr>
              <td>Nama Sumber Data</td>
              <td>:</td>
              <td>Agen properti</td>
            </tr>
			<tr>
              <td>No. Telp. Sumber Data </td>
              <td>: </td>
              <td>0812 72712671</td>
            </tr>
			<tr>
              <td>Luas Tanah Sertipikat</td>
              <td>:</td>
              <td> 450 m2</td>
            </tr>
			<tr>
              <td>Luas Bangunan</td>
              <td>:</td>
              <td> 0 m2</td>
            </tr>
			<tr>
              <td>Nilai Pnwrn/Transaksi</td>
              <td>:</td>
              <td> Rp. 23,000,000,000.-</td>
            </tr>
			<tr>
              <td>Indikasi Nilai Pasar Tanah/m2</td>
              <td>:</td>
              <td> Rp. 43,444,000.-</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
    <!-- /.card -->
    <div class="card">
      <div class="card-header">
        <h3 class="card-title">DATA Pembanding 3</h3>
      </div>
      <!-- /.card-header -->
      <div class="card-body">
        <table class="table table-bordered">
         <tbody>
			<tr>
              <td> Lokasi  </td>
              <td>:</td>
              <td> Jl. Darmawangsa II.B No.2 		
	</td>
            </tr>
			<tr>
              <td>Titik Koordinat</td>
              <td>:</td>
              <td><a href="https://www.google.com/maps/place/6%C2%B015'18.3%22S+106%C2%B047'59.3%22E/@-6.2550877,106.7972251,17z/data=!3m1!4b1!4m4!3m3!8m2!3d-6.255093!4d106.7998?entry=ttu">
  -6.255093, 106.799800 	
                  </a></td>
            </tr>
			<tr>
              <th>Jenis Data</th>
              <th style="width: 10px">:</th>
              <th> Rumah tinggal </th>
            </tr>
           <tr>
              <td>Nama Sumber Data</td>
              <td>:</td>
              <td>Agen properti</td>
            </tr>
			<tr>
              <td>No. Telp. Sumber Data </td>
              <td>: </td>
              <td>0811 3001175</td>
            </tr>
			<tr>
              <td>Luas Tanah Sertipikat</td>
              <td>:</td>
              <td> 401 m2</td>
            </tr>
			<tr>
              <td>Luas Bangunan</td>
              <td>:</td>
              <td> 700 m2</td>
            </tr>
			<tr>
              <td>Nilai Pnwrn/Transaksi</td>
              <td>:</td>
              <td> Rp. 28,000,000,000.-</td>
            </tr>
			<tr>
              <td>Indikasi Nilai Pasar Tanah/m2</td>
              <td>:</td>
              <td> Rp. 48,320,000.-</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
        
      </div>
 
  

<script>
  var peta1 = L.tileLayer('https://api.mapbox.com/styles/v1/{id}/tiles/{z}/{x}/{y}?access_token=pk.eyJ1IjoibWFwYm94IiwiYSI6ImNpejY4NXVycTA2emYycXBndHRqcmZ3N3gifQ.rJcFIG214AriISLbB6B5aw', {
            attribution: 'Map data &copy; <a href="https://www.openstreetmap.org/">OpenStreetMap</a> contributors, ' +
                '<a href="https://creativecommons.org/licenses/by-sa/2.0/">CC-BY-SA</a>, ' +
                'Imagery © <a href="https://www.mapbox.com/">Mapbox</a>',
            id: 'mapbox/streets-v11'
        });
    
    
        var map = L.map('map', {
            center: [-7.9409693,110.5509868],
            zoom: 14,
            layers: [peta1],
        });
    
        var baseMaps = {
            "Grayscale": peta1,
           
        };
    
        L.control.layers(baseMaps).addTo(map);



        var iconsekolah = L.icon({
            iconUrl: 'OBJEK WILKES.png',
            iconSize:     [300, 300],        
        });

		var informasi = '<table class="table table-bordered"> <tr><td colspan="2"><a href="https://www.google.com/maps/dir//-7.9409693,110.5509868" class="btn btn-sm btn-default">Rute</a></td></tr></body></table>';
         L.marker([-7.9409693,110.5509868],{icon: iconsekolah})
        // .bindPopup(L.popup({maxWidth:500}).setContent('<a href="https://www.google.com/maps/dir//-7.9409693,110.5509868" target="_blank">Rute Ke Lokasi</a>'))
		 .addTo(map);
</script>



</div></div></div></html>


      
    </div>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/anchor-js/4.1.0/anchor.min.js" integrity="sha256-lZaRhKri35AyJSypXXs4o6OPFTbTmUoltBbDCbdzegg=" crossorigin="anonymous"></script>
    <script>anchors.add();</script>
  </body>
</html>
