---
title: Projects
---
<link rel="stylesheet" href="../assets/css/research-style.css">
<div class="site-content">
   <div class="demo demo-1">
      <div class="project-list">
         <div class="project">
            <div class="project__card">
               <a href="google.com" class='project__image'><div><img src="http://unsplash.it/600/400?image=189" width=600 height=400 alt="fdfdsf"></div></a>
               <div class="project__detail">
                  <h2 class="project__title"><a href="#">Project Name</a></h2>
                  <small class="project__category"><a href="#">Photography</a></small>
               </div>
            </div>
         </div>
         <div class="project">
            <div class="project__card">
               <a href="" class="project__image"><img src="http://unsplash.it/600/400?image=189" width=600 height=400 alt=""></a>
               <div class="project__detail">
                  <h2 class="project__title"><a href="#">Project Name</a></h2>
                  <small class="project__category"><a href="#">Photography</a></small>
               </div>
            </div>
         </div>
         <div class="project">
            <div class="project__card">
               <a href="" class="project__image"><img src="http://unsplash.it/600/400?image=189" width=600 height=400 alt=""></a>
               <div class="project__detail">
                  <h2 class="project__title"><a href="#">Project Name</a></h2>
                  <small class="project__category"><a href="#">Photography</a></small>
               </div>
            </div>
         </div>
         <div class="project">
            <div class="project__card">
               <a href="" class="project__image"><img src="http://unsplash.it/600/400?image=189" width=600 height=400 alt=""></a>
               <div class="project__detail">
                  <h2 class="project__title"><a href="#">Project Name</a></h2>
                  <small class="project__category"><a href="#">Photography</a></small>
               </div>
            </div>
         </div>
      </div>
   </div>
</div>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.0/jquery.min.js"></script>
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
