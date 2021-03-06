---
rss: false
layout: update
published: true

collection: updates
category: chrome
product: chrome
type: news
date: 2012-04-10

title: "Round-up of Web Browser Internals Resources"
description: ""
article:
  written_on: 2012-04-10
  updated_on: 2012-04-10
authors:
  - paulirish
tags:
  - internals
  - performance
permalink: /updates/2012/04/Round-up-of-Web-Browser-Internals-Resources
---
<style>
.da-thumbs {
	list-style: none;
	width: 690px;
	min-height: 600px;
	position: relative;
	margin: 20px auto;
	padding: 0;


}
.da-thumbs li {
	float: left;
	margin: 5px;
	background: #fff;
	padding: 8px;
	position: relative;
	box-shadow: 0 1px 3px rgba(0,0,0,0.1);
}
.da-thumbs li a,
.da-thumbs li a img {
	display: block;
	position: relative;
}
.da-thumbs li a {
	overflow: hidden;
}
.da-thumbs li a div {
	position: absolute;
	background: rgba(75,75,75,0.7);
	width: 100%;
	height: 100%;
}
.da-thumbs li a div.da-animate {
	-webkit-transition: all 0.3s ease;
	-moz-transition: all 0.3s ease-in-out;
	-o-transition: all 0.3s ease-in-out;
	-ms-transition: all 0.3s ease-in-out;
	transition: all 0.3s ease-in-out;
}
/* Initial state classes: */
.da-slideFromTop {
	left: 0px;
	top: -100%;
}
.da-slideFromBottom {
	left: 0px;
	top: 100%;
}
.da-slideFromLeft {
	top: 0px;
	left: -100%;
}
.da-slideFromRight {
	top: 0px;
	left: 100%;
}
/* Final state classes: */
.da-slideTop {
	top: 0px;
}
.da-slideLeft {
	left: 0px;
}
.da-thumbs li a div span {
	display: block;
	padding: 10px 0;
	margin: 25px 20px 20px 20px;
	font-weight: normal;
	color: rgba(255,255,255,0.9);
	text-shadow: 1px 1px 1px rgba(0,0,0,0.2);
	border-bottom: 1px solid rgba(255,255,255,0.5);
	box-shadow: 0 1px 0 rgba(0,0,0,0.1), 0 -10px 0 rgba(255,255,255,0.3);
	font-size: 20px;
   line-height: 1.2;
}


.da-thumbs li a img {
	width: 200px;
}


.da-thumbs li a img.big {
	width: 432px;
}


</style>

<p>In many cases, we treat web browsers as a black box. But as we gain a better understanding of how they work, we not only recognize where to make smart optimizations but also we push them farther. </p>

<p>The links below capture most of the resources that explain the innerworkings of web browsers. </p>
				<ul id="da-thumbs" class="da-thumbs" >


<li><a href="http://www.html5rocks.com/en/tutorials/internals/howbrowserswork/">
    <img src="http://beta.url2png.com/v6/P4EA9CF92E4F9C/daf350053347a0388a6f4d72ae3277d4/png/?url=http%3A%2F%2Fwww.html5rocks.com%2Fen%2Ftutorials%2Finternals%2Fhowbrowserswork%2F&viewport=1024x746&format=png&thumbnail_max_width=440" class=big>
    <div><span>How Browsers Work: Behind the scenes of modern web browsers, by Tali Garsiel</span></div>
  </a></li>







<li><a href="http://www.vineetgupta.com/2010/11/how-browsers-work-part-1-architecture/">
    <img src="http://beta.url2png.com/v6/P4EA9CF92E4F9C/7825d223b6a7848b44fcba68185d71fb/png/?url=http%3A%2F%2Fwww.vineetgupta.com%2F2010%2F11%2Fhow-browsers-work-part-1-architecture%2F&viewport=1024x746&format=png&thumbnail_max_width=240">
    <div><span>How Browsers Work – Architecture, by Vineet Gupta</span></div>
  </a></li>


  <li><a href="http://blog.mozilla.com/dmandelin/2011/06/16/know-your-engines-at-oreilly-velocity-2011/">
    <img src="http://beta.url2png.com/v6/P4EA9CF92E4F9C/323fe44ef014c5da2e009e389b95cf9f/png/?url=http%3A%2F%2Fblog.mozilla.com%2Fdmandelin%2F2011%2F06%2F16%2Fknow-your-engines-at-oreilly-velocity-2011%2F&viewport=1024x746&format=png&thumbnail_max_width=240">
    <div><span>Know Your JavaScript Engines, by David Mandelin</span></div>
  </a></li>



  <li><a href="http://www.youtube.com/watch?v=XAqIpGU8ZZk">
    <img src="http://beta.url2png.com/v6/P4EA9CF92E4F9C/d0472464d27d25fdef6d77deda654d89/png/?url=http%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DXAqIpGU8ZZk&viewport=1024x746&format=png&thumbnail_max_width=240">
    <div><span>From Console to Chrome, by Lilli Thompson</span></div>
  </a></li>


