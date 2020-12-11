# myselfrishiii.github.io
<!DOCTYPE html>
<html>
<head>
	<title>My Web</title>
	<meta name="viewport" content="width=device-width, initial-scale=1">
	   <link href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet" integrity="sha384-wvfXpqpZZVQGK6TAh5PVlGOfQNHSoD2xbE+QkPxCAFlNEevoEH3Sl0sibVcOQVnN" crossorigin="anonymous">
	   <script
  src="https://code.jquery.com/jquery-3.3.1.slim.min.js"
  integrity="sha256-3edrmyuQ0w65f8gfBsqowzjJe2iM6n0nKciPUp8y+7E="
  crossorigin="anonymous"></script>
	   <link rel="stylesheet" type="text/css" href="animate.min.css">
	   <link rel="stylesheet" href="font-awesome.min.css">
	<!-- <link rel="stylesheet" type="text/css" href="bootstrap.min.css">
	<script type="text/javascript" src="bootstrap.min.js"></script> -->
	
	<style type="text/css">
			html{
				scroll-behavior: smooth;
			}

		body{
			background-color: rgba(255,0,0,.9);
			font-family: sans-serif;
			line-height: 1.8em;
			font-size: 18px bold;
			margin: 0;
            background-size: cover;
		}
			#side-icon{
				position: fixed;
				top:100px;
			}
      
			.affix{
				position: sticky;
				top:0;

			    }

				a{
					color: #fff;
					text-decoration: none;
					background-color: ;
					/*border: 1px solid #fff;*/
					line-height: 1.5em;
					border-radius:none;
				}


				.slantedDivA{
				            position: relative;
				            width: 100%;
				            height: 400px;
				            background: rgba(111,25,40,.5);
				            box-sizing: border-box;
				            padding: 30px;
     					   }
        .clr{
        	clear: both;
        }
        
        .slantedDivA:after{
            position: absolute;
            width: 100%;
            height: 100%;
            content: "";
            background: inherit;
            top:0;
            right: 0;
            bottom: 0;
            left: 0;
            z-index: -1;
            transform-origin: top right;
            transform: skewY(-4deg);
        }

		.containerr{
			width: 100%;
			margin: auto;
			overflow: hidden;
		}
		#main-header{
			background-color: orange;
			color: #fff;
			height: 70px;
			z-index: 100;

		}

		#navbtn{
			
				width:50px;
				height: 50px;
				background-color: #333;
				transform: translate(0px,15px);
				float: right;
				border-radius: 30%;
				margin-right: 5px;
				visibility: visible;
		}

		#navbtn1{
			
				width:250px;
				height: 50px;
				background-color: #333;
				transform: translate(0px,10px);
				float: left;
				border-radius: 30%;
				margin-bottom: 22px;
				margin-left: 20px;
				text-align: center;
				font-size: 20px;
				font-variant-caps: unset;
				box-shadow: 0px -5px 2px 2px rgba(0,0,0,.7); 
		}

		.btnMedia{
			background-color: deepskyblue;
			border-radius: 10px;
			font-size: 18px;
			transform: translate(0px,-13px);
		}
        .btnMedia:hover{
		      box-shadow: 0px 0px 10px 5px #99ffff;
            transform: scale(2) translate(0px,-10px);
             background: #55ff99;
            transition: .5s;
		}

		.btnMedia i{
			color: #fff;
		}

		#navbtn1:hover{
			background-color: #666;
            transition: .5s;
		}

		#main-header i{
			font-size: 26px;
			color: #ff1199;
		}

		#navbar{
			background-color: #333;
            opacity: .9;
			color: #fff;
			z-index: 10;
			
		}
	
		#navbar ul{
			padding:0;
			list-style: none;
		}
        
		#navbar li{
			display: inline;

		}
        
		#navbar a{
			 color: #fff;
			text-decoration: none;
			padding-right : 15px;
			margin-left: 10px;
			font-size: 20px;
		}
        
        #navbar i{
            color: #f19;
        }
        
		#showcase{
			background-image: url('https://images.unsplash.com/photo-1442406964439-e46ab8eff7c4?dpr=2&fit=crop&fm=jpg&h=825&q=50&w=1450');
			background-position:  center;
            background-size: cover;
			height: auto;
           /* border-radius: 30% 0% 30% 0%/50% 50% 50% 0%;*/

		}
        
        #showcase i{
            color: red;
        }
		#showcase p{
				text-align: top;
				font-family: serif,sans-serif;
				font-size: 50px;
				line-height: 1.5em;
				padding-top: 140px;
				color: #fff;
			
		}
        
        #feeds{
            font-family: cursive;
            font-size: 80px;
            padding-top: 100px;
            text-align: center;
            color: #219aaa;
            text-decoration: underline;
            
        }
        
       /* .feedscontainer{
            background: url(green.jpg);
            background-size: cover;
        }*/
		.left-content{
			float: left;
			width: 69%;
			padding:10px;
			font-size: 18px ;
			color: #000;
			margin-top: 10px;
            margin-bottom: 50px;
            margin-left: 5px;
            background-color: #f66;
            border-radius: 5% 50% 30% 0%/50% 20% 20% 50%;
			box-sizing: border-box;
            transform-origin:  top center;
            transform: skewY(-2deg)scale(.9);
            box-shadow: 0px 0px 5px 5px black ;
		}
        .left-content:hover{
               transform-origin:  left;
            transform: rotate(0deg)scale(1);
        }
		.sidebar{
			float: right;
			width: 30%;
			padding: 10px;
			margin-top: 20px;
            margin-bottom: 50px;
            margin-right: 10px;
			background-color: #661166;
            border-radius: 20% 20% 30% 20%/30% 20% 30% 50%;
            text-align: center;
            word-wrap:wrap; 
			color: #fff;
			box-sizing: border-box;
            transform-origin: top ;
            transform: rotate(5deg) scale(.9);
            box-shadow: 0px 0px 5px 5px black ;
		}
        .sidebar:hover{
            transform-origin: top ;
            transform: rotate(0deg) scale(1);
        }
        
        
        /*-----------------testimonial coding ---------------------*/
        
          #testimonial{

			text-align: center;
			color: #000;
			font-size: 80px;
              font-family: cursive;
			padding-top: 100px; 
              padding-bottom: 10px;
			text-decoration: underline;
		}
        
        #testimg{
           
					width:100px;
					height: 100px;
                    top:-60px;
					border-radius: 50%;
                    box-shadow: 0px 0px 10px 5px ;
            
            }
        .btnMediatest{
			background-color: red;
			border-radius: 10px;
			font-size: 18px;
            margin-top: 0px;
			transform: translate(0px,-40px);
		}
        .btnMediatest:hover{
		      box-shadow: 0px 0px 10px 5px #99ffff;
            transform: scale(2) translate(0px,-20px);
             background: #55ff99;
            transition: .5s;
		}

		.btnMediatest i{
			color: #000099;
		}
        #testimg:hover
        {
            transform-origin: top right;
            transform: rotate(360deg);
             box-shadow: 0px 0px 5px 5px black ;
            transition: .5s;
        }
        .testimg{
				width: 25%;
				height: auto;
				float: right;
				text-align: center;
				color: #000 ;
                margin-top: 0px;
                margin-bottom: 50px;
                transition: .5s;
                 border: 2px solid #fff;
                box-shadow: 0px 0px 5px 5px black ;
                box-sizing: border-box;
                transform: rotate(0deg)scale(.9);
            
		}
        .testimg1{
            	background-color: rgba(44,223,166,.5);
                border-radius: 50% 50% 60% 50% / 50% 50% 80% 40%;
        }
        .testimg:hover{
            transform-origin: left;
            transform: rotate(360deg);
            background-color: rgba(22,255,22,.6);
                border-radius: 50% 50% 70% 70% / 50% 50% 90% 90%;
        }
         .testimg2{
            		background-color: rgba(255,25,222,.5);
                 border-radius: 40% 50% 20% 70% / 50% 50% 10% 90%;
        }
         .testimg3{
            		background-color: rgba(55,207,225,.5);
                 border-radius: 50% 50% 70% 70% / 50% 5% 80% 40%;
        }
         .testimg4{
            		background-color: rgba(196,20,88,.5);
                border-radius: 50% 90% 70% 70% / 50% 50% 50% 90%;
        }
         .testimg5{
            		background-color: rgba(111,20,650,.5);
                 border-radius: 50% 0% 70% 70% / 50% 50% 30% 0%;
        }
         .testimg6{
            		background-color: rgba(222,250,0,.5);
                 border-radius: 50% 50% 70% 70% / 50% 50% 80% 90%;
        }
         .testimg7{
            		background-color: rgba(170,50,180,.5);
                 border-radius:50% 50% 30% 70% / 50% 50% 80% 40%;
        }
         .testimg8{
            		background-color: rgba(250,150,50,.5);
                  border-radius: 50% 80% 40% 70% / 70% 50% 80% 90%;
        }
        
        
        .testimg p{
              margin-top: 0px
            font: 18px solid #000;
            padding: 30px;
            
            
        }
        .testimg >h3{
                
                margin-bottom:50px;
            color: darkblue
        }
       
     /*   .testicontainer{
            background: url(galhd.jpg);
        }*/
        
		
        
        
