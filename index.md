<!DOCTYPE html>
<html>
<head>
	<title>Jacob Oliveira</title>
	<link rel="shortcut icon" href="favicon-32x32.ico"/>
	<link href="style_jro.css" rel="stylesheet">
	<meta http-equiv="content-type" content="text/html; charset=utf-8">
    <link href="https://fonts.googleapis.com/css?family=Lato|Marcellus+SC" rel="stylesheet">
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
	<meta name="viewport" content="width=device-width, initial-scale=1">
    
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
    <script>
        $(document).ready(function(){
        // Add smooth scrolling to all links
            $("a").on('click', function(event) {

        // Make sure this.hash has a value before overriding default behavior
            if (this.hash !== "") {
        // Prevent default anchor click behavior
            event.preventDefault();

        // Store hash
            var hash = this.hash;

        // Using jQuery's animate() method to add smooth page scroll
        // The optional number (800) specifies the number of milliseconds it takes to scroll to the specified area
            $('html, body').animate({
                scrollTop: $(hash).offset().top
                }, 800, function(){
   
        // Add hash (#) to URL when done scrolling (default click behavior)
        window.location.hash = hash;
                    });
                } // End if
            });
        });
    </script>
</head>

<body>
	
<div class="main" class="row">
    
    <header class="col-2">
        <nav>
        <!--    <a href="#home"><img alt="logo" src="Photos/namelogo.PNG"></a> -->
            <a class="logo" href="#home"><h1>Jacob <br> Oliveira</h1></a> 
            <ul class="options" id="menu">
                <li><a href="#about"><i class="fa fa-caret-right" aria-hidden="true"></i> About</a></li>
            	<li><a href="#work"><i class="fa fa-caret-right" aria-hidden="true"></i> Work</a></li>
            	<li><a href="#projects"><i class="fa fa-caret-right" aria-hidden="true"></i> Projects</a></li>
            	<li class="current"><a href="#resume"><i class="fa fa-caret-right" aria-hidden="true"></i> Resume</a></li>
            	<li><a href="#contact" class="current"><i class="fa fa-caret-right" aria-hidden="true"></i> Contact</a></li>
        	</ul>
            <button onclick="myFunction()" class="hamburger"><i class="fa fa-bars" aria-hidden="true"></i></button>
		</nav>         
	</header>
    
    <div id="spacer" class="col-2" display: hidden></div>
    
    <div id="content" class="col-10">
        <div id="spacer" class="col-0_5" display: hidden></div>
	    <section id="home" class="intro-container main-section col-11">
	        <div id="intro" class=" col-8">
	        	<h3>Hello Visitor!</h3>
				<p>Welcome to the little place on the web I call home. This site contains general info about me as well as some meaningful experiences and projects that I've done. It was made in the hopes of sharing a little about me and to showcase some of my knowledge and skills. My hope is that colleagues, friends, and potential employers can use this as a portal to access information about who Jacob is. I've tried to be as honest as possible in the writing, both in style and facts, so that you can best get to know me. However, if all you came here to find was my resume, you can get it <a href="#resume">here</a>. But please, explore! The navigation links on the left of the page bring you around to the different information described above. Please, feel free to contact me for any additional information or with any questions, or with anything that you think I may be well suited to tackle.</p>
	        	<h5>Regards,</h5>
				<h4>Jacob</h4>
	        </div><!--end "intro"-->

	        <div class="intro-photo col-4">
	            <img src="Photos/image0.jpg" alt="A photo of me" class="image">
	            <div class="intro-photo-text">
	                This is me!
				</div><!--end "intro-photo-text"-->
	        </div><!--end "intro-photo"-->
            
		</section><!--end "home" intro-container-->
		<div id="spacer" class="col-0_5" display: hidden></div>
        
		<section class="intro-card-container col-12">
            
            <div id="joke_slides" class="card everyother_2">
                <p class="card-title">Some of my favorite jokes</p>
                <div class="slideshow-container">
			
                    <div class="mySlides fade">
                        <div class="joke">
                            <p>Did you here about the guy who was in a car crash? They had to amputate his left arm and left leg</p>
                            <p>But dont worry, he's <i> all right </i> now.</p>
                        </div><!--end "joke"-->
                    </div><!--end "mySlides"-->

                    <div class="mySlides fade">
                        <div class="joke">
                            <p>Why do you never see elephants hiding in trees?</p>
                            <p>They're so darn good at it.</p>
                        </div><!--end "joke"-->
                    </div><!--end "mySlides"-->
                
				    <div class="mySlides fade">
                        <div class="joke">
                            <p>What did one eye say to the other?</p>
                            <p>"Between you and me, something smells"</p>
                        </div><!--end "joke"-->
                    </div><!--end "mySlides"-->

                    <div class="mySlides fade">
                        <div class="joke">
                            <p>Whats brown and sticky?</p>
                            <p>A stick!</p>
                        </div><!--end "joke"-->
                    </div><!--end "mySlides"-->
								
                    <div class="mySlides fade">
                        <div class="joke">
                            <p>Whats a pirates favorite letter?</p>
                            <p>You might thinks its "R",
                                <br>But its the "C"!</p>
                        </div><!--end "joke"-->
                    </div><!--end "mySlides"-->
		
                </div><!--end "slideshow-container"-->
                <br>

                    <div style="text-align:center">
                        <span class="dot"></span>
                        <span class="dot"></span>
                        <span class="dot"></span>
                        <span class="dot"></span>
                        <span class="dot"></span>
                    </div><!--end "dot jiggery-pokery"-->
		
            </div><!--end "joke_slides"-->
            
            <div id="quote" class="card everyother_2">
                <p class="card-title">Inspirational Quote</p>
		        "You miss 100% of the shots you dont take.
                <div class="wayne">- Wayne Gretzky"
                <p>- Micheal Scott</p></div>
            </div><!--end "quote"-->
		
        </section><!-- end "intro-card-contatiner"-->
        
        <section id="about" class="main-section col-12">
            <div class="title">
                <h2>About</h2>
            </div>
            
            <div id="about-content" class="words">
                <p>My name's Jacob Oliveira. I'm from Dartmouth, Massachusetts, and go to school at the Ohio State University. The first big chapter of my story started in high school, and the section I'm writing now takes place in college. the work and projects sections below focusses more on specific accomplishments of mine as opposed to the more general story that explains who I've grown to be (which is featured below).</p>

                <p>Dartmouth is lactated about an hour south of Boston on the South Coast of Massachusetts, which is arguably the greatest place to live in the world. Boating and going to the beach throughout the summer and building snow forts in the winter - I love the benefits of living in a four-season climate. The summer months offer plenty of time for my hobbies, and many have something to do with the ocean. Fishing for Sea Bass, Tautog, and Fluke, having campfires at the beach, and tuba-ing top the list; but I also love playing Frisbee, biking, and running. When not at school, I live here with my family, in which I am the middle child. I have an older brother Zach and younger brother Cory who are both three years apart from in age (but in opposite directions).</p>
                
                <p>In high school, I was very involved throughout the year. In the fall, I performed with the marching band, and in winter and spring I ran on the track team. Throughout the year, I was a member of school council, concert band, orchestra and was very involved with clubs. I was the co-president of the engineering club and participated in multiple robotics competitions like SeaPerch, First Tech Challenge, and Marine Advanced Technology Challenge (MATE). Science and math were my favorite subjects and I took as many APs as my school offered, including Chemistry, Biology, Calculus AB, and Statistics. During these years outside of school, I served community service as a Peer Leader at my local church, St. Julies, and as a volunteer performer in community bands.</p>
                
                <p>After hunting for the right school, I decided on Ohio State University. Despite being far from home, it seemed like a natural decision based on my scholarship package and the level of academic programs. In my first year, I became in involved in extracurricular such as playing sousaphone in the athletic band and being on the executive board of Hall Council. Academically, I pursued a Biomedical Engineering track and took many first year engineering classes such as calculus 1 and 2, general chemistry, and physics. I also took Ohio State's Fundamentals of Engineering Course and learned many valuable traits such as Matlab, SolidWorks, technical writing, and team working skills.</p>
                
                <p>In my second year at OSU, I am still on track to graduate in Biomedical Engineering and am continuing to get more involved around campus through residence life and clubs.</p>
            </div><!--end "about-words"-->
            
            <div id="snapshot-container">
                <div class="profile-container everyother_2">
                    <div class="profile-title">
                        <h3>Snapshot</h3>
                            <p>I'm a firm believer that everyone you meet knows something you don't.
                            <br>I also think the greatest thing we can do with our lives is learn as much as possible.</p>
                    </div><!--end "profile-title"-->

                    <div class="profile-photo">
                        <img src="Photos/DSC_0660_1.jpg" alt="A photo of me">
                    </div><!--end "profile-photo"-->

                    <div class="profile-info">
                        <p class="profile_title">Name:</p> <p class="profile_info">Jacob Oliveira</p>
                        <p class="profile_title">Started Breathing:</p> <p class="profile_info">19 years ago</p>
					   <p class="profile_title">Location:</p> <p class="profile_info">Massachusets/Ohio, United States, Earth</p>
				    </div><!--end "profile"-->
                </div><!--end "profile-container"-->
            </div><!--end "everyother_1"-->
        
        </section><!--end "about"-->
            
        <section id="work" class="main-section col-12">
            <div class="title">
                <h2>Work Experience</h2>
            </div>
            
            <div id="work-content" class="words">
				<h3>Mikel, Inc</h3> <h4>Summer Internship</h4>
					<h5>May 2016 - August 2016</h5>
						<p>Through this job I began the process to obtain a "Secret" level security clearance, which will soon allow me to work on classified government projects.</p>
                        <p>Working at MIKEL full time, I Learned the basics of Verilog Hardware Description Language using Field Programmable Gate Arrays (FPGAs) to be used in submarine combat system simulation units. Also, I worked on the installation of Naval test reconstruction software on Linux systems.</p>
						<hr>	
				<h3>Bittersweet Farms, Resteraunt and Tavern</h3> <h4>Dishwasher and Event Aid</h4>
					<h5>May 2015 - August 2015</h5>
						<p>Working as a dishwasher at a local restaurant, I gained a strong work ethic and learned that hard work pays off as I was given other tasks in the kitchen, such as plating dishes for weddings.</p>
						<hr>
				<h3>Naval Undersea Warfare Center</h3> <h4>Intern</h4>
					<h5>August 2014</h5>
						<p>I worked on a team with other interns alongside professional engineers and scientist to design, build and test an unmanned underwater vehicle (UUV) that completed specific tasks in a testing pool. From this experienced I learned teamwork and leadership skills, as well as how to manage a budget and schedule.</p>
            </div><!--end "work-experiences"-->
        </section><!--end "work"-->
			
        <section id="projects" class="main-section col-12">
			<div class="title">
					<h2>Projects</h2>
			</div><!--end "title"-->
			
			<div id="projects-card-container">
				<div class="projects-card everyother_2">
					<h3>Nanotechnolgy - Lab on a Chip</h3>
					<h5>January 2016 - April 2016</h5>
				        <p>The main project in my Introduction to Engineering class focusing on designing a Lab on a Chip that detects the concentration of flourecien in volumes on the micro- scale. I learned 3D modeling in SolidWorks, technical writing, introduction to fluid mechanics, and leadership skills.</p>
				</div><!--end "projects-card"-->
					
				<div class="projects-card everyother_2">
				    <h3>Train Simulation in MatLab</h3>
				    <h5>August 2015 - December 2015</h5>
                        <p>In my first coding project, I led a team of four to simulate a model train in MatLab.</p>
				</div><!--end "projects-card"-->
						
				<div class="projects-card everyother_2">
				    <h3>Home Automation Suite @ MAKE OHI/O</h3>
					<h5>March 2016</h5>
				        <p>Cross-displinary project made at 24 hour make-a-thon that utilized an Amazon Dot to automate household items like lights and an electric tea kettle. Won the Harris Sponsor Challenge in the category of "electro mechanical project".</p>	
				</div><!--end "projects-card"-->
					
				<div class="projects-card everyother_2">
					<h3>This Website</h3>
					<h5>June 2017 - August 2017</h5>
				        <p>Coding this website from scratch in my downtime over the summer before my sophmore year. Gaining experience in HTML, CSS, and JavaScript.</p>
				</div><!--end "projects-card"-->
					
				<div class="projects-card everyother_2">
                    <h3>Marine Advanced Technology Education (MATE) Challenge</h3>
                    <h5>August 2014</h5>
                        <p>After loosing support from the school system, my team and I privately sought funding and competed in the robotics competition independantly. We were awarded "Rookie of the Year" and "Safest Robot" Honors.</p>
                </div><!--end "projects-card"-->
				    	
                <div class="projects-card everyother_2">
                    <h3>SeaPerch Underwater Robotics Challenge</h3>
                    <h5>August 2014</h5>
                        <p>I built a SeaPerch, then we modified it and made it cooler.</p>
                </div><!--end "projects-card"-->
						
            </div><!--end "projects-container-->
        </section><!--end "width-container-->

        <section id="resume" class="main-section col-12">
            <div class="title">
                <h2>My Resume</h2>
            </div>
                
            <div id="resume-content" class="words">
                <p>To get a pdf version of my resume, please click the button below. This is a great document to get a quick look at my qualifications and areas of expertise, however there is much more information on the 'Experiences' and 'About Me' sections on this site!</p>
            </div><!--end "resume-content"-->
            
            <div id="resume-link" class="title">
				    <form method="get" action="Resume - Jacob Oliveira 2.pdf">
                        <center><button type="submit">Download Resume</button></center>
                    </form>
            </div><!--end "resume-link title"-->
                
            <div id="albert-quote-container">
                <div id="albert-quote" class="everyother_2">
                    <p>"If you judge a fish by its ability to climb a tree, it will live its entire life believing it is stupid."</p>
                    <p>- Albert Einstien</p>
                </div><!--end "albert-quote"-->
            </div><!--end "albert-quote-container"-->
        
        </section><!--end "resume"-->
            
		<section id="contact" class=" main-section col-12">
            <div class ="title">
                <h2>Contact</h2>
            </div>
            
            <div id="contact-info" class="col-5">	
                    
                <p>Please feel free to contact me through any of the means below or with the form to the right.<br> Thank you!</p>
                <div class="contact-list">
                    <p><a href="oliveira.31@buckeyemail.osu.edu"><i class="fa fa-envelope"></i>oliveira.31@osu.edu</a></p>
                    <p><a href="jacobroliveira@gmail.com"><i class="fa fa-envelope"></i>jacobroliveira@gmail.com</a></p>
                    <p><a href="https://goo.gl/7MnKcT"><i class="fa fa-linkedin"></i>LinkedIn</a></p>
                    <p><a href="https://jacoboliveira.com"><i class="fa fa-globe"></i>jacoboliveira.com</a></p>
                    <p><a href="#"><i class="fa fa-phone"></i>(508) 558-0989</a></p>
                </div><!--end "contact-list"-->
            </div><!--end "contact-info"-->
			
            <div id="contact-form" class="col-7">
                <form>
                    <label>Name</label>
                        <input name="name" placeholder="Your Name" required oninvalid="this.setCustomValidity('Woops! You missed a spot.')" oninput="setCustomValidity('')">
                    <label>Email</label>
				        <input name="email" type="email" placeholder="Your Email" required oninvalid="this.setCustomValidity('Woops! You missed a spot.')" oninput="setCustomValidity('')">
				    <label>Message</label>
						<textarea name="message" placeholder="Your Message" required oninvalid="this.setCustomValidity('Please leave me a message!')" oninput="setCustomValidity('')"></textarea>
                    <br>
				    <button id="submitbtn"><input id="submit" name="submit" value="Submit"></button>
                    <!-- type="submit" --><!--Add this into the above input and remove the button wrapper to make the form work -->
				</form>
            </div><!--end "contact-form-->
            
            <div id="sorry-message" class="sorry-message">
                <div id="sorry-message-content" class="sorry-message-content">
                    <span class="close">&times;</span>
                    <p>Sorry! This form doesn't quite work yet, but I'd love to hear from you! Please send and email to <strong>oliveira.31@osu.edu</strong> or any of the other contact methods listed on this site. Thanks!</p>
                </div>
            </div>
            
        </section><!--end "contact-container everyother_2"-->	
        
    </div><!--end "content"-->
    
</div><!--end "main row-->

<script src="control_jro.js"></script>

</body>
</html>