<li style="float:right"><a href="http://dbaron.org/talks/2012-03-11-sxsw/master.xhtml">
    <img src="http://beta.url2png.com/v6/P4EA9CF92E4F9C/d685e329b34e2899e78ff5b6de339604/png/?url=http%3A%2F%2Fdbaron.org%2Ftalks%2F2012-03-11-sxsw%2Fmaster.xhtml&viewport=1024x746&format=png&thumbnail_max_width=440" class=big>
    <div><span>Fast CSS: How Browsers Lay Out Web Pages, by David Baron</span></div>
  </a></li>


  <li><a href="http://dayofjs.com/videos/22158462/web-browsers_alex-russel">
    <img src="http://beta.url2png.com/v6/P4EA9CF92E4F9C/584d9eb36c18ecef9a376ce4ec9ea567/png/?url=http%3A%2F%2Fdayofjs.com%2Fvideos%2F22158462%2Fweb-browsers_alex-russel&viewport=1024x746&format=png&thumbnail_max_width=240">
   <div><span> What Browsers <em>Really</em> Think of your App, by Alex Russell</span></div>
  </a></li>


  <li style="clear:both"><a href="http://www.youtube.com/watch?v=a2_6bGNZ7bA">
    <img src="http://beta.url2png.com/v6/P4EA9CF92E4F9C/9cdf9d13ee882ef233457483f251e345/png/?url=http%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3Da2_6bGNZ7bA&viewport=1024x746&format=png&thumbnail_max_width=240">
    <div><span>Faster HTML and CSS: Layout Eng&shy;ine Internals for Web Dev&shy;elop&shy;ers, by David Baron</span></div>
  </a></li>

  <li><a href="http://stackoverflow.com/questions/5797014/css-selectors-parsed-right-to-left-why/5813672#5813672">
    <img src="http://beta.url2png.com/v6/P4EA9CF92E4F9C/8c411595aeb356e12f7897b370f58842/png/?url=http%3A%2F%2Fstackoverflow.com%2Fquestions%2F5797014%2Fcss-selectors-parsed-right-to-left-why%2F5813672%235813672&viewport=1024x746&format=png&thumbnail_max_width=240">
    <div><span>CSS Selectors parsed right to left. Why?, by Boris Zbarsky</span></div>
  </a></li>



  <li><a href="http://www.webkit.org/blog/114/webcore-rendering-i-the-basics/">
    <img src="http://beta.url2png.com/v6/P4EA9CF92E4F9C/b1b007734c4b31681da3953705d71eb1/png/?url=http%3A%2F%2Fwww.webkit.org%2Fblog%2F114%2Fwebcore-rendering-i-the-basics%2F&viewport=1024x746&format=png&thumbnail_max_width=240">
    <div><span>WebCore Rendering I – The Basics</span></div>
  </a></li>

<li><a href="http://vimeo.com/32364192">
    <img src="http://beta.url2png.com/v6/P4EA9CF92E4F9C/475edf4e5e381e40bdb5ba346357739a/png/?url=http%3A%2F%2Fvimeo.com%2F32364192&viewport=1024x746&format=png&thumbnail_max_width=440" class=big>
    <div><span>Life Of A Button Element, by Alex Russell</span></div>
  </a></li>


  <li><a href="http://paulirish.com/2011/dom-html5-css3-performance/">
    <img src="http://beta.url2png.com/v6/P4EA9CF92E4F9C/0a6e41e2a110474975e0250de4d7c419/png/?url=http%3A%2F%2Fpaulirish.com%2F2011%2Fdom-html5-css3-performance%2F&viewport=1024x746&format=png&thumbnail_max_width=240">
    <div><span>DOM, HTML5, &amp; CSS3 Performance, by Paul Irish</span></div>
  </a></li>

  <li><a href="http://gent.ilcore.com/2011/05/how-web-page-loads.html">
    <img src="http://beta.url2png.com/v6/P4EA9CF92E4F9C/9bc949fa4ad33442c1e6adf1620b3990/png/?url=http%3A%2F%2Fgent.ilcore.com%2F2011%2F05%2Fhow-web-page-loads.html&viewport=1024x746&format=png&thumbnail_max_width=240">
    <div><span>How A Web Page Loads, by Tony Gentilcore</span></div>
  </a></li>

  <li><a href="http://paulirish.com/2011/primitives-html5-video/">
    <img src="http://beta.url2png.com/v6/P4EA9CF92E4F9C/4dadb33cc36dd6331346ee982a8591be/png/?url=http%3A%2F%2Fpaulirish.com%2F2011%2Fprimitives-html5-video%2F&viewport=1024x746&format=png&thumbnail_max_width=240">
    <div><span>The Fund&shy;amentals, Prim&shy;itives and His&shy;tory of HTML5, by Paul Irish</span></div>
  </a></li>



  <li><a href="https://vimeo.com/16241085">
    <img src="http://beta.url2png.com/v6/P4EA9CF92E4F9C/50d2efdef470be7fb44133bc0c7000f1/png/?url=https%3A%2F%2Fvimeo.com%2F16241085&viewport=1024x746&format=png&thumbnail_max_width=240">
    <div><span>High Performance JavaScript, by Nicholas Zakas</span></div>
  </a></li>


				</ul>
		