/*--------------------gallery coding -------------*/
        
        #gallery{
            color: #000;
            font-family: cursive;
			text-align: center;
			font-size: 80px;
			padding-top: 110px; 
			text-decoration: underline;
		}
        .gun:hover{
            transform:scale(2);
        }
        
		#galleryimg{
					width:220px;
					height: 200px;
					border-radius: 30%;
                    box-shadow: 0px 0px 10px 5px ;
		}
        #galleryimg:hover
        {
             box-shadow: 0px 0px 5px 5px black ;
            transition: .5s;
        }

		.slideimg{
				width: 25%;
				height: auto;
				float: right;
				text-align: center;
				color: #000 ;
				margin-top: 30px;
				background-color: rgba(255,55,251,.8);
                border-radius: 0% 0% 70% 70% / 0% 50% 80% 90%;
            transition: .5s;
             border: 2px solid #fff;
            box-sizing: border-box;
            box-shadow: 0px 0px 5px 5px black ;
				transform: rotate(0deg)scale(.9);
		}
        
        .slideimg:hover{
            transform-origin: top left;
            transform: rotate(360deg)scale(1);
              box-shadow: 0px 0px 10px 0px black;
            background-color: #f55;
            transition: 1s;
        }
        .slideimg p{
          background-color: rgba(255,55,251,.8);
            border-radius: 40px 0px;
            font: 20px solid #000;    
            
        }
        .slideimg p:hover{
            background: #ff6666;
            font-size: 20px;
            border: 2px solid transparent;
            margin-top: 5px;
            transition: .5s;
            
        }
       /* .gallerycontainer{
            background: url(galaxy.jpg);
            
        }
        .gallerycontainer:after{
            filter: blur(5px);
        }*/
		#main-footer{
			text-align: center;
			padding: 5px;
			margin-top: 40px;
			background-color: #333;
			color:#fff;
		}
		@media(max-width: 1120px)  {
            #testimg{
					width: 100px;
					height: 100px;
			}
			.testimg{
				width: 33%;
				float: left;
			}
			#galleryimg{
					width: 220px;
					height: 200px;
			}
			.slideimg{
				width: 33%;
				float: left;
			}
		}
			@media(max-width: 955px)  {
                #testimg{
					width: 100px;
					height: 100px;
			}
			.testimg{
				width: 50%;
				float: left;
			}
			#galleryimg{
					width: 220px;
					height: 200px;
			}
			.slideimg{
				width: 50%;
				float: left;
			}
		}
		@media(max-width: 686px)  {
			#main-header{
				position: sticky;
				height: 75px;
				top:0;
			}
			
			.affix{
				position: sticky;
				top: 75px;
			}
			
			#navbar{
				text-align: center;
			}
			
			#navbar li{
				display: block;
			
			}
            #feeds{
            font-size: 40px;
        }
			.left-content{
				width: 100%;
				float: none;
			}
			.sidebar{
				width: 100%;
				float: none;
			}
            #testimonial{
			font-size: 50px;
                color: #000;
			
		    }
            .testimg{
				width: 100%;
				float: none;
			}
            #gallery{
                font-size: 50px;
                color: #000;
            }
			.slideimg{
				width: 100%;
				float: none;
			}

		}

	</style>
