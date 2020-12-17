<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">

    <link rel="stylesheet" href="style.css">

    <title>Pantau Penyebaran Covid-19</title>
  </head>
    <body>
    <!--navbar-->
    <nav class="navbar navbar-light bg-light justify-content-between">
      <a class="navbar-brand" href="index.php">Info Marga</a>
      <form class="form-inline">
        <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
      </form>
    </nav>

    <!--jumbotron-->
    <div class="jumbotron jumbotron-fluid bg-primary">
      <div class="container text-center">
        <h1 class="display-4"><span>Corona Virus</span></h1>
        <p class="lead">
            <h2>Pantau penyebaran virus Covid-19 di Dunia </h2>
        </p>
      </div>
    </div>

  <style type="text/css">
    .box {
      padding: 30px 40px;
      border-radius:6px;
    }
  
  
  </style>



    <div class="container">
      <div class="row">
        <div class="col-md-4">
          <div class="bg-info box text-white">
            <div class="row">
              <div class="col-md-6">
                <h5>Positif</h5>
                <h2 id="data-kasus">69228394</h2>
                <h5>orang</h5>
              </div>
              <div class="col-md-4">
                <img src="img/sad.svg" style="width: 100px;">
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="bg-danger box text-white">
            <div class="row">
              <div class="col-md-6">
                <h5>Meninggal</h5>
                <h2 id="data-mati">1575621</h2>
                <h5>orang</h5>
              </div>
              <div class="col-md-4">
                <img src="img/cry.svg" style="width: 100px;">
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="bg-success box text-white">
            <div class="row">
              <div class="col-md-6">
                <h5>Sembuh</h5>
                <h2 id="data-sembuh">47983487</h2>
                <h5>orang</h5>
              </div>
              <div class="col-md-4">
                <img src="img/happy.svg" style="width: 100px;">
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-12 mt-4">
          <div class="bg-danger box text-white">
            <div class="row">
              <div class="col-md-6">
                <h2>Indonesia</h2>
                <h5 id="data-id">Positif : 592900 orang <br>Meningal : 18171 orang <br>Sembuh : 487445 orang</h5>
              </div>
              <div class="col-md-4">
                <img src="img/indonesia.svg" style="width: 150px;">
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-12 mt-4">
          <div class="bg-danger box text-white">
            <div class="row">
              <div class="col-md-6">
                <h2>Amerika</h2>
                <h5 id="data-id">Positif : 17394314 orang <br>Meningal : 314629 orang <br>Sembuh :  10170788 orang</h5>
              </div>
              <div class="col-md-4">
                <img src="img/jp-draws-US-Flag.svg" style="width: 150px;">
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-12 mt-4">
          <div class="bg-danger box text-white">
            <div class="row">
              <div class="col-md-6">
                <h2>Kanada</h2>
                <h5 id="data-id">Positif : 481630 orang <br>Meningal : 13799 orang <br>Sembuh : 391946 orang</h5>
              </div>
              <div class="col-md-4">
                <img src="img/Anonymous-Flag-of-Canada.svg" style="width: 160px;">
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <footer class="bg-primary text-center text-white mt-3 bt-2 pb-2">create by "HaryTukil"</footer>
    

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js"></script>
    
  </body>
</html>

<script>
    $(document).ready(function(){

      //semua data global
      semuadata();
      datanegara();

      //refresh otomatis
      setInterval function(){
       semuadata();
       datanegara();

      function semuadata(){
        $.ajax({
          url : 'https://coronavirus-19-api.herokuapp.com/all',
          succes : function(data){
            try{
              var json = data;
              var kasus = data.cases;
              var meningal = data.deaths;
              var sembuh = data.recovered;

              $('#data-kasus').html(kasus);
              $('#data-mati').html(meningal);
              $('#data-sembuh').html(sembuh);

            }catch{
              alert('error');
            }
          }
        });
      }

      function datanegara() {
        $.ajax({
          url : 'https://coronavirus-19-api.herokuapp.com/countries',
          succes : function(data){
            try{
              var json = data;
              var html = [];

              if(json.length > 0){
                var i;
                for(i=0; i < json.length; i++){
                  var datanegara = json[i];
                  var namanegara = datanegara.country

                  if(namanegara === 'Indonesia'){
                    var kasus = datanegara.cases;
                    var mati = datanegara.deaths;
                    var sembuh = datanegara.recovered;
                    $('data-id') html(
                      'positif : '+kasus+' orang <br>
                       meningal : '+mati+' orang <br>
                      sembuh : '+sembuh' orang'
                    )
                  }
                }
              }
             
            }catch{
              alert('error');
            }
          }
        });
      }
      function datanegara() {
        $.ajax({
          url : 'https://coronavirus-19-api.herokuapp.com/countries',
          succes : function(data){
            try{
              var json = data;
              var html = [];

              if(json.length > 0){
                var i;
                for(i=0; i < json.length; i++){
                  var datanegara = json[i];
                  var namanegara = datanegara.country

                  if(namanegara === 'USA'){
                    var kasus = datanegara.cases;
                    var mati = datanegara.deaths;
                    var sembuh = datanegara.recovered;
                    $('data-id') html(
                      'positif : '+kasus+' orang <br>
                       meningal : '+mati+' orang <br>
                      sembuh : '+sembuh' orang'
                    )
                  }
                }
              }
             
            }catch{
              alert('error');
            }
          }
        });
      }
      function datanegara() {
        $.ajax({
          url : 'https://coronavirus-19-api.herokuapp.com/countries',
          succes : function(data){
            try{
              var json = data;
              var html = [];

              if(json.length > 0){
                var i;
                for(i=0; i < json.length; i++){
                  var datanegara = json[i];
                  var namanegara = datanegara.country

                  if(namanegara === 'Canada'){
                    var kasus = datanegara.cases;
                    var mati = datanegara.deaths;
                    var sembuh = datanegara.recovered;
                    $('data-id') html(
                      'positif : '+kasus+' orang <br>
                       meningal : '+mati+' orang <br>
                      sembuh : '+sembuh' orang'
                    )
                  }
                }
              }
             
            }catch{
              alert('error');
            }
          }
        });
      }
</script>