<p style="clear:both">
<a href="http://tympanus.net/codrops/2012/04/09/direction-aware-hover-effect-with-css3-and-jquery/">Thanks Codrops</a> for the fanciness. Thank you <a href="https://twitter.com/#!/rik24d">Anthony Ricaud</a> for the <a href="http://blogmarks.net/user/rik/marks/tag/navigateur-marche">resources</a>. 

<p>
If you know of other browser internals posts to capture, link them in the comments!
</p>


		<script>
		(function(b,c){b.HoverDir=function(d,e){this.$el=b(e);this._init(d)};b.HoverDir.defaults={hoverDelay:0,reverse:false};b.HoverDir.prototype={_init:function(d){this.options=b.extend(true,{},b.HoverDir.defaults,d);this._loadEvents()},_loadEvents:function(){var d=this;this.$el.on("mouseenter.hoverdir, mouseleave.hoverdir",function(i){var g=b(this),h=i.type,e=g.find("div"),j=d._getDir(g,{x:i.pageX,y:i.pageY}),f=d._getClasses(j);e.removeClass();if(h==="mouseenter"){e.hide().addClass(f.from);clearTimeout(d.tmhover);d.tmhover=setTimeout(function(){e.show(0,function(){b(this).addClass("da-animate").addClass(f.to)})},d.options.hoverDelay)}else{e.addClass("da-animate");clearTimeout(d.tmhover);e.addClass(f.from)}})},_getDir:function(f,j){var e=f.width(),g=f.height(),d=(j.x-f.offset().left-(e/2))*(e>g?(g/e):1),k=(j.y-f.offset().top-(g/2))*(g>e?(e/g):1),i=Math.round((((Math.atan2(k,d)*(180/Math.PI))+180)/90)+3)%4;return i},_getClasses:function(e){var f,d;switch(e){case 0:(!this.options.reverse)?f="da-slideFromTop":f="da-slideFromBottom";d="da-slideTop";break;case 1:(!this.options.reverse)?f="da-slideFromRight":f="da-slideFromLeft";d="da-slideLeft";break;case 2:(!this.options.reverse)?f="da-slideFromBottom":f="da-slideFromTop";d="da-slideTop";break;case 3:(!this.options.reverse)?f="da-slideFromLeft":f="da-slideFromRight";d="da-slideLeft";break}return{from:f,to:d}}};var a=function(d){if(this.console){console.error(d)}};b.fn.hoverdir=function(e){if(typeof e==="string"){var d=Array.prototype.slice.call(arguments,1);this.each(function(){var f=b.data(this,"hoverdir");if(!f){a("cannot call methods on hoverdir prior to initialization; attempted to call method '"+e+"'");return}if(!b.isFunction(f[e])||e.charAt(0)==="_"){a("no such method '"+e+"' for hoverdir instance");return}f[e].apply(f,d)})}else{this.each(function(){var f=b.data(this,"hoverdir");if(!f){b.data(this,"hoverdir",new b.HoverDir(e,this))}})}return this}})(jQuery);
		</script>

		<script type="text/javascript">
			$(function() {
				$('#da-thumbs > li').hoverdir();
				$('a div').addClass('da-slideFromLeft da-slideLeft da-animate')
			});
			$(window).load(function(){
				setTimeout(function(){
					$('a div').removeClass(' da-slideLeft');
				}, 1700);
			})
		</script>