</head>
<body >

	<div id="side-icon">
	<a href="https://w3schools.com"> <i class="fa fa-signal"></i></a>
	</div>

		<header id="main-header" >
			<div class="containerr">
				<button id="navbtn">
					<a href="#navCollapse" class="animated hang"><i class="fa fa-bars"></i></a>
			</button>
				<button id="navbtn1" >
					<a href="#" class="animated flipInY "><i class="fa fa-motorcycle "></i>CODERS JUNCTION</a>

			</button>
			</div>
		</header>
		<nav id="navbar"  class="affix">
			<div class="containerr">
				<ul class="animated swing">
					<li><a href="#"><i class="fa fa-home"> </i>Home</a></li>
					<li><a href="#feeds"><i class="fa fa-feed"> </i>Feeds</a></li>
					<li><a href="#testimonial"><i class="fa fa-google"> </i>Testimonial</a></li>
					<li><a href="#gallery"><i class="fa fa-tv"> </i>Gallery</a></li>
					<li><a href="#"><i class="fa fa-bell"> </i>Services</a></li>
					<li><a href="#"><i class="fa fa-phone"> </i>Contact</a></li>
				</ul>
			</div>
		</nav>
		<section id="showcase">
				<div class="containerr">
				
					<p class="animated slideInUp"><i class="fa fa-quote-left"> </i>This webpage is encoded by "Gaurav singh Rawat".
					Here we can see the different sections are created without taking help of Bootstrap.
				Bootstrap has many advantages upon web development and have become most popular framework at this time.<i class="fa fa-quote-right"> </i></p>
				</div>
		</section>
		    
		    <div class="feedscontainer">    
			<div class="containerr">
			<h1 id="feeds">Daily Feeds</h1>
				<section class="left-content">
					<h1><u>Author Section</u></h1>
					<p class="animated slideInLeft">This webpage is encoded by "Gaurav singh Rawat".
					Here we can see the different sections are created without taking help of Bootstrap.
				Bootstrap has many advantages upon web development and have become most popular framework at this time.
			This webpage is encoded by "Gaurav singh Rawat".
					Here we can see the different sections are created without taking help of Bootstrap.
				Bootstrap has many advantages upon web development and have become most popular framework at this time.</p>
				</section>
				<aside class="sidebar">
					<p class="animated slideInRight">This webpage is encoded by "Gaurav singh Rawat".
					Here we can see the different sections are created without taking help of Bootstrap.
				Bootstrap has many advantages upon web development and have become most popular framework at this time.</p>
				</aside>
			</div>
			
			<div class="containerr" >
			
				<section class="left-content">
					<h1><u>Author Section</u></h1>
					<p class="animated slideInLeft">This webpage is encoded by "Gaurav singh Rawat".
					Here we can see the different sections are created without taking help of Bootstrap.
				Bootstrap has many advantages upon web development and have become most popular framework at this time.
			This webpage is encoded by "Gaurav singh Rawat".
					Here we can see the different sections are created without taking help of Bootstrap.
				Bootstrap has many advantages upon web development and have become most popular framework at this time.</p>
				</section>
				<aside class="sidebar">
					<p class="animated slideInRight">This webpage is encoded by "Gaurav singh Rawat".
					Here we can see the different sections are created without taking help of Bootstrap.
				Bootstrap has many advantages upon web development and have become most popular framework at this time.</p>
				</aside>
			</div>

			<div class="containerr">
				<section class="left-content">
					<h1><u>Author Section</u></h1>
					<p class="animated slideInLeft">This webpage is encoded by "Gaurav singh Rawat".
					Here we can see the different sections are created without taking help of Bootstrap.
				Bootstrap has many advantages upon web development and have become most popular framework at this time.
			This webpage is encoded by "Gaurav singh Rawat".
					Here we can see the different sections are created without taking help of Bootstrap.
				Bootstrap has many advantages upon web development and have become most popular framework at this time.</p>
				</section>
				<aside class="sidebar">
					<p class="animated slideInRight">This webpage is encoded by "Gaurav singh Rawat".
					Here we can see the different sections are created without taking help of Bootstrap.
				Bootstrap has many advantages upon web development and have become most popular framework at this time.</p>
				</aside>
			</div>
			<div class="containerr">
				<section class="left-content">
					<h1><u>Author Section</u></h1>
					<p class="animated slideInLeft">This webpage is encoded by "Gaurav singh Rawat".
					Here we can see the different sections are created without taking help of Bootstrap.
				Bootstrap has many advantages upon web development and have become most popular framework at this time.
			This webpage is encoded by "Gaurav singh Rawat".
					Here we can see the different sections are created without taking help of Bootstrap.
				Bootstrap has many advantages upon web development and have become most popular framework at this time.</p>
				</section>
				<aside class="sidebar">
					<p class="animated slideInRight">This webpage is encoded by "Gaurav singh Rawat".
					Here we can see the different sections are created without taking help of Bootstrap.
				Bootstrap has many advantages upon web development and have become most popular framework at this time.</p>
				</aside>
			</div>
            </div>
            
              
             <!-- Testimonial page -->
             
             
             
         <div class="testicontainer">
             <div class="containerr">
			  <h1 id="testimonial">Testimonial</h1>
				<section class="testimg1 testimg" >
					
					<a href="https://images.unsplash.com/photo-1442406964439-e46ab8eff7c4?dpr=2&fit=crop&fm=jpg&h=825&q=50&w=1450"><img src="https://images.unsplash.com/photo-1442406964439-e46ab8eff7c4?dpr=2&fit=crop&fm=jpg&h=825&q=50&w=1450" id="testimg" class="animated slideInDown"></a>
					<p class="animated slideInLeft"><i class="fa fa-quote-left"></i>Hello,We are professional in our work.
					Quality work is the aim of the company in measurable price.<i class="fa fa-quote-right"></i></p>
					<h3 class="animated slideInLeft">"Gaurav singh Rawat"</h3>
					<button class="btnMediatest" ><a href="#" class="animated slideInUp"><i class="fa fa-facebook" ></i></a></button>
					<button class="btnMediatest"><a href="#"><i class="fa fa-twitter"></i></a></button>
					<button class="btnMediatest"><a href="#"><i class="fa fa-instagram"></i></a></button>
					<button class="btnMediatest"><a href="#"><i class="fa fa-search"></i></a></button>
				</section>

				<section class="testimg2 testimg" >
					
					<a href="https://images.unsplash.com/photo-1442406964439-e46ab8eff7c4?dpr=2&fit=crop&fm=jpg&h=825&q=50&w=1450"><img src="https://images.unsplash.com/photo-1442406964439-e46ab8eff7c4?dpr=2&fit=crop&fm=jpg&h=825&q=50&w=1450" id="testimg" class="animated slideInDown"></a>
					<p class="animated slideInLeft"><i class="fa fa-quote-left"></i>Hello,We are professional in our work.
					Quality work is the aim of the company in measurable price.<i class="fa fa-quote-right"></i></p>
					<h3 class="animated slideInLeft">"Gaurav singh Rawat"</h3>
					<button class="btnMediatest" ><a href="#" class="animated slideInUp"><i class="fa fa-facebook" ></i></a></button>
					<button class="btnMediatest"><a href="#"><i class="fa fa-twitter"></i></a></button>
					<button class="btnMediatest"><a href="#"><i class="fa fa-instagram"></i></a></button>
					<button class="btnMediatest"><a href="#"><i class="fa fa-search"></i></a></button>
				</section>

				<section class="testimg3 testimg" >
					
					<a href="https://images.unsplash.com/photo-1442406964439-e46ab8eff7c4?dpr=2&fit=crop&fm=jpg&h=825&q=50&w=1450"><img src="https://images.unsplash.com/photo-1442406964439-e46ab8eff7c4?dpr=2&fit=crop&fm=jpg&h=825&q=50&w=1450" id="testimg" class="animated slideInDown"></a>
					<p class="animated slideInLeft"><i class="fa fa-quote-left"></i>Hello,We are professional in our work.
					Quality work is the aim of the company in measurable price.<i class="fa fa-quote-right"></i></p>
					<h3 class="animated slideInLeft">"Gaurav singh Rawat"</h3>
					<button class="btnMediatest" ><a href="#" class="animated slideInUp"><i class="fa fa-facebook" ></i></a></button>
					<button class="btnMediatest"><a href="#"><i class="fa fa-twitter"></i></a></button>
					<button class="btnMediatest"><a href="#"><i class="fa fa-instagram"></i></a></button>
					<button class="btnMediatest"><a href="#"><i class="fa fa-search"></i></a></button>
				</section>
				<section class="testimg4 testimg" >
					
					<a href="https://images.unsplash.com/photo-1442406964439-e46ab8eff7c4?dpr=2&fit=crop&fm=jpg&h=825&q=50&w=1450"><img src="https://images.unsplash.com/photo-1442406964439-e46ab8eff7c4?dpr=2&fit=crop&fm=jpg&h=825&q=50&w=1450" id="testimg" class="animated slideInDown"></a>
					<p class="animated slideInLeft"><i class="fa fa-quote-left"></i>Hello,We are professional in our work.
					Quality work is the aim of the company in measurable price.<i class="fa fa-quote-right"></i></p>
					<h3 class="animated slideInLeft">"Gaurav singh Rawat"</h3>
					<button class="btnMediatest" ><a href="#" class="animated slideInUp"><i class="fa fa-facebook" ></i></a></button>
					<button class="btnMediatest"><a href="#"><i class="fa fa-twitter"></i></a></button>
					<button class="btnMediatest"><a href="#"><i class="fa fa-instagram"></i></a></button>
					<button class="btnMediatest"><a href="#"><i class="fa fa-search"></i></a></button>
				</section>
				<section class="testimg5 testimg" >
				
					<a href="https://images.unsplash.com/photo-1442406964439-e46ab8eff7c4?dpr=2&fit=crop&fm=jpg&h=825&q=50&w=1450"><img src="https://images.unsplash.com/photo-1442406964439-e46ab8eff7c4?dpr=2&fit=crop&fm=jpg&h=825&q=50&w=1450" id="testimg" class="animated slideInDown"></a>
					<p class="animated slideInLeft"><i class="fa fa-quote-left"></i>Hello,We are professional in our work.
					Quality work is the aim of the company in measurable price.<i class="fa fa-quote-right"></i></p>
					<h3 class="animated slideInLeft">"Gaurav singh Rawat"</h3>
					<button class="btnMediatest" ><a href="#" class="animated slideInUp"><i class="fa fa-facebook" ></i></a></button>
					<button class="btnMediatest"><a href="#"><i class="fa fa-twitter"></i></a></button>
					<button class="btnMediatest"><a href="#"><i class="fa fa-instagram"></i></a></button>
					<button class="btnMediatest"><a href="#"><i class="fa fa-search"></i></a></button>
				</section>
				<section class="testimg6 testimg" >
					
					<a href="https://images.unsplash.com/photo-1442406964439-e46ab8eff7c4?dpr=2&fit=crop&fm=jpg&h=825&q=50&w=1450"><img src="https://images.unsplash.com/photo-1442406964439-e46ab8eff7c4?dpr=2&fit=crop&fm=jpg&h=825&q=50&w=1450" id="testimg" class="animated slideInDown"></a>
					<p class="animated slideInLeft"><i class="fa fa-quote-left"></i>Hello,We are professional in our work.
					Quality work is the aim of the company in measurable price.<i class="fa fa-quote-right"></i></p>
					<h3 class="animated slideInLeft">"Gaurav singh Rawat"</h3>
					<button class="btnMediatest" ><a href="#" class="animated slideInUp"><i class="fa fa-facebook" ></i></a></button>
					<button class="btnMediatest"><a href="#"><i class="fa fa-twitter"></i></a></button>
					<button class="btnMediatest"><a href="#"><i class="fa fa-instagram"></i></a></button>
					<button class="btnMediatest"><a href="#"><i class="fa fa-search"></i></a></button>
				</section>
				<section class="testimg7 testimg" >
				
					<a href="https://images.unsplash.com/photo-1442406964439-e46ab8eff7c4?dpr=2&fit=crop&fm=jpg&h=825&q=50&w=1450"><img src="https://images.unsplash.com/photo-1442406964439-e46ab8eff7c4?dpr=2&fit=crop&fm=jpg&h=825&q=50&w=1450" id="testimg" class="animated slideInDown"></a>
					<p class="animated slideInLeft"><i class="fa fa-quote-left"></i>Hello,We are professional in our work.
					Quality work is the aim of the company in measurable price.<i class="fa fa-quote-right"></i></p>
					<h3 class="animated slideInLeft">"Gaurav singh Rawat"</h3>
					<button class="btnMediatest" ><a href="#" class="animated slideInUp"><i class="fa fa-facebook" ></i></a></button>
					<button class="btnMediatest"><a href="#"><i class="fa fa-twitter"></i></a></button>
					<button class="btnMediatest"><a href="#"><i class="fa fa-instagram"></i></a></button>
					<button class="btnMediatest"><a href="#"><i class="fa fa-search"></i></a></button>
				</section>
				<section class="testimg8 testimg" >
					
					<a href="https://images.unsplash.com/photo-1442406964439-e46ab8eff7c4?dpr=2&fit=crop&fm=jpg&h=825&q=50&w=1450"><img src="https://images.unsplash.com/photo-1442406964439-e46ab8eff7c4?dpr=2&fit=crop&fm=jpg&h=825&q=50&w=1450" id="testimg" class="animated slideInDown"></a>
			<p class="animated slideInLeft"><i class="fa fa-quote-left"></i>Hello,We are professional in our work.
					Quality work is the aim of the company in measurable price.<i class="fa fa-quote-right"></i></p>
					<h3 class="animated slideInLeft">"Gaurav singh Rawat"</h3>
					<button class="btnMediatest" ><a href="#" class="animated slideInUp"><i class="fa fa-facebook" ></i></a></button>
					<button class="btnMediatest"><a href="#"><i class="fa fa-twitter"></i></a></button>
					<button class="btnMediatest"><a href="#"><i class="fa fa-instagram"></i></a></button>
					<button class="btnMediatest"><a href="#"><i class="fa fa-search"></i></a></button>
				</section>
			</div>
        </div>
            
            
            
             <!-----------------Image gallary  --------------------------------- -->
             
             
             
             
             
         <div class="gallerycontainer">
			<div class="containerr">
			  <h1 id="gallery">GALLERY</h1>
				<section class="slideimg" >
					<h1 class="animated slideInLeft"><u>Tekken</u></h1>
					<a href="https://images.unsplash.com/photo-1442406964439-e46ab8eff7c4?dpr=2&fit=crop&fm=jpg&h=825&q=50&w=1450"><img src="https://images.unsplash.com/photo-1442406964439-e46ab8eff7c4?dpr=2&fit=crop&fm=jpg&h=825&q=50&w=1450" id="galleryimg" class="animated slideInDown"></a>
					<p class="animated slideInLeft">"Gaurav singh Rawat"</p>
					<button class="btnMedia" ><a href="#" class="animated slideInUp"><i class="fa fa-facebook" ></i></a></button>
					<button class="btnMedia"><a href="#"><i class="fa fa-twitter"></i></a></button>
					<button class="btnMedia"><a href="#"><i class="fa fa-instagram"></i></a></button>
					<button class="btnMedia"><a href="#"><i class="fa fa-search"></i></a></button>
				</section>
				<section class="slideimg" >
					<h1 class="animated slideInLeft"><u>Tekken</u></h1>
					<a href="https://images.unsplash.com/photo-1434543177303-ef2cc7707e0d?dpr=2&fit=crop&fm=jpg&h=825&q=50&w=1450"><img src="https://images.unsplash.com/photo-1434543177303-ef2cc7707e0d?dpr=2&fit=crop&fm=jpg&h=825&q=50&w=1450" id="galleryimg" class="animated slideInDown"></a>
					<p class="animated slideInLeft">"Gaurav singh Rawat"</p>
					<button class="btnMedia" ><a href="#" class="animated slideInUp"><i class="fa fa-facebook" ></i></a></button>
					<button class="btnMedia"><a href="#"><i class="fa fa-twitter"></i></a></button>
					<button class="btnMedia"><a href="#"><i class="fa fa-instagram"></i></a></button>
					<button class="btnMedia"><a href="#"><i class="fa fa-search"></i></a></button>
				</section>
				<section class="slideimg" >
					<h1 class="animated slideInLeft"><u>Tekken</u></h1>
					<a href="https://images.unsplash.com/photo-1444090542259-0af8fa96557e?dpr=2&fit=crop&fm=jpg&h=825&q=50&w=1450"><img src="https://images.unsplash.com/photo-1444090542259-0af8fa96557e?dpr=2&fit=crop&fm=jpg&h=825&q=50&w=1450" id="galleryimg" class="animated slideInDown"></a>
					<p class="animated slideInLeft"> "Gaurav singh Rawat"</p>
					<button class="btnMedia" ><a href="#" class="animated slideInUp"><i class="fa fa-facebook" ></i></a></button>
					<button class="btnMedia"><a href="#"><i class="fa fa-twitter"></i></a></button>
					<button class="btnMedia"><a href="#"><i class="fa fa-instagram"></i></a></button>
					<button class="btnMedia"><a href="#"><i class="fa fa-search"></i></a></button>
				</section>
				<section class="slideimg" >
					<h1 class="animated slideInLeft"><u>Tekken</u></h1>
					<a href="https://images.unsplash.com/photo-1439694458393-78ecf14da7f9?dpr=2&fit=crop&fm=jpg&h=825&q=50&w=1450"><img src="https://images.unsplash.com/photo-1439694458393-78ecf14da7f9?dpr=2&fit=crop&fm=jpg&h=825&q=50&w=1450" id="galleryimg" class="animated slideInDown"></a>
					<p class="animated slideInLeft">"Gaurav singh Rawat"</p>
					<button class="btnMedia" ><a href="#" class="animated slideInUp"><i class="fa fa-facebook" ></i></a></button>
					<button class="btnMedia"><a href="#"><i class="fa fa-twitter"></i></a></button>
					<button class="btnMedia"><a href="#"><i class="fa fa-instagram"></i></a></button>
					<button class="btnMedia"><a href="#"><i class="fa fa-search"></i></a></button>
				</section>
				<section class="slideimg" >
					<h1 class="animated slideInLeft"><u>Tekken</u></h1>
					<a href="https://images.unsplash.com/photo-1439694458393-78ecf14da7f9?dpr=2&fit=crop&fm=jpg&h=825&q=50&w=1450"><img src="https://images.unsplash.com/photo-1439694458393-78ecf14da7f9?dpr=2&fit=crop&fm=jpg&h=825&q=50&w=1450" id="galleryimg" class="animated slideInDown"></a>
					<p class="animated slideInLeft"> "Gaurav singh Rawat"</p>
					<button class="btnMedia" ><a href="#" class="animated slideInUp"><i class="fa fa-facebook" ></i></a></button>
					<button class="btnMedia"><a href="#"><i class="fa fa-twitter"></i></a></button>
					<button class="btnMedia"><a href="#"><i class="fa fa-instagram"></i></a></button>
					<button class="btnMedia"><a href="#"><i class="fa fa-search"></i></a></button>
				</section>
				<section class="slideimg" >
					<h1 class="animated slideInLeft"><u>Tekken</u></h1>
					<a href="https://images.unsplash.com/photo-1439524970634-649c37a69e5c?ixlib=rb-0.3.5&q=80&fm=jpg&crop=entropy&w=1450&h=825&fit=crop&s=bfda9916c885869b43b70738693428d9"><img src="https://images.unsplash.com/photo-1439524970634-649c37a69e5c?ixlib=rb-0.3.5&q=80&fm=jpg&crop=entropy&w=1450&h=825&fit=crop&s=bfda9916c885869b43b70738693428d9" id="galleryimg" class="animated slideInDown"></a>
					<p class="animated slideInLeft">"Gaurav singh Rawat"</p>
					<button class="btnMedia" ><a href="#" class="animated slideInUp"><i class="fa fa-facebook" ></i></a></button>
					<button class="btnMedia"><a href="#"><i class="fa fa-twitter"></i></a></button>
					<button class="btnMedia"><a href="#"><i class="fa fa-instagram"></i></a></button>
					<button class="btnMedia"><a href="#"><i class="fa fa-search"></i></a></button>
				</section>
				<section class="slideimg" >
					<h1 class="animated slideInLeft"><u>Tekken</u></h1>
					<a href="https://images.unsplash.com/photo-1444090542259-0af8fa96557e?dpr=2&fit=crop&fm=jpg&h=825&q=50&w=1450"><img src="https://images.unsplash.com/photo-1444090542259-0af8fa96557e?dpr=2&fit=crop&fm=jpg&h=825&q=50&w=1450" id="galleryimg" class="animated slideInDown"></a>
					<p class="animated slideInLeft"> "Gaurav singh Rawat"</p>
					<button class="btnMedia" ><a href="#" class="animated slideInUp"><i class="fa fa-facebook" ></i></a></button>
					<button class="btnMedia"><a href="#"><i class="fa fa-twitter"></i></a></button>
					<button class="btnMedia"><a href="#"><i class="fa fa-instagram"></i></a></button>
					<button class="btnMedia"><a href="#"><i class="fa fa-search"></i></a></button>
				</section>
				<section class="slideimg" >
					<h1 class="animated slideInLeft"><u>Tekken</u></h1>
					<a href="https://images.unsplash.com/photo-1434543177303-ef2cc7707e0d?dpr=2&fit=crop&fm=jpg&h=825&q=50&w=1450"><img src="https://images.unsplash.com/photo-1434543177303-ef2cc7707e0d?dpr=2&fit=crop&fm=jpg&h=825&q=50&w=1450" id="galleryimg" class="animated slideInDown"></a>
					<p class="animated slideInLeft">"Gaurav singh Rawat"</p>
					<button class="btnMedia" ><a href="#" class="animated slideInUp"><i class="fa fa-facebook" ></i></a></button>
					<button class="btnMedia"><a href="#"><i class="fa fa-twitter"></i></a></button>
					<button class="btnMedia"><a href="#"><i class="fa fa-instagram"></i></a></button>
					<button class="btnMedia"><a href="#"><i class="fa fa-search"></i></a></button>
				</section>
			</div>
			</div>

		<footer id="main-footer">
			<h3>Copyright &copy; 2019. All rights reserved</h3>
		</footer>
		<!-- <div class="clr"></div> -->

		<!-- <script type="text/javascript" src="jquery.js"></script> -->
	<script type="text/javascript">
		$(document).ready(function(){
			$('#navbar').hide();
			$('#navbtn').on('click',function(){
				$('#navbar').toggle(3000);
			});
		});
      
	</script>
</body>
</html>
