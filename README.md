kirkkohlerYeomanWebsite
=======================

Personal Website using Yeoman webapp

Target site: https://kirkkohler.github.io/kirkkohlerWebsite

Build
-----

- npm install
- bower install
- grunt server

<!doctype html>
<!--[if lt IE 7]>      <html class="no-js lt-ie9 lt-ie8 lt-ie7"> <![endif]-->
<!--[if IE 7]>         <html class="no-js lt-ie9 lt-ie8"> <![endif]-->
<!--[if IE 8]>         <html class="no-js lt-ie9"> <![endif]-->
<!--[if gt IE 8]><!--> <html class="no-js"> <!--<![endif]-->
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <title>Kirk Kohler's Website | Home</title>
        <meta name="description" content="Kirk Kohler's web portal to my blogs, projects, twitter and contact information">
        <meta name="viewport" content="width=device-width">
        <!-- Place favicon.ico and apple-touch-icon.png in the root directory -->
        <!-- build:css(.tmp) styles/main.css -->
        <link rel="stylesheet" href="styles/main.css">
        <!-- endbuild -->
        <!-- build:js scripts/vendor/modernizr.js -->
        <script src="bower_components/modernizr/modernizr.js"></script>
        <!-- endbuild -->
    </head>
    <body>
        <!--[if lt IE 10]>
            <p class="browsehappy">You are using an <strong>outdated</strong> browser. I really want you to be happy surfing the web, so please <a href="http://browsehappy.com/">upgrade your browser</a> to improve your experience.</p>
        <![endif]-->

        <!-- only adding span for accessibility to know there is a background within page -->
        <span id="backgroundImg" role="img" aria-label="background image of big sur california"></span>

        <div class="container">
            <div class="header navbar">
                <ul class="nav nav-pills pull-left">
                    <h1 class="text-muted titleLink"><a href="http://kirkkohler.com">KirkKohler.com</a></h1>
                    <!-- <li class="active"><a href="#">Home</a></li> -->
                    <!-- <li><a href="#about" title="About Kirk">About</a></li> -->
                </ul>
                <!-- <i class="icon-external-link"></i>Icon Here -->
                <ul class="nav nav-pills pull-right">
                    <li><a href="https://medium.com/digital-cake" target="_blank" title="Blog">Blog</a></li>
                    <li><a href="http://www.linkedin.com/in/kirkkohler" target="_blank" title="Kirk's LinkedIn Account"><i class="fa fa-linkedin-square fa-2x"></i></a></li>
                    <li><a href="https://twitter.com/kirkkohler" target="_blank" title="Kirk's Twitter Feed"><i class="fa fa-twitter-square fa-2x"></i></a></li>
                    <li><a href="https://angel.co/u/kirk-kohler" target="_blank" title="Kirk's Angellist Account">AngelList</a></li>
                    <li><a href="https://github.com/kirkkohler" target="_blank" title="Kirk's Github"><i class="fa fa-github-square fa-2x"></i></a></li>
                </ul>
            </div>
            
            <!--<div class="jumbotron transparent">
                <h2>Welcome!</h2>
                <p class="lead">Thank you for visiting my site.  Please feel free to contact me with exciting project opportunities through my <a href="http://www.linkedin.com/in/kirkkohler" target="_blank">LinkedIn</a> profile.</p>
            -->
                <!-- <p><a class="btn btn-lg btn-success" href="#">Splendid!</a></p> -->
            <!--</div>-->
            <div class="row marketing" id="about">
                <div class="panel panel-default col-lg-12 transparent">
                    <h2>Current Projects</h2>
                    <ul>
                        <li><a href="http://cvrnt.com/" target="_blank">CVRNT Podcast</a> - (pronounced current) is a podcast/blog about the latest and greatest in Virtual Reality with some rife speculation. Subscribe at <a href="https://itunes.apple.com/us/podcast/cvrnt/id1167903953" target="_blank">iTunes</a>, <a href="https://play.google.com/music/m/Iqphq5drczoca63dip4wu5wdr6u?t=CVRNT_A_Virtual_Reality_Podcast_For_Your_Entertainment" target="_blank">Google Play</a> or wherever you listen to podcasts. Follow us on Twitter: <a href="https://twitter.com/cvrnt" target="_blank">@cvrnt</a>, <a href="https://www.youtube.com/channel/UCJqaCttI5biychf7UZirOnA" target="_blank">Youtube</a>, <a href="https://www.instagram.com/cvrntpodcast/" target="_blank">Instagram</a> and <a href="https://www.facebook.com/cvrntpodcast/" target="_blank">Facebook</a></li>
                        <li><a href="http://vrnear.me/" target="_blank">VR Near Me</a> - A website where people can find the most exciting virtual reality locations.</li>
                        <li><a href="https://kirkkohler.github.io/vrChicken/" target="_blank">vrChicken</a> - A Virtual Reality prototype with chicken <a href="https://ephtracy.github.io/" target="_blank">Voxel models</a> supported on mobile platforms using <a href="https://aframe.io/" target="_blank">A-Frame</a>, a WebVR framework.</li>
                        <img src="images/vrChicken.gif" style="max-width: 100%; height: auto;">
                    </ul>
                    <h2>Archived Projects</h2>
                    <ul>
                        <li><a href="http://www.meetup.com/Eastside-Virtual-Reality-Meetup/" target="_blank">Eastside Virtual Reality Meetup</a> - A meetup for VR enthusiasts Eastside of Seattle. Follow us on Twitter: <a href="https://twitter.com/esidevr" target="_blank">@esidevr</a>, <a href="https://www.youtube.com/channel/UCBUfVuqFaxoFNUgttW2kf6g" target="_blank">Youtube</a> and <a href="https://www.facebook.com/esidevr/" target="_blank">Facebook</a></li>
                        <li><a href="http://devpost.com/software/bimvar" target="_blank">BIMVAR</a> - At a Virtual Reality Hackathon, my team built a collaborative system allowing many users to analyze, and mark BIM clashes within a virtual space with head, hand tracking and voice support.</li>
                        <style>.embed-container { position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 80%; } .embed-container iframe, .embed-container object, .embed-container embed { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }</style><div class="embed-container"><iframe src="https://www.youtube.com/embed//S5yNC-MGN0U" frameborder="0" allowfullscreen=""></iframe></div>
                        <li><a href="http://outwestoutdoors.tv" target="_blank">Out West Outdoors</a> - A videography site exploring hunting and fishing in Northern California</li>
                        <li><a href="https://twit-vizual.herokuapp.com" target="_blank">Twit Vizual</a> - A "MEAN" stack application, hosted on Heroku, which provides a RESTful API returning results from Twitter’s streaming service to a web application and visualizes the data using D3.js</li>
                    </ul>
                </div>
            </div>
            <div class="row marketing" id="about">
                <div class="panel panel-default col-lg-12 transparent">
                    <h2>About</h2>
                    <p>I have been interested in technology since my early youth when my dad purchased a subscription to <a href="http://www.popsci.com/" target="_blank">Popular Science Magazine</a> for my brother and me.  I remember imagining how cool the world would be when scientists could make the machines and computers they were designing.  Fast forward a decade later, and I was building my first computer with an Intel Pentium III 500MHz Processor.  In 1996, I got the itch for coding by making fan websites for bands and starting an online magazine.  I recall how exciting it was to see my code trigger a song to play within a webpage for the first time.</p>
                    <p>A nerd was born.</p>
                    <p>I decided to pursue a Computer Science degree at California State University, Chico, where I continued to build and repair computers as part of the Information Technology Support staff. After graduating from college, I worked as a Software Engineer at Chevron, AT&T, and Comcast.  I now have the taste of developing and deploying applications to 30+ million users across the United States and am hungry to do more.</p>
                    <p>I have moved into Product Management from the role of Engineering Manager, and I love it!  I enjoy being hands-on technically with designing and coding and working toward a common vision with my team members.</p>
                    <p>When I am not coding or doing research, you can find me hanging out with my wife or out mountain biking, shooting photos, reading, or hunting for the perfect cup of coffee.</p>
                    <p>If you have an exciting start-up, project or role that you feel I would be interested in, feel free to contact me immediately through my <a href="http://www.linkedin.com/in/kirkkohler" target="_blank">LinkedIn</a> profile. Otherwise, follow me through my various social networks, such as <a href="https://twitter.com/kirkkohler" target="_blank">Twitter</a> or my <a href="https://medium.com/digital-cake" target="_blank" title="Kirk's Blog">blog</a>.</p>
                </div>
            </div>
            <div class="footer panel panel-default transparent">
                <p>&copy; <a href="http://kirkkohler.com">KirkKohler.com</a> 2016

                    <br> Built with ♥ from the following tools: 
                    <a href="http://yeoman.io/" target="_blank">Yeoman</a>, 
                    <a href="http://html5boilerplate.com/" target="_blank">HTML5 Boilerplate</a>, 
                    <a href="http://getbootstrap.com/" target="_blank">Bootstrap</a>, 
                    <a href="http://modernizr.com/" target="_blank">Modernizr</a>, &amp;
                    <a href="http://requirejs.org/" target="_blank">RequireJS</a> &amp; of course <a href="http://fontawesome.io" target="_blank">Font Awesome</a>.
                </p>    
            </div>

        </div>


        <!-- build:js scripts/vendor.js -->
        <!-- bower:js -->
        <script src="bower_components/jquery/jquery.js"></script>
        <!-- endbower -->
        <!-- endbuild -->

        <!-- Google Analytics: change UA-XXXXX-X to be your site's ID. -->
        <script>
            (function(b,o,i,l,e,r){b.GoogleAnalyticsObject=l;b[l]||(b[l]=
            function(){(b[l].q=b[l].q||[]).push(arguments)});b[l].l=+new Date;
            e=o.createElement(i);r=o.getElementsByTagName(i)[0];
            e.src='//www.google-analytics.com/analytics.js';
            r.parentNode.insertBefore(e,r)}(window,document,'script','ga'));
            ga('create','UA-34904642-1');ga('send','pageview');
        </script>

        <!-- build:js scripts/main.js -->
        <script data-main="scripts/main" src="bower_components/requirejs/require.js"></script>
        <!-- endbuild -->
</body>
</html>
