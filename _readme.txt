CHALLENGES

I had 3 major challenges during the development of my web portfolio.

The first challenge I faced was how to change the layout of the contents in 'Services' page. The images were too large and overlapped even though I specified 6 columns for each one using a class of ".col-md-6" in the <div> containing the contents. However, I was able to solve this by adding a class of ".col-12" to each of the <img> tags. Please find the code below:

 <div class="container">
        <div class="row">
            <div class="col-md-6 mt-5">
                <a class="text-decoration-none text-dark" href="#">
                    <h2 class="text-center">Photography</h2>
                </a>
                <img class="col-12" src="wp-images/me.jpg" alt="image">
            </div>
            <div class="col-md-6 mt-5">
                <a class="text-decoration-none text-dark" href="#">
                    <h2 class="text-center">Videography</h2>
                </a>
                <img class="col-12" src="wp-images/woman-659350_1920.jpg" alt="image">
            </div>
        </div>
    </div>


The second challenge I had was the usage of a toggler for mobile view. The toggler appeared but it would not drop down the menu and I could not figure out why. Unfortunately, I was unable to overcome this.

Please find the code below:

<div class="collapse navbar-collapse" id="MobileTog">
        <div class="navbar-nav ml-auto">
            <a class="nav-link active" href="#">Home</a>
            <a class="nav-link" href="#">About</a>
            <a class="nav-link" href="#">Services</a>
            <a class="nav-link" href="#">Contact</a>
        </div>
    </div>
    <button class="navbar-toggler" data-target="#MobileTog" data-toggle="collapse">
        <span class="navbar-toggler-icon" ></span>

    </button>
</nav>

The third challenge which I was also unable to overcome was not being able to make the image in 'Contact' page disappear in mobile view as it is in the mockup.



ASSETS & RESOURCES USED

Framework: Bootstrap
Fonts: Google Fonts
Images (except for the image for 'Photography' which is mine): https://pixabay.com/


The one thing that I learnt by creating my web portfolio is that the design of a website may look good, but developing the website exactly the way it is designed may not be practicable.





