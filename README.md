# portfolio
Final project 
I started the process with adding a files and folders in the currect order. After I resized all my images to be responsive across all decives.
I started by creating a html file for the home, about, and the contact page; also, I added the css file. 
After adding the files I went ot the bootstrap page and I copyed the quick start `code` from the bootstrap page, and I also I add the <link> `code` to link the css file with the html files and I did this to all the html files. After I add the Javascrip `code` <!--- <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.7/dist/umd/popper.min.js" integrity="sha384-zYPOMqeu1DAVkHiLqWBUTcbYfZ8osu1Nd6Z89ify25QV9guujx43ITvfi12/QExE" crossorigin="anonymous"></script> --->
<!----
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.min.js" integrity="sha384-Y4oOpwW3duJdCWv5ly8SCFYWqFDsfob/3GkgExXKV4idmbt98QcxXYs9UoXAB7BZ" crossorigin="anonymous"></script> ----->

I started coding the page with adding the <<header>> tag the <<mian>> tag and the <<footer>> tag

<!----------------- Header -------------------->
 Items on he nav bar unordered list: - first item the About page <<a>> link[title] (contact.html), - second item is the contact page <<a>> link [title] (about.html)

I copyed the the nav bar `code` with offcanves pop up on smaller screen, and I used the same `code` across all three pages.

The callenge I faced during writing the `code` for the nav bar is to add a header image on screens bigger then 800px. I added the <<img>> tag inside a <<div>> with a class of (d-lg-lock). Also, adding the right colour to the offcanves bar it was hard becasue I needed to targget the right <<div>> to display a different color on a middle and larger screen, I have done that by adding a background-color in `css`.


I have used two image size for small-medium and large screen, using the <<picture>> tag with screst element. 

<!--====================== for the about page===========================----->
For the about page I add the same `code` for the nav bar; however, the only different thing is it does not have a header image on a bigger image size. 

For the <<mian>> section of the about page I had to add two smiller slightly different `code`  because I needed to display two different stylies, on for the middile where I display a picuter of myselif inside the frame with `border-radius of 50rem` to give it the round shape I added the class of `d-block d-sm-none` to only display that style on the mobile size only. 


<!-----------------------------------===================For the contact page    ========================------------------------------------------------------------------->

I used the form code using bootstrap the code `<section class="contact m-5">
          <div class="container text-center"> 
              <img class="contact-us-image" src="images/final-edit-Feb-23-300_x_300.jpg" alt="image of Manar"> 
          </div>
              <h2 class="display-3 text-center fw-bold">Contact</h2>
          <div class="mb-3 fw-bold fs-2">
                <label class="form-label">First Name</label>
                <input type="text" class="form-control" placeholder="First name" aria-label="First name">
          </div>
            <div class="mb-3 text fw-bold fs-2">
                <label for="exampleFormControlInput1" class="form-label">Email</label>
                <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="name@example.com">
          </div>
          <div class="mb-3 fw-bold fs-2">
                <label for="exampleFormControlTextarea1" class="form-label">Message</label>
                <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
          </div>
          <div class="contact-us fw-bold">
                <button type="button" class="btn btn-secondary btn-lg m-4 fw-bold fs-2">Contact Us</button>
          </div>
          </div>
          </section>`

          added social media links in the bottom right of the page. 