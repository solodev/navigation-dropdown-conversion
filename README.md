# navigation-dropdown-conversion
On occasion, you may have a sidebar navigation that can present problems on mobile where a long list of navigation items isn’t ideal. With Bootstrap classes, however, you can convert that list into a convenient dropdown menu.

## Tutorial
For detailed instruction's, view Solodev's [How to Convert a Sidebar Navigation to Dropdown with Bootstrap](https://www.solodev.com/blog/web-design/how-to-convert-a-sidebar-navigation-to-dropdown-with-bootstrap.stml)

## Demo
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/cnz6bxaf/).

## HTML
The tutorial contains the following basic HTML markup.

```
 <div class="container">
   <div class="row">

     <article class="col-lg-8 content-page--text">
       <div class="row">
         <div class="col-12 col-centered">
           <h1 class="text-center p-5">The Cosmos Awaits</h1>
           <p class="mb-4">Rogue cosmos muse about Rig Veda concept of the number one hydrogen atoms.
             Brain is the seed of intelligence emerged into consciousness are creatures of the cosmos
             the only home we've ever known hearts of the stars corpus callosum.
             Something incredible is waiting to be known vastness is bearable only through love vanquish
             the impossible vanquish the impossible the carbon in our apple pies are creatures of the cosmos.</p>
           <p class="mb-4">Concept of the number one billions upon billions citizens of distant epochs stirred by starlight consciousness the only home
             we've ever known? With pretty stories for which there's little good evidence a still more glorious dawn awaits of brilliant
             syntheses Sea of Tranquility Rig Veda paroxysm of global death. The sky calls to us emerged into consciousness Apollonius of Perga
             courage of our questions extraordinary claims require extraordinary evidence hearts of the stars and billions upon billions
             upon billions upon billions upon billions upon billions upon billions.</p>
         </div>
       </div>
     </article>

     <aside class="sidebar col-lg-3 ml-auto">
       <p class="border-top pt-3 d-block d-lg-none"><strong>Navigate to:</strong></p>
       <select class="subMenuSelect form-control d-block d-lg-none mb-5" aria-label="Sidebar page navigation">
         <option value="">Select navigation option</option>
         <option value="#"><span>XP-1</span></option>
         <option value="#"><span class="subMenuHighlight">HAB-1</span></option>
         <option value="#"><span>ORBITER-1</span></option>
         <option value="#"><span>TALON-2</span></option>
         <option value="#"><span>LUNAR XPLORER</span></option>
       </select>
       <div id="subMenu" class="d-none d-lg-block">
         <ul>
           <li class="subMenu1">
             <a class="subMenu1" href="#"><span>XP-1</span></a>
           </li>
         </ul>
         <ul class="subMenuHighlight">
           <li class="subMenuHighlight" id="subMenuHighlight">
             <a class="subMenuHighlight" href="#"><span class="subMenuHighlight">HAB-1</span></a>
           </li>
         </ul>
         <ul>
           <li>
             <a class="subMenu1" href="#"><span>ORBITER-1</span></a>
           </li>
         </ul>
         <ul>
           <li>
             <a class="subMenu1" href="#"><span>TALON-2</span></a>
           </li>
         </ul>
         <ul>
           <li>
             <a class="subMenu1" href="#"><span>LUNAR XPLORER</span></a>
           </li>
         </ul>
       </div>
     </aside>

   </div><!-- row -->
 </div><!-- container -->
```

## CSS
All required CSS is contained with style.css

## External Resources
This tutorial includes the following third party resources.

```
<!-- Bootstrap CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
<script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
```