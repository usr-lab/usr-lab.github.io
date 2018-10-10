---
title: Research
---
<link rel="stylesheet" href="../assets/css/research-style.css">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.1/jquery.min.js"></script>
<script src="../assets/js/plugins/jquery.hover3d.js" ></script>
<script>
   $(document).ready(function(){
   	$(".project").hover3d({
   		selector: ".project__card"
   	});
   
   	$(".movie").hover3d({
   		selector: ".movie__card",
   		shine: true,
   		sensitivity: 20,
   	});
   });
   
</script>
<div class="site-content">
   <div class="demo demo-1">
      <div class="project-list">
         <div class="project">
            <div class="project__card">
               <a href="www.google.com" class="project__image"><img src="../images/research-modeling.jpg"></a>
			   <!--<a href="google.com" class='project__image'>-->
               <div class="project__detail">
                  <small class="project__title"><a href="#">User modelling for personalised and co-adaptive human-robot interaction</a></small>
                  
               </div>
            </div>
         </div>
         <div class="project">
            <div class="project__card">
               <a href="" class="project__image"><img src="../images/research-synergies.jpg"></a>
               <div class="project__detail">
                  <h3 class="project__title"><a href="#">Synergies between robot appearance, behavior and quality of the interaction</a></h3>
                  <small class="project__category"><a href="#">Photography</a></small>
               </div>
            </div>
         </div>
         <div class="project">
            <div class="project__card">
               <a href="" class="project__image"><img src="../images/research-social.jpg"></a>
               <div class="project__detail">
                  <h3 class="project__title"><a href="#">Social learning</a></h3>
                  <small class="project__category"><a href="#">Photography</a></small>
               </div>
            </div>
         </div>
         <div class="project">
            <div class="project__card">
               <a href="" class="project__image"><img src="../images/research-education.jpg"></a>
               <div class="project__detail">
                  <h3 class="project__title"><a href="#">Educational robots</a></h3>
                  <small class="project__category"><a href="#">Photography</a></small>
               </div>
            </div>
         </div>
      </div>
   </div>
</div>

<script>window.jQuery || document.write('<script src="js/vendor/jquery-1.12.1.min.js"><\\/script>')</script>
<!-- Place this tag right after the last button or just before your close body tag. -->
<script async defer id="github-bjs" src="https://buttons.github.io/buttons.js"></script>
<script>window.twttr = (function(d, s, id) {
   var js, fjs = d.getElementsByTagName(s)[0],
     t = window.twttr || {};
   if (d.getElementById(id)) return t;
   js = d.createElement(s);
   js.id = id;
   js.src = "https://platform.twitter.com/widgets.js";
   fjs.parentNode.insertBefore(js, fjs);
   
   t._e = [];
   t.ready = function(f) {
     t._e.push(f);
   };
   
   return t;
   }(document, "script", "twitter-wjs"));
</script>


