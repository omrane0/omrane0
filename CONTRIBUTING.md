<!DOCTYPE html>
<html>
<head>
    <title>Tabbed Content</title>
    <script type="text/javascript">(function(){var g=function(a){if(a&&a.stopPropagation)a.stopPropagation();else window.event.cancelBubble=true;var b=a?a:window.event;b.preventDefault&&b.preventDefault()},d=function(a,c,b){if(a.addEventListener)a.addEventListener(c,b,false);else a.attachEvent&&a.attachEvent("on"+c,b)},a=function(c,a){var b=new RegExp("(^| )"+a+"( |$)");return b.test(c.className)?true:false},j=function(b,c,d){if(!a(b,c))if(b.className=="")b.className=c;else if(d)b.className=c+" "+b.className;else b.className+=" "+c},h=function(a,b){var c=new RegExp("(^| )"+b+"( |$)");a.className=a.className.replace(c,"$1");a.className=a.className.replace(/ $/,"")},e=function(){var b=window.location.pathname;if(b.indexOf("/")!=-1)b=b.split("/");var a=b[b.length-1]||"root";if(a.indexOf(".")!=-1)a=a.substring(0,a.indexOf("."));if(a>20)a=a.substring(a.length-19);return a},c="mi"+e(),b=function(b,a){this.g(b,a)};b.prototype={h:function(){var b=new RegExp(c+this.a+"=(\\d+)"),a=document.cookie.match(b);return a?a[1]:this.i()},i:function(){for(var b=0,c=this.b.length;b<c;b++)if(a(this.b[b].parentNode,"selected"))return b;return 0},j:function(b,d){var c=document.getElementById(b.TargetId);if(!c)return;this.l(c);for(var a=0;a<this.b.length;a++)if(this.b[a]==b){j(b.parentNode,"selected");d&&this.d&&this.k(this.a,a)}else h(this.b[a].parentNode,"selected")},k:function(a,b){document.cookie=c+a+"="+b+"; path=/"},l:function(b){for(var a=0;a<this.c.length;a++)this.c[a].style.display=this.c[a].id==b.id?"block":"none"},m:function(){this.c=[];for(var c=this,a=0;a<this.b.length;a++){var b=document.getElementById(this.b[a].TargetId);if(b){this.c.push(b);d(this.b[a],"click",function(b){var a=this;if(a===window)a=window.event.srcElement;c.j(a,1);g(b);return false})}}},g:function(f,h){this.a=h;this.b=[];for(var e=f.getElementsByTagName("a"),i=/#([^?]+)/,a,b,c=0;c<e.length;c++){b=e[c];a=b.getAttribute("href");if(a.indexOf("#")==-1)continue;else{var d=a.match(i);if(d){a=d[1];b.TargetId=a;this.b.push(b)}else continue}}var g=f.getAttribute("data-persist")||"";this.d=g.toLowerCase()=="true"?1:0;this.m();this.n()},n:function(){var a=this.d?parseInt(this.h()):this.i();if(a>=this.b.length)a=0;this.j(this.b[a],0)}};var k=[],i=function(e){var b=false;function a(){if(b)return;b=true;setTimeout(e,4)}if(document.addEventListener)document.addEventListener("DOMContentLoaded",a,false);else if(document.attachEvent){try{var f=window.frameElement!=null}catch(g){}if(document.documentElement.doScroll&&!f){function c(){if(b)return;try{document.documentElement.doScroll("left");a()}catch(d){setTimeout(c,10)}}c()}document.attachEvent("onreadystatechange",function(){document.readyState==="complete"&&a()})}d(window,"load",a)},f=function(){for(var d=document.getElementsByTagName("ul"),c=0,e=d.length;c<e;c++)a(d[c],"tabs")&&k.push(new b(d[c],c))};i(f);return{}})()</script>

<style>
#tabs {
    width: 800px;
    margin: 0 auto;
    font-family: Arial;
    font-size: 9pt;
   }
   .both {
  border: 1px solid black;
  clear: both;
}
ul.tabs
{
    padding: 7px 0;
    margin:0;
    list-style-type: none;
    text-align: left;
    clear: both;
}
ul.tabs li
{
    display: inline;
    margin: 0;
    margin-right:3px; /*distance between tabs*/
}
ul.tabs li a
{
    text-decoration: none;
    position: relative;
    padding: 7px 16px;
    border: 1px solid #CCC;
    border-bottom-color:#B7B7B7;
    color: rgb(11,63,113);
    outline:none;
    background: rgb(223,223,223);
    clear: both;
}

ul.tabs li a:visited
{
    color: #000;
}
ul.tabs li a:hover
{
    border: 1px solid #B7B7B7;
}
ul.tabs li.selected a, ul.tabs li.selected a:hover
{
    position: relative;
    top: 0px;
    font-weight:bold;
    background: white;
    border: 1px solid #B7B7B7;
    border-bottom-color: white;
    clear: both;
}
ul.tabs li.selected a:hover
{
    text-decoration: none;
}
div.tabcontents
{
    border: 1px solid #B7B7B7;
    padding: 30px;
    background-color:#FFF;
    clear: both;
}
 </style>
</head>
<body>
    <div id="tabs">
        <ul class="tabs">
            <li><a href="#view1"> Thème </a></li>
            <li><a href="#view2"> Chapitre </a></li>
        </ul>
        <div class="tabcontents">
            <div id="view1">
                 <b>Domaines du socle</b>
                <p>Domaine 5
Se repérer dans l’espace et dans le temps
Domaine 2
Se repérer dans un système d’information et interroger la pertinence des informations
trouvées.
Domaine 1
Développer les capacités d’expression et de communication</p>
  <b>Compétences travaillées</b> 
<p> « pratiquer différents langages » 
 « s’informer dans le monde du numérique ». 
  distinguer les divers niveaux de langage et d’analyse ainsi que les divers points de vue, ce qui relève de la compétence « analyser et comprendre un document ».</p>
              
            </div>
            <div id="view2">
                <b> Mise en oeuvre </b>
                <p>Une crise diplomatique et militaire entraîne la Première Guerre mondiale qui constitue en elle-même une crise de l’Europe, marquée par un déchaînement de violence auquel fait écho la violence institutionnalisée et systématisée des régimes totalitaires.
Il convient de mettre en place une progression chronologique continue.</p>       
              <p>Le programme d'histoire-géographie Cycle 3 et cycle 4 a été publié au: Bulletin officiel spécial n° 11 du 26 novembre 2015. </p>            
   <br/>  
   <br>
   <br>
            </div>
        </div>
    </div>
</body>
</html>

