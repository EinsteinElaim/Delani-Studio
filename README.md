# DELANI STUDIO WEBSITE

# 22/2/2020

# Description
This is a web app for  Delani studio. It's comprised of a welcome note on opening the site, an About Us section that follows it that includes descriptions of Delani Studio, what they do at Delani Studio and how they do it briefly.

# Behaviour Driven Development
On opening the site, the user gets an interactive layout to the site.
The user can check out the about us section rght after the welcome section for brief details about Delani Studio and what they do there.
After the About Us section, the user will see the Services section which is comprised of brief descriptions of the order of how Delani Studio's team goes about understanding the product vision of a contract before they act on it.
Then they hold a scoping session whose outcome is a proposal or high-level statement of work.
Finally, based on your requirements, Delani Studio's team can provide a complete offering or just the pieces you need for the project.




                  
                          s for changes as business requirements evolve.
                            </p>
                        </div>
                    </div>
                </div>
```
then add the following Javascript to make it function as wanted, using the classes that were assigned above.

```
  $("div#design").click(function() {
      $("div#content").toggle();
      $("div#design").toggle();
    });
    $("div#content").click(function() {
      $("div#content").toggle();
      $("div#design").toggle();
    });
    $("div#dev").click(function() {
      $("div#dev-content").toggle();
      $("div#dev").toggle();
    });
    $("div#dev-content").click(function() {
      $("div#dev-content").toggle();
      $("div#dev").toggle();
    });
    $("div#product").click(function() {
      $("div#prod-content").toggle();
      $("div#product").toggle();
    });
    $("div#prod-content").click(function() {
      $("div#prod-content").toggle();
     $("div#product").toggle();
    });
```

### Portfolio
In the portfolio section they where eight different portfolios.first thing to do is place them in the the following classes;
```
<div class="container">
                    <div class="row">
```
Then place each portfolio inside it's own column class so that we will be able to edit each portfolio individually.

```
<div id="photo1">
                                <img src="IP3-master/assets/portfolio/work4.jpg" class="img-responsive" width="100%">
                            </div>
                            <div id="text1" class="fade"><p>Black theme</p></div>
                        </div>
```
To add the hover effect when the mouse is ontop of on each portfolio, we add the following javascript.

```
 $("#col-1").hover(function() {
      $("#text1").fadeTo("slow",1);
      $("#photo1").fadeTo("slow",0.4);
      },function() {
        $("#text1").fadeTo("slow",0);
        $("#photo1").fadeTo("slow",1);
      });
```

### The Footer
The final part of the page is to name and the year it was published. 
```
 <div class="end">
                <p>DELANI STUDIO</p>
                <P>2020</P>
            </div>
```
### Known Bugs
If you find any issues in the code feel free to [click here](https://neema-bmb.github.io/Delani/)

### Technologies Used
I used:
HTML, Bootstrap, CSS, jQuery & Javascript.

### Contact me on: neemashiramba@gmail.com
I encourage anyone who has any contribution to make to this code to improve it do so. 
Live link:https://neema-bmb.github.io/Delani/


### License
App is licenced by [MIT.licensing](LICENCE.txt)
