
<html lang="en">
  <head>
    
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css" integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">
	<style type = "text/css">
	
		.jumbotron{
		
			background-image: url("bg1.jpg");
			background-size: cover;
			text-align: center;
			color: white;
			
		}
		form{
		text-align: center;
		
		}
		#emailEntered{
		
			height: 30px;
			width: 300px;
			
		
		}
		#bodyText{
		text-align: center;
		margin-bottom: 100px;
		margin-top: 100px;
		
		}
		#logo{
		
		width: 20px;
		height: 20px;
		
		}
		#footer{
		
			background-color: yellow;
			margin-top: 150px;
			padding-top: 50px;
			text-align: center;
		
		}
		body{
			position: relative;
		}
	
	</style>

    <title>Bootstrap</title>
  </head>
  <body data-spy = "scroll" data-target="#navbar">
		<nav class="navbar navbar-expand-lg navbar-light bg-light navbar-fixed-top" id = "navbar">
			<a class="navbar-brand" href="#">MyApp</a>
			<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
				<span class="navbar-toggler-icon"></span>
			</button>

			<div class="collapse navbar-collapse" id="navbarSupportedContent">
				<ul class="navbar-nav mr-auto">
					<li class="nav-item active">
						<a class="nav-link" href="#jumbotron">Home <span class="sr-only">(current)</span></a>
					</li>
					<li class="nav-item">
						<a class="nav-link" href="#about">About</a>
					</li>
					<li class="nav-item">
						<a class="nav-link" href="#footer">Download</a>
					</li>
					<li class="nav-item">
						<a class="nav-link" href="#">The App</a>
					</li>
				</ul>
				<form class="form-inline my-2 my-lg-0">
					<input class="form-control mr-sm-2" type="email" placeholder="Email" aria-label="email">
					<input class="form-control mr-sm-2" type="password" placeholder="Password" aria-label="password">
					<button class="btn btn-success my-2 my-sm-0" type="submit">Login</button>
				</form>
			</div>
		</nav>
		<div class="jumbotron" id="jumbotron">
			<h1 class="display-4">My Awesome App!</h1>
			<p class="lead">This is why YOU should download this app!</p>
			<hr class="my-4">
			<p>Want to know MORE! Join our mailing list!</p>
			<form>
				<div class="row justify-content-center">   
					<div class="col-auto">
						<label class="sr-only" for="inlineFormInputGroup">Username</label>
						<div id = "emailEntered" class="input-group mb-2">
							<div class="input-group-prepend">
								<div class="input-group-text">@</div>
							</div>
							<input type="text" class="form-control" id="inlineFormInputGroup" placeholder="Your Email">
						</div>
					</div>
					<button type="submit" class="btn btn-primary">Submit</button>
				</div>
				
					
				
			</form>
			
		</div>
		<div id = "bodyText">
		
			<h1 class="display-4">Why This App Is Awesome</h1>
			<p class="lead">Summary, once again, of your app's awesomeness </p>
		
		</div>
	<div class = "container" >
	<div class="card-deck" id = "about">
		<div class="card">
			<img src="bg1.jpg" class="card-img-top" alt="...">
			<div class="card-body">
				<h5 class="card-title">Card title</h5>
				<p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
				<p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
			</div>
		</div>
		<div class="card">
			<img src="bg1.jpg" class="card-img-top" alt="...">
			<div class="card-body">
				<h5 class="card-title">Card title</h5>
				<p class="card-text">This card has supporting text below as a natural lead-in to additional content.</p>
				<p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
			</div>
		</div>
		<div class="card">
			<img src="bg1.jpg" class="card-img-top" alt="...">
			<div class="card-body">
				<h5 class="card-title">Card title</h5>
				<p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
				<p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
			</div>
		</div>
	</div>
	</div>
	<div  id = "footer">
	
		
			<h2>Download</h2>
			<p class = "lead">Really why should i download this app</p>
			<p><a href = ""><img id = "logo" src = "bg1.jpg"></a></p>
		
		
	
	</div>
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js" integrity="sha384-OgVRvuATP1z7JjHLkuOU7Xw704+h835Lr+6QL9UvYjZE3Ipu6Tp75j7Bh/kR0JKI" crossorigin="anonymous"></script>
    
  </body>
</html>
