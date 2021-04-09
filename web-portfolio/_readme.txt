
My major challenge was making the images fit the 12 columns without making them too big. The images in the mockup take all 12 columns and looked fine, but when I gave them 12 columns when building the website, they were just too big and I had to reduce the number of columns allocated to each image.

The other challenge I had was giving the contact form a dark background and making it fit the form without shrinking it.

One major challenge that I had was how to change the layout of the contents in 'Services' page. The images were too large and overlapped even though I specified 6 columns for each one using a class of ".col-md-6" in the <div> containing the contents. I was able to solve this by adding a class of ".col-12" to the <img> tags.

 <div class="container">
        <div class="row">
            <div class="col-md-6 mt-5">
                <a class="text-decoration-none text-dark" href="#">
                    <h2 class="text-center">Photography</h2>
                </a>
                <img src="wp-images/me.jpg" alt="image">
            </div>
            <div class="col-md-6 mt-5">
                <a class="text-decoration-none text-dark" href="#">
                    <h2 class="text-center">Videography</h2>
                </a>
                <img src="wp-images/woman-659350_1920.jpg" alt="image">
            </div>
        </div>
    </div>

Framework: Bootstrap
Fonts: Google Fonts
Images (except for the image for 'Photography' which is mine): https://pixabay.com/




