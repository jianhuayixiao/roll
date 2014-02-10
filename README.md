<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="utf-8" />

		<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />

		<title>emp</title>
		<meta name="description" content="" />
		<meta name="author" content="jabriel" />

		<meta name="viewport" content="width=device-width; initial-scale=1.0" />
		<style type="text/css">
			body{ background-color: #CCE8CF; }
			article{  }
			section{ position: relative; width: 100px; height: 500px; margin: 0 auto;
				-moz-transform-style: preserve-3d; 
				-webkit-transform-style: preserve-3d;
				-moz-transform-origin: 116px 200px 116px;
				-webkit-transform-origin: 116px 200px 116px;
				-moz-animation: 10s linear 0s normal none infinite spin;
				-webkit-animation: 10s linear 0s normal none infinite spin;
			}
			section>div{ position: absolute; border-style: solid; border-width: 200px 0 200px 346px; 
				-moz-transform-origin: 0 0 0;
				-webkit-transform-origin: 0 0 0;
			}
			section>div:after{ color: white; content: 'Triangle'; left: -250px; position: absolute; }
			section>div:first-child{ border-color: rgba(0, 0, 0, 0) rgba(0, 0, 0, 0) rgba(0, 0, 0, 0) rgba(250, 0, 0, 0.6);
				
				-moz-transform: rotateY(-19.5deg) rotateX(180deg) translateY(-400px);
				-webkit-transform: rotateY(-19.5deg) rotateX(180deg) translateY(-400px);	
			}
			section>div:nth-child(2){ border-color: rgba(0, 0, 0, 0) rgba(0, 0, 0, 0) rgba(0, 0, 0, 0) rgba(0, 250, 0, 0.6); 
				-moz-transform: rotateY(90deg) rotateZ(60deg) rotateX(180deg) translateY(-400px);
				-webkit-transform: rotateY(90deg) rotateZ(60deg) rotateX(180deg) translateY(-400px);	
			}
			section>div:nth-child(3){ border-color: rgba(0, 0, 0, 0) rgba(0, 0, 0, 0) rgba(0, 0, 0, 0) rgba(0, 0, 250, 0.5); 
				-moz-transform: rotateX(60deg) rotateY(19.5deg);
				-webkit-transform: rotateX(60deg) rotateY(19.5deg);	
			}
			section>div:last-child{ border-color: rgba(0, 0, 0, 0) rgba(0, 0, 0, 0) rgba(0, 0, 0, 0) rgba(150, 50, 50, 0.5);
				-moz-transform: rotateX(-60deg) rotateY(19.5deg) translateX(-116px) translateY(-200px) translateZ(326px);
				-webkit-transform: rotateX(-60deg) rotateY(19.5deg) translateX(-116px) translateY(-200px) translateZ(326px);	
			}
			
			@-webkit-keyframes spin {
				from { -webkit-transform: rotateX(0deg) rotateY(0deg) rotateZ(0deg); }
				to   { -webkit-transform: rotateX(360deg) rotateY(360deg) rotateZ(360deg); }
			} 
			@-moz-keyframes spin {
				from { -moz-transform: rotateX(0deg) rotateY(0deg) rotateZ(0deg); }
				to   { -moz-transform: rotateX(360deg) rotateY(360deg) rotateZ(360deg); }
			} 
			
			
			
			
		</style>
	</head>

	<body>
		<article>
			<section>
				<div> </div>
				<div> </div>
				<div> </div>
				<div> </div>	
			</section>	
		</article>		
	</body>
</html>
