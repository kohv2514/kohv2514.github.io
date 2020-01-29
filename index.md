<!DOCTYPE html>
<html>
<head>
	<title>ESPR'S</title>
	<meta charset="utf-8">
	
<!-- BootStrap -->
	<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css">
<!-- popperjs -->
	<script src="https://unpkg.com/@popperjs/core@2.0.0-rc.3"></script>
<!-- jquery -->
	<script src="https://code.jquery.com/jquery-3.4.1.min.js"></script>
<!-- Bootstrapjs -->
	<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js"></script>
<!-- Style -->
	<link rel="stylesheet" type="text/css" href="style.css">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<style>
		.carousel-inner img{
			width: 100%;
			height: 100%;
		}
	</style>
	<script type="text/javascript">
    $(window).on('load',function(){
        $('#modin').modal('show');
    });
	</script>
</head>
<body>
<header>
<!-- Navigation -->
	<nav id="nabi" class="navbar navbar-expand-sm navbar-dark sticky-top">
		<a class="navbar-brand">
			<img class="img-fluid" src="/Users/Victor/Documents/projeto/img/esprs3.png" alt="ESPR'S">
		</a>
		<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#naabiba">
			<span class="navbar-toggler-icon"></span>
		</button>
		<div class="collapse navbar-collapse justify-content-center" id="naabiba">
			<ul class="navbar-nav">
				<li class="nav-item">
					<a class="nav-link" href="#">Home</a>
				</li>
				<li class="nav-item">
					<a class="nav-link" href="#">FeelDoLive</a>					
				</li>
				<li class="nav-item">
					<a class="nav-link" href="#">STREET LIFE PARK</a>					
				</li>
				<li class="nav-item">
					<a class="nav-link" href="#">FUJIYAMA探訪記</a>					
				</li>
				<li class="nav-item">
					<a class="nav-link" href="#">Goods</a>					
				</li>
			</ul> 			
		</div>
	</nav>
</header>
<!-- Center -->
	<div class="container">
		<div id="cent" class="carousel slide" data-ride="carousel">
<!-- Indicators -->
			<ul class="carousel-indicators">
				<li data-target="#cent" data-slide-to="0" class="active"></li>			
				<li data-target="#cent" data-slide-to="1"></li>		
				<li data-target="#cent" data-slide-to="2"></li>
				<li data-target="#cent" data-slide-to="3"></li>
				<li data-target="#cent" data-slide-to="4"></li>
				<li data-target="#cent" data-slide-to="5"></li>
			</ul>
<!-- Slides -->
			<div id="caru" class="carousel-inner rounded-lg">
				<div class="carousel-item active">
					<img src="/Users/Victor/Documents/projeto/img/ousside.jpeg">
					<div class="carousel-caption LetCar">
						<h2>ライブスペース</h2>
					</div>
				</div>
				<div class="carousel-item">
					<img src="/Users/Victor/Documents/projeto/img/meat2.jpg">
					<div class="carousel-caption LetCar">
						<h2>BBQスペース</h2>
					</div>
				</div>
				<div class="carousel-item">
					<img src="/Users/Victor/Documents/projeto/img/event2.jpg">
					<div class="carousel-caption LetCar">
						<h2>フォトスタジオ</h2>
					</div>
				</div>
				<div class="carousel-item">
					<img src="/Users/Victor/Documents/projeto/img/spl22.jpg">
					<div class="carousel-caption LetCar">
						<h2>メンテナンススペース</h2>
					</div>
				</div>
				<div class="carousel-item">
					<img src="/Users/Victor/Documents/projeto/img/cent2.jpg">
					<div class="carousel-caption LetCar">
						<h2>イベントスペース</h2>
					</div>
				</div>
				<div class="carousel-item">
					<img src="/Users/Victor/Documents/projeto/img/tvstudio.jpg">
					<div class="carousel-caption LetCar">
					<h2>インターネットTVスタジオ</h2>
					</div>
				</div>
			</div>
<!-- C/Controls -->
			<a class="carousel-control-prev" href="#cent" data-slide="prev">
				<span class="carousel-control-prev-icon"></span>
			</a>
			<a class="carousel-control-next" href="#cent" data-slide="next">
				<span class="carousel-control-next-icon"></span>
			</a>
		</div>
	</div>
<!-- Contact -->
	<div class="contatainer">
		<div id=contactus class="card-deck text-center">
			<div class="card">
				<p class="card-text">TEL 0561-65-5591 <br><br> FAX 0561-65-5595</p>
			</div>
			<div class="card">
				<p class="card-text">info@esprs.xyz<br> </p>
			</div>
			<div class="card">
				<p class="card-text">〒470-0162 <br><br> 愛知県愛知郡東郷町春木狐塚９番</p>
			</div>
		</div>
	</div>
<!-- Footer-->>
	<div id="foot" class="container-fluid">
		<nav class="navbar navbar-expand-sm">
			<ul class="navbar-nav">
				<li class="nav-item">
					<a class="nav-link" href="https://www.facebook.com/ESPRSbroadcaster/">
						<img src="/Users/Victor/Documents/projeto/img/face.png">
					</a>
				</li>
				<li class="nav-item">
					<a class="nav-link" href="https://www.instagram.com/esprs.broadcaster/">
						<img src="/Users/Victor/Documents/projeto/img/insta.png">
					</a>
				</li>
				<li class="nav-item">
					<a class="nav-link" href="https://www.youtube.com/channel/UCGs8s8bwd2EqqcNRm4laufA">
						<img src="/Users/Victor/Documents/projeto/img/utub.png">
					</a>
				</li>
				<li class="nav-item">
					<a class="nav-link" href="https://freshlive.tv/esprs">
						<img src="/Users/Victor/Documents/projeto/img/abema.jpg">
					</a>
				</li>
			</ul>			
			<div class="ml-auto">									
				<span class="navbar-text ">
					ESPR'S Co.ltd <br>
				</span>
				<span class="navbar-text">
					Mosquito Battlers Gym Co.ltd
				</span>		
			</div>		
		</nav>
	</div>
<!-- SPONSORS -->
	<div id="sponsors" class="text-center">
		<h2>Sponsored by</h2>
		<a href="http://www.accel426.jp/">
			<img class="img-fluid rounded-lg" src="/Users/Victor/Documents/projeto/img/banner8.jpg">
		</a>

		<a href="http://www.woodies.jp/">
			<img class="img-fluid rounded-lg" src="/Users/Victor/Documents/projeto/img/banner5.jpg">
		</a>

		<a href="http://www.fafinc.net/">
			<img class="img-fluid rounded-lg" src="/Users/Victor/Documents/projeto/img/banner_faf.jpg">
		</a>
	</div>	
<!-- Modal -->
	<div class="modal fade" id="modin">
		<div class="modal-dialog modal-dialog-centered modal">
			<div class="modal-content">
				<div class="modal-body">
					<button type="button" class="close" data-dismiss="modal">x</button>
					<img src="/Users/Victor/Documents/projeto/img/slp_2x.jpg">
				</div>				
			</div>
		</div>		
	</div>
</body>
</html>
