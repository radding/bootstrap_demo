#Links

##CDN Links
*Copy and Paste these into your skeleton*
###CSS
`<link rel="stylesheet" href=“https://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/css/bootstrap.min.css">`
###JS
`<script src=“https://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/js/bootstrap.min.js"></script>`

##Reference 
http://getbootstrap.com/components/

#Code Snipets

##Nav Bar
    
    <nav class="navbar navbar-default">
        <div class="container-fluid">
            <div class="navbar-header">
                <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#nav_content" aria-expanded="false">
                <span class="sr-only">Toggle navigation</span>
                <span class="icon-bar"></span>
                <span class="icon-bar"></span>
                <span class="icon-bar"></span>
                </button>
                <a class="navbar-brand" href="#">FirstInitial. LastName Here</a>
            </div>
            <div class="collapse navbar-collapse" id="nav_content">
                <ul class="nav navbar-nav">
                    <li class="active"> <a href="#about">About Me</a></li>
                    <li><a href="#projects"> Projects &amp; Experience</a></li>
                    <li class="dropdown">
                        <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Contact Me<span class="caret"></span></a>
                        <ul class="dropdown-menu">
                            <li><a href="#contact">Email</a></li>
                            <li><a href="#contact">Website</a></li>
                            <li><a href="#contact">GitHub</a></li>
                        </ul>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

##About Section

    <div class="container-fluid desktop" id="about">
        <div class="row">
            <div class="col-md-2 hidden-sm"></div>
            <div class="col-md-4">
                <img class="img-responsive img-circle" src="me.GIF" alt="me" height="100%" width="100%" style="padding-top: 144px"/>
            </div>
            <div class="col-md-4">
                <center>
                    <h1>About Me</h1>
                    <p>My Name is Your name here. I do web development and I am cool! I'm really just trying to fill a lot of text so this looks cool!</p>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque pretium velit metus, non interdum dolor vestibulum fringilla. Morbi gravida condimentum consequat. Quisque a nunc nunc. Duis maximus rhoncus risus, vitae volutpat felis suscipit ut. Aenean sed diam id nibh congue mollis. Cras orci urna, tincidunt sed diam ut, maximus placerat est. Nunc sed maximus lacus, at dapibus lacus. Vivamus condimentum nunc enim, et ultricies metus elementum sit amet. Curabitur ac neque elementum, posuere justo non, convallis metus. Sed faucibus, mauris sit amet consequat ullamcorper, eros felis ullamcorper eros, ut mollis erat libero vel ligula. Morbi et vulputate dui. Phasellus cursus pulvinar turpis, nec tincidunt mi feugiat quis. Aliquam erat volutpat. Fusce pretium, metus ac volutpat sodales, justo nibh placerat lorem, eget auctor nibh nibh ut dui.</p>
                    <p>I am also making this site as an example for bootstrap</p>
                </center>
            </div>
            <div class="col-md-2 hidden-sm"></div>
        </div>
    </div>

##Projects

    <div class="container-fluid desktop" id="projects">
        <div class="row">
            <div class="col-md-12">
                <center style="padding-bottom:50px"><h1>Projects &amp; Experience</h1></center>
                <div class="row">  <!-- Add one of these for every three items -->
                    <div class="col-md-4">
                        <h3>Project Name Here</h3>
                        <p>Project description here.</p>
                    </div>
                     <div class="col-md-4">
                        <h3>Project Name Here</h3>
                        <p>Project description here.</p>
                    </div>  
                    <div class="col-md-4">
                        <h3>Project Name Here</h3>
                        <p>Project description here.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

