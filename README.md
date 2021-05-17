- 👋 Hi, I’m @modest12345
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
modest12345/modest12345 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html><!--[if IE 8]>    <html class="ie8" lang="en-GB"> <![endif]--><!--[if IE 9]>    <html class="ie9" lang="en-GB"> <![endif]--><!--[if (gt IE 9)|!(IE)] lang="en-GB"><![endif]--><html lang="en-GB"><!-- Global site tag (gtag.js) - Google Analytics --><head><meta charset="utf-8"/>
<script data-ezscrex='false' data-cfasync='false' data-pagespeed-no-defer>var __ez=__ez||{};__ez.stms=Date.now();__ez.evt={};__ez.script={};__ez.ck=__ez.ck||{};__ez.template={};__ez.template.isOrig=true;__ez.queue=(function(){var count=0,incr=0,items=[],timeDelayFired=false,hpItems=[],lpItems=[],allowLoad=true;var obj={func:function(name,funcName,parameters,isBlock,blockedBy,deleteWhenComplete,proceedIfError){var self=this;this.name=name;this.funcName=funcName;this.parameters=parameters===null?null:(parameters instanceof Array)?parameters:[parameters];this.isBlock=isBlock;this.blockedBy=blockedBy;this.deleteWhenComplete=deleteWhenComplete;this.isError=false;this.isComplete=false;this.isInitialized=false;this.proceedIfError=proceedIfError;this.isTimeDelay=false;this.process=function(){log("... func = "+name);self.isInitialized=true;self.isComplete=true;log("... func.apply: "+name);var funcs=self.funcName.split('.');var func=null;if(funcs.length>3){}else if(funcs.length===3){func=window[funcs[0]][funcs[1]][funcs[2]];}else if(funcs.length===2){func=window[funcs[0]][funcs[1]];}else{func=window[self.funcName];}
if(typeof func!=='undefined'&&func!==null){func.apply(null,this.parameters);}
if(self.deleteWhenComplete===true)delete items[name];if(self.isBlock===true){log("----- F'D: "+self.name);processAll();}}},file:function(name,path,isBlock,blockedBy,async,defer,proceedIfError){var self=this;this.name=name;this.path=path;this.async=async;this.defer=defer;this.isBlock=isBlock;this.blockedBy=blockedBy;this.isInitialized=false;this.isError=false;this.isComplete=false;this.proceedIfError=proceedIfError;this.isTimeDelay=false;this.process=function(){self.isInitialized=true;log("... file = "+name);var scr=document.createElement('script');scr.src=path;if(async===true)scr.async=true;else if(defer===true)scr.defer=true;scr.onerror=function(){log("----- ERR'D: "+self.name);self.isError=true;if(self.isBlock===true){processAll();}};scr.onreadystatechange=scr.onload=function(){var state=scr.readyState;log("----- F'D: "+self.name);if((!state||/loaded|complete/.test(state))){self.isComplete=true;if(self.isBlock===true){processAll();}}};document.getElementsByTagName('head')[0].appendChild(scr);}},fileLoaded:function(name,isComplete){this.name=name;this.path="";this.async=false;this.defer=false;this.isBlock=false;this.blockedBy=[];this.isInitialized=true;this.isError=false;this.isComplete=isComplete;this.proceedIfError=false;this.isTimeDelay=false;this.process=function(){};}};function init(){window.addEventListener("load",function(){setTimeout(function(){timeDelayFired=true;log('TDELAY -----');processAll();},5000);},false);}
function addFile(name,path,isBlock,blockedBy,async,defer,proceedIfError,priority){var item=new obj.file(name,path,isBlock,blockedBy,async,defer,proceedIfError);if(priority===true){hpItems[name]=item}else{lpItems[name]=item}
items[name]=item;checkIfBlocked(item);}
function setallowLoad(settobool){allowLoad=settobool}
function addFunc(name,func,parameters,isBlock,blockedBy,autoInc,deleteWhenComplete,proceedIfError,priority){if(autoInc===true)name=name+"_"+incr++;var item=new obj.func(name,func,parameters,isBlock,blockedBy,deleteWhenComplete,proceedIfError);if(priority===true){hpItems[name]=item}else{lpItems[name]=item}
items[name]=item;checkIfBlocked(item);}
function addTimeDelayFile(name,path){var item=new obj.file(name,path,false,[],false,false,true);item.isTimeDelay=true;log(name+' ... '+' FILE! TDELAY');lpItems[name]=item;items[name]=item;checkIfBlocked(item);}
function addTimeDelayFunc(name,func,parameters){var item=new obj.func(name,func,parameters,false,[],true,true);item.isTimeDelay=true;log(name+' ... '+' FUNCTION! TDELAY');lpItems[name]=item;items[name]=item;checkIfBlocked(item);}
function checkIfBlocked(item){if(isBlocked(item)===true||allowLoad==false)return;item.process();}
function isBlocked(item){if(item.isTimeDelay===true&&timeDelayFired===false){log(item.name+" blocked = TIME DELAY!");return true;}
if(item.blockedBy instanceof Array){for(var i=0;i<item.blockedBy.length;i++){var block=item.blockedBy[i];if(items.hasOwnProperty(block)===false){log(item.name+" blocked = "+block);return true;}else if(item.proceedIfError===true&&items[block].isError===true){return false;}else if(items[block].isComplete===false){log(item.name+" blocked = "+block);return true;}}}
return false;}
function markLoaded(filename){if(!filename||0===filename.length){return;}
if(filename in items){var item=items[filename];if(item.isComplete===true){log(item.name+' '+filename+': error loaded duplicate')}else{item.isComplete=true;item.isInitialized=true;}}else{items[filename]=new obj.fileLoaded(filename,true);}
log("Added dummyfile: "+items[filename]);}
function log(msg){var href=window.location.href;var reg=new RegExp('[?&]ezq=([^&#]*)','i');var string=reg.exec(href);var res=string?string[1]:null;if(res==="1")console.debug(msg);}
function processAll(){count++;if(count>200)return;log("let's go");processItems(hpItems);processItems(lpItems);}
function processItems(list){for(var i in list){if(list.hasOwnProperty(i)===false)continue;var item=list[i];if(item.isComplete===true||isBlocked(item)||item.isInitialized===true||item.isError===true){if(item.isError===true){log(item.name+': error')}else if(item.isComplete===true){log(item.name+': complete already')}else if(item.isInitialized===true){log(item.name+': initialized already')}}else{item.process();}}}
init();return{addFile:addFile,addDelayFile:addTimeDelayFile,addFunc:addFunc,addDelayFunc:addTimeDelayFunc,items:items,processAll:processAll,setallowLoad:setallowLoad,markLoaded:markLoaded,};})();__ez.evt.add=function(e,t,n){e.addEventListener?e.addEventListener(t,n,!1):e.attachEvent?e.attachEvent("on"+t,n):e["on"+t]=n()},__ez.evt.remove=function(e,t,n){e.removeEventListener?e.removeEventListener(t,n,!1):e.detachEvent?e.detachEvent("on"+t,n):delete e["on"+t]};__ez.script.add=function(e){var t=document.createElement("script");t.src=e,t.async=!0,t.type="text/javascript",document.getElementsByTagName("head")[0].appendChild(t)};__ez.dot={};__ez.vep=(function(){var pixels=[],pxURL="/detroitchicago/grapefruit.gif";function AddPixel(vID,pixelData){if(__ez.dot.isDefined(vID)&&__ez.dot.isValid(pixelData)){pixels.push({type:'video',video_impression_id:vID,domain_id:__ez.dot.getDID(),t_epoch:__ez.dot.getEpoch(0),data:__ez.dot.dataToStr(pixelData)});}}
function Fire(){if(typeof document.visibilityState!=='undefined'&&document.visibilityState==="prerender"){return;}
if(__ez.dot.isDefined(pixels)&&pixels.length>0){while(pixels.length>0){var j=5;if(j>pixels.length){j=pixels.length;}
var pushPixels=pixels.splice(0,j);var pixelURL=__ez.dot.getURL(pxURL)+"?orig="+(__ez.template.isOrig===true?1:0)+"&v="+btoa(JSON.stringify(pushPixels));__ez.dot.Fire(pixelURL);}}
pixels=[];}
return{Add:AddPixel,Fire:Fire};})();</script><script data-ezscrex='false' data-cfasync='false' data-pagespeed-no-defer>__ez.pel=(function(){var pixels=[],pxURL="/porpoiseant/army.gif";function AddAndFirePixel(adSlot,pixelData){AddPixel(adSlot,pixelData,0,0,0,0,0);Fire();}
function AddAndFireOrigPixel(adSlot,pixelData){AddPixel(adSlot,pixelData,0,0,0,0,0,true);Fire();}
function GetCurrentPixels(){return pixels;}
function AddPixel(adSlot,pixelData,revenue,est_revenue,bid_floor_filled,bid_floor_prev,stat_source_id,isOrig){if(!__ez.dot.isDefined(adSlot)||__ez.dot.isAnyDefined(adSlot.getSlotElementId,adSlot.ElementId)==false){return;}
var ad_position_id=parseInt(__ez.dot.getTargeting(adSlot,'ap'));var impId=__ez.dot.getSlotIID(adSlot),adUnit=__ez.dot.getAdUnit(adSlot,isOrig);var compId=parseInt(__ez.dot.getTargeting(adSlot,"compid"));var lineItemId=0;var creativeId=0;var ezimData=getEzimData(adSlot);if(typeof ezimData=='object'){if(ezimData.creative_id!==undefined){creativeId=ezimData.creative_id;}
if(ezimData.line_item_id!==undefined){lineItemId=ezimData.line_item_id;}}
if(__ez.dot.isDefined(impId,adUnit)&&__ez.dot.isValid(pixelData)){pixels.push({type:"impression",impression_id:impId,domain_id:__ez.dot.getDID(),unit:adUnit,t_epoch:__ez.dot.getEpoch(0),revenue:revenue,est_revenue:est_revenue,ad_position:ad_position_id,ad_size:"",bid_floor_filled:bid_floor_filled,bid_floor_prev:bid_floor_prev,stat_source_id:stat_source_id,country_code:__ez.dot.getCC(),pageview_id:__ez.dot.getPageviewId(),comp_id:compId,line_item_id:lineItemId,creative_id:creativeId,data:__ez.dot.dataToStr(pixelData),is_orig:isOrig||__ez.template.isOrig,});}}
function AddPixelById(impFullId,pixelData,isOrig){var vals=impFullId.split('/');if(__ez.dot.isDefined(impFullId)&&vals.length===3&&__ez.dot.isValid(pixelData)){var adUnit=vals[0],impId=vals[2];pixels.push({type:"impression",impression_id:impId,domain_id:__ez.dot.getDID(),unit:adUnit,t_epoch:__ez.dot.getEpoch(0),pageview_id:__ez.dot.getPageviewId(),data:__ez.dot.dataToStr(pixelData),is_orig:isOrig||__ez.template.isOrig});}}
function Fire(){if(typeof document.visibilityState!=='undefined'&&document.visibilityState==="prerender")return;if(__ez.dot.isDefined(pixels)&&pixels.length>0){var allPixels=[pixels.filter(function(pixel){return pixel.is_orig}),pixels.filter(function(pixel){return!pixel.is_orig})];allPixels.forEach(function(pixels){while(pixels.length>0){var isOrig=pixels[0].is_orig||false;var j=5;if(j>pixels.length){j=pixels.length;}
var pushPixels=pixels.splice(0,j);var pixelURL=__ez.dot.getURL(pxURL)+"?orig="+(isOrig===true?1:0)+"&sts="+btoa(JSON.stringify(pushPixels));if(typeof window.isAmp!=='undefined'&&isAmp&&typeof window._ezaq!=='undefined'&&_ezaq.hasOwnProperty("domain_id")){pixelURL+="&visit_uuid="+_ezaq['visit_uuid'];}
__ez.dot.Fire(pixelURL);}})}
pixels=[];}
function getEzimData(adSlot){if(typeof _ezim_d=="undefined"){return false}
var adUnitName=__ez.dot.getAdUnitPath(adSlot).split('/').pop();if(typeof _ezim_d==='object'&&_ezim_d.hasOwnProperty(adUnitName)){return _ezim_d[adUnitName];}
for(var ezimKey in _ezim_d){if(ezimKey.split('/').pop()===adUnitName){return _ezim_d[ezimKey];}}
return false;}
return{Add:AddPixel,AddAndFire:AddAndFirePixel,AddAndFireOrig:AddAndFireOrigPixel,AddById:AddPixelById,Fire:Fire,GetPixels:GetCurrentPixels,};})();</script><script async="" src="https://www.googletagmanager.com/gtag/js?id=UA-736542-2"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-736542-2');
</script>
<meta name="ahrefs-site-verification" content="d6926dba99e1bd878af8dbd9b2d998468388bbd077eb787eb8e2188353fab432"/>


<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<!-- feeds & pingback -->
<link rel="profile" href="http://gmpg.org/xfn/11"/>
<link rel="pingback" href="https://www.wonkeedonkeetools.co.uk/xmlrpc.php"/>
<!--[if lt IE 9]><script src="https://www.wonkeedonkeetools.co.uk/wp-content/themes/rehub-theme/js/html5shiv.js"></script><![endif]-->	
<meta name="robots" content="index, follow, max-image-preview:large, max-snippet:-1, max-video-preview:-1"/>

<!-- Google Tag Manager for WordPress by gtm4wp.com -->
<script data-cfasync="false" data-pagespeed-no-defer="" type="text/javascript">//<![CDATA[
	var gtm4wp_datalayer_name = "dataLayer";
	var dataLayer = dataLayer || [];
//]]>
</script>
<!-- End Google Tag Manager for WordPress by gtm4wp.com -->
	<!-- This site is optimized with the Yoast SEO plugin v16.2 - https://yoast.com/wordpress/plugins/seo/ -->
	<title>Bricklayers Tools &amp; Supplies - Wonkee Donkee Tools UK</title>
	<meta name="description" content="Have you got the best bricklayers tools for the job? Check out our guide today and make sure you are prepared for any work that comes your way."/>
	<link rel="canonical" href="https://www.wonkeedonkeetools.co.uk/best-bricklayers-tools"/>
	<meta property="og:locale" content="en_GB"/>
	<meta property="og:type" content="article"/>
	<meta property="og:title" content="Bricklayers Tools &amp; Supplies - Wonkee Donkee Tools UK"/>
	<meta property="og:description" content="Have you got the best bricklayers tools for the job? Check out our guide today and make sure you are prepared for any work that comes your way."/>
	<meta property="og:url" content="https://www.wonkeedonkeetools.co.uk/best-bricklayers-tools"/>
	<meta property="og:site_name" content="Wonkee Donkee Tools"/>
	<meta property="article:modified_time" content="2020-12-08T15:14:28+00:00"/>
	<meta property="og:image" content="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Pointing-Trowel-1.jpg"/>
	<meta property="og:image:width" content="1200"/>
	<meta property="og:image:height" content="798"/>
	<meta name="twitter:card" content="summary_large_image"/>
	<meta name="twitter:label1" content="Est. reading time"/>
	<meta name="twitter:data1" content="9 minutes"/>
	<script type="application/ld+json" class="yoast-schema-graph">{"@context":"https://schema.org","@graph":[{"@type":"WebSite","@id":"https://www.wonkeedonkeetools.co.uk/#website","url":"https://www.wonkeedonkeetools.co.uk/","name":"Wonkee Donkee Tools","description":"Wonkee Donkee Power Tools and DIY Tools","potentialAction":[{"@type":"SearchAction","target":"https://www.wonkeedonkeetools.co.uk/?s={search_term_string}","query-input":"required name=search_term_string"}],"inLanguage":"en-GB"},{"@type":"ImageObject","@id":"https://www.wonkeedonkeetools.co.uk/best-bricklayers-tools#primaryimage","inLanguage":"en-GB","url":"https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Pointing-Trowel-1.jpg","contentUrl":"https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Pointing-Trowel-1.jpg","width":1200,"height":798,"caption":"Pointing Trowel"},{"@type":"WebPage","@id":"https://www.wonkeedonkeetools.co.uk/best-bricklayers-tools#webpage","url":"https://www.wonkeedonkeetools.co.uk/best-bricklayers-tools","name":"Bricklayers Tools & Supplies - Wonkee Donkee Tools UK","isPartOf":{"@id":"https://www.wonkeedonkeetools.co.uk/#website"},"primaryImageOfPage":{"@id":"https://www.wonkeedonkeetools.co.uk/best-bricklayers-tools#primaryimage"},"datePublished":"2019-10-08T14:33:49+00:00","dateModified":"2020-12-08T15:14:28+00:00","description":"Have you got the best bricklayers tools for the job? Check out our guide today and make sure you are prepared for any work that comes your way.","breadcrumb":{"@id":"https://www.wonkeedonkeetools.co.uk/best-bricklayers-tools#breadcrumb"},"inLanguage":"en-GB","potentialAction":[{"@type":"ReadAction","target":["https://www.wonkeedonkeetools.co.uk/best-bricklayers-tools"]}]},{"@type":"BreadcrumbList","@id":"https://www.wonkeedonkeetools.co.uk/best-bricklayers-tools#breadcrumb","itemListElement":[{"@type":"ListItem","position":1,"item":{"@type":"WebPage","@id":"https://www.wonkeedonkeetools.co.uk/","url":"https://www.wonkeedonkeetools.co.uk/","name":"Home"}},{"@type":"ListItem","position":2,"item":{"@id":"https://www.wonkeedonkeetools.co.uk/best-bricklayers-tools#webpage"}}]}]}</script>
	<!-- / Yoast SEO plugin. -->


<link rel="dns-prefetch" href="//fonts.googleapis.com"/>
<link rel="dns-prefetch" href="//s.w.org"/>
<link href="https://fonts.gstatic.com" crossorigin="" rel="preconnect"/>
<link rel="alternate" type="application/rss+xml" title="Wonkee Donkee Tools » Feed" href="https://www.wonkeedonkeetools.co.uk/feed"/>
<link rel="alternate" type="application/rss+xml" title="Wonkee Donkee Tools » Comments Feed" href="https://www.wonkeedonkeetools.co.uk/comments/feed"/>
		<script type="text/javascript">
			window._wpemojiSettings = {"baseUrl":"https:\/\/s.w.org\/images\/core\/emoji\/13.0.1\/72x72\/","ext":".png","svgUrl":"https:\/\/s.w.org\/images\/core\/emoji\/13.0.1\/svg\/","svgExt":".svg","source":{"concatemoji":"https:\/\/www.wonkeedonkeetools.co.uk\/wp-includes\/js\/wp-emoji-release.min.js?ver=5.7.1"}};
			!function(e,a,t){var n,r,o,i=a.createElement("canvas"),p=i.getContext&&i.getContext("2d");function s(e,t){var a=String.fromCharCode;p.clearRect(0,0,i.width,i.height),p.fillText(a.apply(this,e),0,0);e=i.toDataURL();return p.clearRect(0,0,i.width,i.height),p.fillText(a.apply(this,t),0,0),e===i.toDataURL()}function c(e){var t=a.createElement("script");t.src=e,t.defer=t.type="text/javascript",a.getElementsByTagName("head")[0].appendChild(t)}for(o=Array("flag","emoji"),t.supports={everything:!0,everythingExceptFlag:!0},r=0;r<o.length;r++)t.supports[o[r]]=function(e){if(!p||!p.fillText)return!1;switch(p.textBaseline="top",p.font="600 32px Arial",e){case"flag":return s([127987,65039,8205,9895,65039],[127987,65039,8203,9895,65039])?!1:!s([55356,56826,55356,56819],[55356,56826,8203,55356,56819])&&!s([55356,57332,56128,56423,56128,56418,56128,56421,56128,56430,56128,56423,56128,56447],[55356,57332,8203,56128,56423,8203,56128,56418,8203,56128,56421,8203,56128,56430,8203,56128,56423,8203,56128,56447]);case"emoji":return!s([55357,56424,8205,55356,57212],[55357,56424,8203,55356,57212])}return!1}(o[r]),t.supports.everything=t.supports.everything&&t.supports[o[r]],"flag"!==o[r]&&(t.supports.everythingExceptFlag=t.supports.everythingExceptFlag&&t.supports[o[r]]);t.supports.everythingExceptFlag=t.supports.everythingExceptFlag&&!t.supports.flag,t.DOMReady=!1,t.readyCallback=function(){t.DOMReady=!0},t.supports.everything||(n=function(){t.readyCallback()},a.addEventListener?(a.addEventListener("DOMContentLoaded",n,!1),e.addEventListener("load",n,!1)):(e.attachEvent("onload",n),a.attachEvent("onreadystatechange",function(){"complete"===a.readyState&&t.readyCallback()})),(n=t.source||{}).concatemoji?c(n.concatemoji):n.wpemoji&&n.twemoji&&(c(n.twemoji),c(n.wpemoji)))}(window,document,window._wpemojiSettings);
		</script>
		<style type="text/css">
img.wp-smiley,
img.emoji {
	display: inline !important;
	border: none !important;
	box-shadow: none !important;
	height: 1em !important;
	width: 1em !important;
	margin: 0 .07em !important;
	vertical-align: -0.1em !important;
	background: none !important;
	padding: 0 !important;
}
</style>
	<link data-wpacu-style-handle="wp-block-library" rel="stylesheet" id="wp-block-library-css" href="https://www.wonkeedonkeetools.co.uk/wp-includes/css/dist/block-library/style.min.css?ver=5.7.1" type="text/css" media="all"/>
<link data-wpacu-style-handle="default_font" rel="stylesheet" id="default_font-css" href="//fonts.googleapis.com/css?family=Roboto%3A400%2C700&amp;subset=latin%2Ccyrillic&amp;ver=5.7.1" type="text/css" media="all"/>
<!--[if lt IE 9]>
<link data-wpacu-style-handle='vc_lte_ie9' rel='stylesheet' id='vc_lte_ie9-css'  href='https://www.wonkeedonkeetools.co.uk/wp-content/plugins/js_composer/assets/css/vc_lte_ie9.min.css?ver=7.0.3' type='text/css' media='screen' />
<![endif]-->
<link data-wpacu-style-handle="elementor-icons" rel="stylesheet" id="elementor-icons-css" href="https://www.wonkeedonkeetools.co.uk/wp-content/plugins/elementor/assets/lib/eicons/css/elementor-icons.min.css?ver=5.11.0" type="text/css" media="all"/>
<link data-wpacu-style-handle="elementor-animations" rel="stylesheet" id="elementor-animations-css" href="https://www.wonkeedonkeetools.co.uk/wp-content/plugins/elementor/assets/lib/animations/animations.min.css?ver=3.1.4" type="text/css" media="all"/>
<link data-wpacu-style-handle="elementor-frontend-legacy" rel="stylesheet" id="elementor-frontend-legacy-css" href="https://www.wonkeedonkeetools.co.uk/wp-content/plugins/elementor/assets/css/frontend-legacy.min.css?ver=3.1.4" type="text/css" media="all"/>
<link data-wpacu-style-handle="elementor-frontend" rel="stylesheet" id="elementor-frontend-css" href="https://www.wonkeedonkeetools.co.uk/wp-content/plugins/elementor/assets/css/frontend.min.css?ver=3.1.4" type="text/css" media="all"/>
<link data-wpacu-style-handle="elementor-post-255153" rel="stylesheet" id="elementor-post-255153-css" href="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/elementor/css/post-255153.css?ver=1615805830" type="text/css" media="all"/>
<link data-wpacu-style-handle="elementor-post-125569" rel="stylesheet" id="elementor-post-125569-css" href="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/elementor/css/post-125569.css?ver=1615812326" type="text/css" media="all"/>
<link data-wpacu-style-handle="rhstyle" rel="stylesheet" id="rhstyle-css" href="https://www.wonkeedonkeetools.co.uk/wp-content/themes/rehub-theme/style.css?ver=9.1.3" type="text/css" media="all"/>
<link data-wpacu-style-handle="responsive" rel="stylesheet" id="responsive-css" href="https://www.wonkeedonkeetools.co.uk/wp-content/themes/rehub-theme/css/responsive.css?ver=9.1.3" type="text/css" media="all"/>
<link data-wpacu-style-handle="rehub_shortcode" rel="stylesheet" id="rehub_shortcode-css" href="https://www.wonkeedonkeetools.co.uk/wp-content/themes/rehub-theme/shortcodes/css/css.css?ver=9.1.3" type="text/css" media="all"/>
<link data-wpacu-style-handle="rehubfontawesome" rel="stylesheet" id="rehubfontawesome-css" href="https://www.wonkeedonkeetools.co.uk/wp-content/themes/rehub-theme/admin/fonts/fontawesome/font-awesome.min.css?ver=5.3.1" type="text/css" media="all"/>
<link data-wpacu-style-handle="google-fonts-1" rel="stylesheet" id="google-fonts-1-css" href="https://fonts.googleapis.com/css?family=Roboto%3A100%2C100italic%2C200%2C200italic%2C300%2C300italic%2C400%2C400italic%2C500%2C500italic%2C600%2C600italic%2C700%2C700italic%2C800%2C800italic%2C900%2C900italic%7CRoboto+Slab%3A100%2C100italic%2C200%2C200italic%2C300%2C300italic%2C400%2C400italic%2C500%2C500italic%2C600%2C600italic%2C700%2C700italic%2C800%2C800italic%2C900%2C900italic&amp;ver=5.7.1" type="text/css" media="all"/>
<link data-wpacu-style-handle="elementor-icons-shared-0" rel="stylesheet" id="elementor-icons-shared-0-css" href="https://www.wonkeedonkeetools.co.uk/wp-content/plugins/elementor/assets/lib/font-awesome/css/fontawesome.min.css?ver=5.15.1" type="text/css" media="all"/>
<link data-wpacu-style-handle="elementor-icons-fa-regular" rel="stylesheet" id="elementor-icons-fa-regular-css" href="https://www.wonkeedonkeetools.co.uk/wp-content/plugins/elementor/assets/lib/font-awesome/css/regular.min.css?ver=5.15.1" type="text/css" media="all"/>
<script data-wpacu-jquery-core-handle="1" data-wpacu-script-handle="jquery-core" type="text/javascript" src="https://www.wonkeedonkeetools.co.uk/wp-includes/js/jquery/jquery.min.js?ver=3.5.1" id="jquery-core-js"></script>
<script data-wpacu-jquery-migrate-handle="1" data-wpacu-script-handle="jquery-migrate" type="text/javascript" src="https://www.wonkeedonkeetools.co.uk/wp-includes/js/jquery/jquery-migrate.min.js?ver=3.3.2" id="jquery-migrate-js"></script>
<script data-wpacu-script-handle="gtm4wp-form-move-tracker" type="text/javascript" src="https://www.wonkeedonkeetools.co.uk/wp-content/plugins/duracelltomi-google-tag-manager/js/gtm4wp-form-move-tracker.js?ver=1.12.3" id="gtm4wp-form-move-tracker-js"></script>
<link rel="https://api.w.org/" href="https://www.wonkeedonkeetools.co.uk/wp-json/"/><link rel="alternate" type="application/json" href="https://www.wonkeedonkeetools.co.uk/wp-json/wp/v2/pages/125569"/><link rel="EditURI" type="application/rsd+xml" title="RSD" href="https://www.wonkeedonkeetools.co.uk/xmlrpc.php?rsd"/>
<link rel="wlwmanifest" type="application/wlwmanifest+xml" href="https://www.wonkeedonkeetools.co.uk/wp-includes/wlwmanifest.xml"/> 
<meta name="generator" content="WordPress 5.7.1"/>
<link rel="shortlink" href="https://www.wonkeedonkeetools.co.uk/?p=125569"/>
<link rel="alternate" type="application/json+oembed" href="https://www.wonkeedonkeetools.co.uk/wp-json/oembed/1.0/embed?url=https%3A%2F%2Fwww.wonkeedonkeetools.co.uk%2Fbest-bricklayers-tools"/>
<link rel="alternate" type="text/xml+oembed" href="https://www.wonkeedonkeetools.co.uk/wp-json/oembed/1.0/embed?url=https%3A%2F%2Fwww.wonkeedonkeetools.co.uk%2Fbest-bricklayers-tools&amp;format=xml"/>

<!-- Call Now Button 0.4.1 by Jerry Rietveld (callnowbutton.com) -->
<style>#callnowbutton {display:none;} @media screen and (max-width:650px){#callnowbutton {display:block; position:fixed; text-decoration:none; z-index:2147483647;width:65px; height:65px; border-radius:50%; box-shadow: 0 3px 6px rgba(0, 0, 0, 0.3);transform: scale(1);bottom:15px; right:20px;background:url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB2aWV3Qm94PSIwIDAgNjAgNjAiPjxwYXRoIGQ9Ik03LjEwNCAxNC4wMzJsMTUuNTg2IDEuOTg0YzAgMC0wLjAxOSAwLjUgMCAwLjk1M2MwLjAyOSAwLjc1Ni0wLjI2IDEuNTM0LTAuODA5IDIuMSBsLTQuNzQgNC43NDJjMi4zNjEgMy4zIDE2LjUgMTcuNCAxOS44IDE5LjhsMTYuODEzIDEuMTQxYzAgMCAwIDAuNCAwIDEuMSBjLTAuMDAyIDAuNDc5LTAuMTc2IDAuOTUzLTAuNTQ5IDEuMzI3bC02LjUwNCA2LjUwNWMwIDAtMTEuMjYxIDAuOTg4LTI1LjkyNS0xMy42NzRDNi4xMTcgMjUuMyA3LjEgMTQgNy4xIDE0IiBmaWxsPSIjMDA0MTY4Ii8+PHBhdGggZD0iTTcuMTA0IDEzLjAzMmw2LjUwNC02LjUwNWMwLjg5Ni0wLjg5NSAyLjMzNC0wLjY3OCAzLjEgMC4zNWw1LjU2MyA3LjggYzAuNzM4IDEgMC41IDIuNTMxLTAuMzYgMy40MjZsLTQuNzQgNC43NDJjMi4zNjEgMy4zIDUuMyA2LjkgOS4xIDEwLjY5OWMzLjg0MiAzLjggNy40IDYuNyAxMC43IDkuMSBsNC43NC00Ljc0MmMwLjg5Ny0wLjg5NSAyLjQ3MS0xLjAyNiAzLjQ5OC0wLjI4OWw3LjY0NiA1LjQ1NWMxLjAyNSAwLjcgMS4zIDIuMiAwLjQgMy4xMDVsLTYuNTA0IDYuNSBjMCAwLTExLjI2MiAwLjk4OC0yNS45MjUtMTMuNjc0QzYuMTE3IDI0LjMgNy4xIDEzIDcuMSAxMyIgZmlsbD0iI2ZmZmZmZiIvPjwvc3ZnPg==) center/45px 45px no-repeat #115f86;}}#callnowbutton span{display:none;}</style>
<!-- start Simple Custom CSS and JS -->
<script type="text/javascript">
/* Default comment here */ 

jQuery(document).ready(function( $ ){
  $("#sidebar-toggle").click(function(){
    $(".new-product-learning-template .left-sidebar ul").slideToggle(200); 
  });
});</script>
<!-- end Simple Custom CSS and JS -->
<!-- start Simple Custom CSS and JS -->
<style type="text/css">
.new-product-learning-template .left-sidebar {
    width: 20%;
    float: left;
}

.new-product-learning-template .left-sidebar ul {
    padding: 15px;
    border: 1px solid #e3e3e3;
    box-shadow: 0 2px 2px #ECECEC;
}

.new-product-learning-template .left-sidebar ul li {
    margin-bottom: 10px;
}

.new-product-learning-template .left-sidebar ul li:last-of-type {
    margin-bottom: 0;
}

.new-product-learning-template .left-sidebar ul li a {
    color: inherit;
    font-size: 13px;
}

.new-product-learning-template .left-sidebar ul li.active a {
    font-weight: 700;
}

.new-product-learning-template .main-side {
    width: 60% !important;
    padding: 0 25px;
}

.new-product-learning-template .sidebar {
    width: 20%;
}

.learning-index-boxes {
  display: -webkit-box;
  display: flex;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
  flex-flow: row wrap;
  width: 100%;
}

.learning-index-boxes a {
  padding: 7px;
  margin: 7px;
  border: 1px solid #e3e3e3;
  box-shadow: 0 2px 2px #ECECEC;
  display: block;
  color: inherit;
  
  flex-basis: auto;
  -webkit-box-flex: 0;
  flex: 0 0 auto;
  width: calc(14.2857142857% - 14px);
}

.learning-index-boxes a img {
  display: block;
  width: 100%;
  height: auto;
}

.learning-index-boxes a .link-title {
  display: block;
  width: 100%;
  text-align: center;
  margin-top: 10px;
  font-size: 13px;
}

.learning-filters {
  margin: 30px auto;
}

.learning-filters h5 {
  text-align: center;
  margin-bottom: 10px;
}

.learning-filters ul.filter-list {
  display: -webkit-box;
  display: flex;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
  flex-flow: row wrap;
  width: 100%;
}

.learning-filters ul.filter-list li.filter-item {
  padding: 15px 5px;
  margin: 5px;
  border: 1px solid #e3e3e3;
  box-shadow: 0 2px 2px #ECECEC;
  display: block;
  color: inherit!important;
  
  flex-basis: auto;
  -webkit-box-flex: 0;
  flex: 0 0 auto;
  width: calc(7.14% - 10px);
  text-align: center;
  cursor: pointer;
  font-size: 13px;
}

.learning-filters ul.filter-list li.filter-item a {
  padding: 0;
  color: inherit;
}

.learning-filters ul.filter-list li.filter-item:hover a {
  color: #115f86;
}

#sidebar-toggle {
  display: none;
  cursor: pointer;
  width: 100%;
  padding: 10px;
  background: #115f86;
  color: #fff;
}

@media only screen and (max-width: 1600px) {
   .learning-index-boxes a {
    width: calc(16.6666666667% - 14px);
  }
}

@media only screen and (max-width: 1450px) {
   .learning-index-boxes a {
    width: calc(20% - 14px);
  }
}

@media only screen and (max-width: 1150px) {
   .learning-index-boxes a {
    width: calc(25% - 14px);
  }
}

@media only screen and (max-width: 900px) {
   .learning-index-boxes a {
    width: calc(33.3333% - 14px);
  }
}

@media only screen and (max-width: 600px) {
  
  .new-product-learning-template .left-sidebar {
      width: 100%;
  }

   .new-product-learning-template .main-side {
     width: 100% !important;
     margin: 20px auto;
     float: left;
     padding: 0;
  }

  .new-product-learning-template .sidebar {
      width: 100%;
  }

   .learning-index-boxes a {
    width: calc(50% - 14px);
  }
  
  #sidebar-toggle {
    display: block;
  }
  
  .new-product-learning-template .left-sidebar ul {
    display: none;
  }
  
}

.header-other-sites {
	 padding: 10px 25px;
	 border-bottom: 1px solid #efefef;
	 text-align: center;
}
 .header-other-sites h4 {
	 color: #000;
	 display: inline-block;
	 margin: 0 5px 0 0;
	 vertical-align: middle;
}
 @media only screen and (max-width: 750px) {
	 .header-other-sites h4 {
		 display: block;
		 margin: 0 0 5px;
	}
}
 .header-other-sites .other-sites-inner {
	 display: inline-block;
	 vertical-align: middle;
}
 .header-other-sites .other-sites-inner a {
	 display: inline-block;
	 vertical-align: middle;
	 margin: 0 5px;
}
 @media only screen and (max-width: 750px) {
	 .header-other-sites .other-sites-inner a {
		 max-width: 24%;
		 margin: 0;
	}
}
 .header-other-sites .other-sites-inner a img {
	 max-height: 60px;
	 border: 1px solid #efefef;
}
 
</style>
<!-- end Simple Custom CSS and JS -->
<script data-ad-client="ca-pub-9035597241048800" async="" src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><style id="wplmi-inline-css" type="text/css"> span.wplmi-user-avatar { width: 16px;display: inline-block !important;flex-shrink: 0; } img.wplmi-elementor-avatar { border-radius: 100%;margin-right: 3px; } 

</style>

<!-- Google Tag Manager for WordPress by gtm4wp.com -->
<script data-cfasync="false" data-pagespeed-no-defer="" type="text/javascript">//<![CDATA[
	var dataLayer_content = {"pagePostType":"page","pagePostType2":"single-page","pageCategory":["tool-guides"],"pagePostAuthor":"Chris"};
	dataLayer.push( dataLayer_content );//]]>
</script>
<script data-cfasync="false">//<![CDATA[
(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
'//www.googletagmanager.com/gtm.'+'js?id='+i+dl;f.parentNode.insertBefore(j,f);
})(window,document,'script','dataLayer','GTM-N28J8LR');//]]>
</script>
<!-- End Google Tag Manager -->
<!-- End Google Tag Manager for WordPress by gtm4wp.com -->		<script>
			document.documentElement.className = document.documentElement.className.replace( 'no-js', 'js' );
		</script>
				<style>
			.no-js img.lazyload { display: none; }
			figure.wp-block-image img.lazyloading { min-width: 150px; }
							.lazyload, .lazyloading { opacity: 0; }
				.lazyloaded {
					opacity: 1;
					transition: opacity 400ms;
					transition-delay: 0ms;
				}
					</style>
		<style type="text/css"> nav.top_menu > ul > li > a{padding:11px 15px 15px 15px;font-size:17px}nav.top_menu > ul > li > a{font-size:13px}nav.top_menu > ul > li > a{text-transform:uppercase;}nav.top_menu > ul > li > a{font-weight:normal;}header .main-nav,.main-nav.dark_style{background:none repeat scroll 0 0 #115f86!important;box-shadow:none;}.main-nav{border-bottom:none;}.dl-menuwrapper .dl-menu{margin:0 !important}.main-nav .user-ava-intop:after,nav.top_menu > ul > li > a,.dl-menuwrapper button i{color:#ffffff !important;}nav.top_menu > ul > li > a:hover{box-shadow:none;}#main_header,.is-sticky .logo_section_wrap{background-color:#ffffff !important}.header-top{border:none;}.left-sidebar-archive .main-side{float:right;}.left-sidebar-archive .sidebar{float:left}.footer-bottom{background-color:#0e567b !important}.footer-bottom .footer_widget{border:none !important} .widget .title:after{border-bottom:2px solid #0029ff;}.rehub-main-color-border,nav.top_menu > ul > li.vertical-menu.border-main-color .sub-menu,.rh-main-bg-hover:hover,.wp-block-quote,ul.def_btn_link_tabs li.active a,.wp-block-pullquote{border-color:#0029ff;}.wpsm_promobox.rehub_promobox{border-left-color:#0029ff!important;}.color_link{color:#0029ff !important;}.search-header-contents{border-top-color:#0029ff;}.wpb_content_element.wpsm-tabs.n_b_tab .wpb_tour_tabs_wrapper .wpb_tabs_nav .ui-state-active a{border-bottom:3px solid #0029ff !important}.featured_slider:hover .score,.top_chart_controls .controls:hover,article.post .wpsm_toplist_heading:before{border-color:#0029ff;}.btn_more:hover,.small_post .overlay .btn_more:hover,.tw-pagination .current{border:1px solid #0029ff;color:#fff}.wpsm-tabs ul.ui-tabs-nav .ui-state-active a,.rehub_woo_review .rehub_woo_tabs_menu li.current{border-top:3px solid #0029ff;}.wps_promobox{border-left:3px solid #0029ff;}.gallery-pics .gp-overlay{box-shadow:0 0 0 4px #0029ff inset;}.post .rehub_woo_tabs_menu li.current,.woocommerce div.product .woocommerce-tabs ul.tabs li.active{border-top:2px solid #0029ff;}.rething_item a.cat{border-bottom-color:#0029ff}nav.top_menu ul li ul.sub-menu{border-bottom:2px solid #0029ff;}.widget.deal_daywoo,.elementor-widget .deal_daywoo{border:3px solid #0029ff;padding:20px;background:#fff;}.deal_daywoo .wpsm-bar-bar{background-color:#0029ff !important} #buddypress div.item-list-tabs ul li.selected a span,#buddypress div.item-list-tabs ul li.current a span,#buddypress div.item-list-tabs ul li a span,.user-profile-div .user-menu-tab > li.active > a,.user-profile-div .user-menu-tab > li.active > a:focus,.user-profile-div .user-menu-tab > li.active > a:hover,.slide .news_cat a,.news_in_thumb:hover .news_cat a,.news_out_thumb:hover .news_cat a,.col-feat-grid:hover .news_cat a,.carousel-style-deal .re_carousel .controls,.re_carousel .controls:hover,.openedprevnext .postNavigation a,.postNavigation a:hover,.top_chart_pagination a.selected,.flex-control-paging li a.flex-active,.flex-control-paging li a:hover,.widget_edd_cart_widget .edd-cart-number-of-items .edd-cart-quantity,.btn_more:hover,.tabs-menu li:hover,.tabs-menu li.current,.featured_slider:hover .score,#bbp_user_edit_submit,.bbp-topic-pagination a,.bbp-topic-pagination a,.custom-checkbox label.checked:after,.slider_post .caption,ul.postpagination li.active a,ul.postpagination li:hover a,ul.postpagination li a:focus,.top_theme h5 strong,.re_carousel .text:after,#topcontrol:hover,.main_slider .flex-overlay:hover a.read-more,.rehub_chimp #mc_embed_signup input#mc-embedded-subscribe,#rank_1.rank_count,#toplistmenu > ul li:before,.rehub_chimp:before,.wpsm-members > strong:first-child,.r_catbox_btn,.wpcf7 .wpcf7-submit,.comm_meta_wrap .rh_user_s2_label,.wpsm_pretty_hover li:hover,.wpsm_pretty_hover li.current,.rehub-main-color-bg,.togglegreedybtn:after,.rh-bg-hover-color:hover .news_cat a,.rh-main-bg-hover:hover,.rh_wrapper_video_playlist .rh_video_currently_playing,.rh_wrapper_video_playlist .rh_video_currently_playing.rh_click_video:hover,.rtmedia-list-item .rtmedia-album-media-count,.tw-pagination .current,.dokan-dashboard .dokan-dash-sidebar ul.dokan-dashboard-menu li.active,.dokan-dashboard .dokan-dash-sidebar ul.dokan-dashboard-menu li:hover,.dokan-dashboard .dokan-dash-sidebar ul.dokan-dashboard-menu li.dokan-common-links a:hover,#ywqa-submit-question,.woocommerce .widget_price_filter .ui-slider .ui-slider-range,.rh-hov-bor-line > a:after,nav.top_menu > ul:not(.off-canvas) > li > a:after,.rh-border-line:after,.wpsm-table.wpsm-table-main-color table tr th{background:#0029ff;}@media (max-width:767px){.postNavigation a{background:#0029ff;}}.rh-main-bg-hover:hover,.rh-main-bg-hover:hover .whitehovered{color:#fff !important} a,.carousel-style-deal .deal-item .priced_block .price_count ins,nav.top_menu ul li.menu-item-has-children ul li.menu-item-has-children > a:before,.top_chart_controls .controls:hover,.flexslider .fa-pulse,.footer-bottom .widget .f_menu li a:hover,.comment_form h3 a,.bbp-body li.bbp-forum-info > a:hover,.bbp-body li.bbp-topic-title > a:hover,#subscription-toggle a:before,#favorite-toggle a:before,.aff_offer_links .aff_name a,.rh-deal-price,.commentlist .comment-content small a,.related_articles .title_cat_related a,article em.emph,.campare_table table.one td strong.red,.sidebar .tabs-item .detail p a,.footer-bottom .widget .title span,footer p a,.welcome-frase strong,article.post .wpsm_toplist_heading:before,.post a.color_link,.categoriesbox:hover h3 a:after,.bbp-body li.bbp-forum-info > a,.bbp-body li.bbp-topic-title > a,.widget .title i,.woocommerce-MyAccount-navigation ul li.is-active a,.category-vendormenu li.current a,.deal_daywoo .title,.rehub-main-color,.wpsm_pretty_colored ul li.current a,.wpsm_pretty_colored ul li.current,.rh-heading-hover-color:hover h2 a,.rh-heading-hover-color:hover h3 a,.rh-heading-hover-color:hover h4 a,.rh-heading-hover-color:hover h5 a,.rh-heading-icon:before,.widget_layered_nav ul li.chosen a:before,.wp-block-quote.is-style-large p,ul.page-numbers li span.current,ul.page-numbers li a:hover,ul.page-numbers li.active a,.page-link > span:not(.page-link-title),blockquote:not(.wp-block-quote) p,span.re_filtersort_btn:hover,span.active.re_filtersort_btn,.deal_daywoo .price,div.sortingloading:after{color:#0029ff;}a{color:#174a96;} .page-link > span:not(.page-link-title),.postimagetrend .title,.widget.widget_affegg_widget .title,.widget.top_offers .title,.widget.cegg_widget_products .title,header .header_first_style .search form.search-form [type="submit"],header .header_eight_style .search form.search-form [type="submit"],.more_post a,.more_post span,.filter_home_pick span.active,.filter_home_pick span:hover,.filter_product_pick span.active,.filter_product_pick span:hover,.rh_tab_links a.active,.rh_tab_links a:hover,.wcv-navigation ul.menu li.active,.wcv-navigation ul.menu li:hover a,form.search-form [type="submit"],.rehub-sec-color-bg,input#ywqa-submit-question,input#ywqa-send-answer,.woocommerce button.button.alt,.tabsajax span.active.re_filtersort_btn,.wpsm-table.wpsm-table-sec-color table tr th{background:#1c348a !important;color:#fff !important;outline:0}.widget.widget_affegg_widget .title:after,.widget.top_offers .title:after,.vc_tta-tabs.wpsm-tabs .vc_tta-tab.vc_active,.vc_tta-tabs.wpsm-tabs .vc_tta-panel.vc_active .vc_tta-panel-heading,.widget.cegg_widget_products .title:after{border-top-color:#1c348a !important;}.page-link > span:not(.page-link-title){border:1px solid #1c348a;}.page-link > span:not(.page-link-title),.header_first_style .search form.search-form [type="submit"] i{color:#fff !important;}.rh_tab_links a.active,.rh_tab_links a:hover,.rehub-sec-color-border,nav.top_menu > ul > li.vertical-menu.border-sec-color > .sub-menu{border-color:#1c348a}.rh_wrapper_video_playlist .rh_video_currently_playing,.rh_wrapper_video_playlist .rh_video_currently_playing.rh_click_video:hover{background-color:#1c348a;box-shadow:1200px 0 0 #1c348a inset;}.rehub-sec-color{color:#1c348a} .news .priced_block .price_count,.blog_string .priced_block .price_count,.main_slider .price_count{margin-right:5px}.right_aff .priced_block .btn_offer_block,.right_aff .priced_block .price_count{border-radius:0 !important}form.search-form.product-search-form input[type="text"]{border-radius:4px 0 0 4px;}form.search-form [type="submit"]{border-radius:0 4px 4px 0;}.rtl form.search-form.product-search-form input[type="text"]{border-radius:0 4px 4px 0;}.rtl form.search-form [type="submit"]{border-radius:4px 0 0 4px;}.price_count,.rehub_offer_coupon,#buddypress .dir-search input[type=text],.gmw-form-wrapper input[type=text],.gmw-form-wrapper select,#buddypress a.button,.btn_more,#main_header .wpsm-button,#rh-header-cover-image .wpsm-button,#wcvendor_image_bg .wpsm-button,input[type="text"],textarea,input[type="tel"],input[type="password"],input[type="email"],input[type="url"],input[type="number"],.def_btn,input[type="submit"],input[type="button"],input[type="reset"],.rh_offer_list .offer_thumb .deal_img_wrap,.grid_onsale,.rehub-main-smooth,.re_filter_instore span.re_filtersort_btn:hover,.re_filter_instore span.active.re_filtersort_btn,#buddypress .standard-form input[type=text],#buddypress .standard-form textarea{border-radius:4px}.news-community,.woocommerce .products.grid_woo .product,.rehub_chimp #mc_embed_signup input.email,#mc_embed_signup input#mc-embedded-subscribe,.rh_offer_list,.woo-tax-logo,#buddypress div.item-list-tabs ul li a,#buddypress form#whats-new-form,#buddypress div#invite-list,#buddypress #send-reply div.message-box,.rehub-sec-smooth,.rate-bar-bar,.rate-bar,#wcfm-main-contentainer #wcfm-content,.wcfm_welcomebox_header{border-radius:5px} .woocommerce .summary .masked_coupon,.woocommerce a.woo_loop_btn,.woocommerce input.button.alt,.woocommerce a.add_to_cart_button,.woocommerce-page a.add_to_cart_button,.woocommerce .single_add_to_cart_button,.woocommerce div.product form.cart .button,.woocommerce .checkout-button.button,.woofiltersbig .prdctfltr_buttons a.prdctfltr_woocommerce_filter_submit,.priced_block .btn_offer_block,.priced_block .button,.rh-deal-compact-btn,input.mdf_button,#buddypress input[type="submit"],#buddypress input[type="button"],#buddypress input[type="reset"],#buddypress button.submit,.wpsm-button.rehub_main_btn,.wcv-grid a.button,input.gmw-submit,#ws-plugin--s2member-profile-submit,#rtmedia_create_new_album,input[type="submit"].dokan-btn-theme,a.dokan-btn-theme,.dokan-btn-theme,#wcfm_membership_container a.wcfm_submit_button,.woocommerce button.button,.rehub-main-btn-bg{background:none #de1414 !important;color:#ffffff !important;border:none !important;text-decoration:none !important;outline:0;box-shadow:-1px 6px 19px rgba(222,20,20,0.2) !important;border-radius:4px !important;}.woocommerce a.woo_loop_btn:hover,.woocommerce input.button.alt:hover,.woocommerce a.add_to_cart_button:hover,.woocommerce-page a.add_to_cart_button:hover,.woocommerce a.single_add_to_cart_button:hover,.woocommerce-page a.single_add_to_cart_button:hover,.woocommerce div.product form.cart .button:hover,.woocommerce-page div.product form.cart .button:hover,.woocommerce .checkout-button.button:hover,.woofiltersbig .prdctfltr_buttons a.prdctfltr_woocommerce_filter_submit:hover,.priced_block .btn_offer_block:hover,.wpsm-button.rehub_main_btn:hover,#buddypress input[type="submit"]:hover,#buddypress input[type="button"]:hover,#buddypress input[type="reset"]:hover,#buddypress button.submit:hover,.small_post .btn:hover,.ap-pro-form-field-wrapper input[type="submit"]:hover,.wcv-grid a.button:hover,#ws-plugin--s2member-profile-submit:hover,input[type="submit"].dokan-btn-theme:hover,a.dokan-btn-theme:hover,.dokan-btn-theme:hover,.rething_button .btn_more:hover,#wcfm_membership_container a.wcfm_submit_button:hover,.woocommerce button.button:hover,.rehub-main-btn-bg:hover{background:none #1e1496 !important;color:#ffffff !important;box-shadow:-1px 6px 13px rgba(30,20,150,0.4) !important;border-color:transparent;}.rehub_offer_coupon:hover{border:1px dashed #1e1496;}.rehub_offer_coupon:hover i.far,.rehub_offer_coupon:hover i.fal,.rehub_offer_coupon:hover i.fas{color:#1e1496}.re_thing_btn .rehub_offer_coupon.not_masked_coupon:hover{color:#1e1496 !important}.woocommerce a.woo_loop_btn:active,.woocommerce .button.alt:active,.woocommerce a.add_to_cart_button:active,.woocommerce-page a.add_to_cart_button:active,.woocommerce a.single_add_to_cart_button:active,.woocommerce-page a.single_add_to_cart_button:active,.woocommerce div.product form.cart .button:active,.woocommerce-page div.product form.cart .button:active,.woocommerce .checkout-button.button:active,.woofiltersbig .prdctfltr_buttons a.prdctfltr_woocommerce_filter_submit:active,.wpsm-button.rehub_main_btn:active,#buddypress input[type="submit"]:active,#buddypress input[type="button"]:active,#buddypress input[type="reset"]:active,#buddypress button.submit:active,.ap-pro-form-field-wrapper input[type="submit"]:active,.wcv-grid a.button:active,#ws-plugin--s2member-profile-submit:active,input[type="submit"].dokan-btn-theme:active,a.dokan-btn-theme:active,.dokan-btn-theme:active,.woocommerce button.button:active,.rehub-main-btn-bg:active{background:none #de1414 !important;box-shadow:0 1px 0 #999 !important;top:2px;color:#ffffff !important;}.rehub_btn_color{background-color:#de1414;border:1px solid #de1414;}.rehub-button-color{color:#de1414}.rething_button .btn_more{border:1px solid #de1414;color:#de1414;}.rething_button .priced_block.block_btnblock .price_count{color:#de1414;font-weight:normal;}.widget_merchant_list .buttons_col{background-color:#de1414 !important;}.widget_merchant_list .buttons_col a{color:#ffffff !important;}@media (max-width:767px){#float-panel-woo-area{border-top:1px solid #de1414}}.rh_post_layout_big_offer .priced_block .btn_offer_block{text-shadow:none}.rh_deal_block .redemptionText .code,.rh_deal_block .not_masked_coupon{display:block;margin:10px 0 0 0;float:none;}.rh_deal_block .rh-deal-left,.rh_deal_block .rh-deal-right{display:block;padding:0}.rh_deal_block .rh-deal-btn,.rh_deal_block .rh-deal-right .rh-deal-price{text-align:inherit;}#content-sticky-panel{margin-left:-90px}@media (min-width:1400px){.postimagetrend.two_column .wrap img{min-height:120px}.postimagetrend.two_column .wrap{height:120px}.rh-boxed-container .rh-outer-wrap{width:1380px}.rh-container,.content{width:1330px;}.centered-container .vc_col-sm-12 > * > .wpb_wrapper,.vc_section > .vc_row,.wcfm-membership-wrapper,.elementor-section.elementor-section-boxed > .elementor-container{max-width:1330px;}.sidebar,.side-twocol,.vc_row.vc_rehub_container > .vc_col-sm-4{width:270px}.vc_row.vc_rehub_container > .vc_col-sm-8,.main-side:not(.full_width),.main_slider.flexslider{width:1030px;}}@media (min-width:1600px){.rehub_chimp h3{font-size:20px}.rh-boxed-container .rh-outer-wrap{width:1580px}.rh-container,.content{width:1530px;}.centered-container .vc_col-sm-12 > * > .wpb_wrapper,.vc_section > .vc_row,.wcfm-membership-wrapper,.elementor-section.elementor-section-boxed > .elementor-container{max-width:1530px;}.sidebar,.side-twocol,.vc_row.vc_rehub_container > .vc_col-sm-4{width:270px}.vc_row.vc_rehub_container > .vc_col-sm-8,.main-side:not(.full_width),.main_slider.flexslider{width:1230px;}}@media(min-width:1224px){.single-post .full_width > article.post,single-product .full_width > article.post{padding:32px}.title_single_area.full_width{margin:25px 32px 0 32px;}.main-side .title_single_area.full_width{margin:0;}.full_width .wpsm-comptable td img{padding:5px}}</style><meta name="generator" content="Powered by WPBakery Page Builder - drag and drop page builder for WordPress."/>
<link rel="icon" href="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/07/favicon-32x32-100x100.png" sizes="32x32"/>
<link rel="icon" href="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/07/favicon-32x32-300x300.png" sizes="192x192"/>
<link rel="apple-touch-icon" href="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/07/favicon-32x32-300x300.png"/>
<meta name="msapplication-TileImage" content="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/07/favicon-32x32-300x300.png"/>
<noscript><style> .wpb_animate_when_almost_visible { opacity: 1; }</style></noscript><style>.header_seven_style .search{ display:none!important;}

.main-nav.white_style {
    border-top: 4px solid #115f86;
    border-bottom: 4px solid #115f86;
}

.footer-bottom .footer_widget a {
    font-weight: bold !important;
    text-decoration: none !important;
}

#outercssLI_5, #outercssLI_9, #outercssLI_13, #outercssLI_17 {

    list-style: outside!important;
}

.rh_post_layout_metabig{
display:none !important;
}

.entry-title{
display:none;
}

.icon-search-onclick{
display:none;
}

.ajax_add_to_cart {
display:none
}

.product-add{display:none}


.page-id-240008 .et-db #et-boc .et_pb_row {
    padding: 2% !important;
}

.page-id-240008 .logo_container{
display:none!important;
}</style><script type="text/javascript">var ezouid = "1";</script><base href="https://www.wonkeedonkeetools.co.uk/best-bricklayers-tools"><script type='text/javascript'>
var ezoTemplate = 'old_site_noads';
if(typeof ezouid == 'undefined')
{
    var ezouid = 'none';
}
var ezoFormfactor = '1';
var ezo_elements_to_check = Array();
</script><!-- START EZHEAD -->
<script data-ezscrex="false" type='text/javascript'>
var soc_app_id = '0';
var did = 175424;
var ezdomain = 'wonkeedonkeetools.co.uk';
var ezoicSearchable = 1;
</script>
<!--{jquery}-->
<!-- END EZHEAD -->
<script data-ezscrex="false" type="text/javascript" data-cfasync="false">var _ezaq = {"ab_test_id":"mod13-c","ad_cache_level":0,"ad_lazyload_version":0,"ad_load_version":0,"city":"Birmingham","country":"GB","days_since_last_visit":0,"domain_id":175424,"engaged_time_visit":285,"ezcache_level":0,"ezcache_skip_code":0,"form_factor_id":1,"framework_id":1,"is_return_visitor":true,"is_sitespeed":0,"last_page_load":"1621255010010","last_pageview_id":"51bb862d-73e0-4a86-6c75-90624fcf5110","lt_cache_level":0,"metro_code":0,"page_ad_positions":"","page_view_count":2,"page_view_id":"a2a652a0-6915-4825-5856-d4bb8fd1ea87","position_selection_id":0,"postal_code":"B7","pv_event_count":0,"referring_domain":"google.com","response_size_orig":222195,"response_time_orig":0,"serverid":"35.180.117.135:17675","state":"BIR","t_epoch":1621256219,"template_id":120,"time_on_site_visit":4343,"url":"https://www.wonkeedonkeetools.co.uk/best-bricklayers-tools","user_id":0,"visit_uuid":"e23b8ebf-2b4e-447a-77bb-b6898a43d951","word_count":1868,"worst_bad_word_level":0};var _ezExtraQueries = "&ez_orig=1";</script><script data-ezscrex='false' data-cfasync='false' type="text/javascript">var ezWp = true;</script>
<script data-ezscrex='false' data-pagespeed-no-defer data-cfasync='false'>
function create_ezolpl(pvID, rv) {
    var d = new Date();
    d.setTime(d.getTime() + (365*24*60*60*1000));
    var expires = "expires="+d.toUTCString();
    __ez.ck.setByCat("ezux_lpl_175424=" + new Date().getTime() + "|" + pvID + "|" + rv + "; " + expires, 3);
}
function attach_ezolpl(pvID, rv) {
    if (document.readyState === "complete") {
        create_ezolpl(pvID, rv);
    }
    if(window.attachEvent) {
        window.attachEvent("onload", create_ezolpl, pvID, rv);
    } else {
        if(window.onload) {
            var curronload = window.onload;
            var newonload = function(evt) {
                curronload(evt);
                create_ezolpl(pvID, rv);
            };
            window.onload = newonload;
        } else {
            window.onload = create_ezolpl.bind(null, pvID, rv);
        }
    }
}

__ez.queue.addFunc("attach_ezolpl", "attach_ezolpl", ["a2a652a0-6915-4825-5856-d4bb8fd1ea87", "true"], false, ['/detroitchicago/boise.js'], true, false, false, false);
</script>
<script type="text/javascript">var _audins_dom="wonkeedonkeetools_co_uk",_audins_did=175424;__ez.queue.addFile('/detroitchicago/cmb.js', '//g.ezoic.net/detroitchicago/cmb.js?gcb=194-0&cb=&01&00&03&04&0d&06&07&0a&0c&0e&13&21&01-100-103-1004-10d-506-507-70a-30c-30e-213-321-1&cmbcb=11', true, [], true, false, true, false);</script></head>
<body class="page-template-default page page-id-125569 wpb-js-composer js-comp-ver-7.0.3 vc_responsive elementor-default elementor-kit-255153 elementor-page elementor-page-125569">
	<div class="megatop_wrap">
		<div class="mediad megatop_mediad">
			<script async="" src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
<!-- header -->
<ins class="adsbygoogle" style="display:inline-block;width:728px;height:90px" data-ad-client="ca-pub-9035597241048800" data-ad-slot="6023572390"></ins>
<script>
     (adsbygoogle = window.adsbygoogle || []).push({});
</script>		</div>
	</div>
	   
	
	   <div class="header-other-sites">
       <h4>Our other sites:</h4>
       <div class="other-sites-inner">
           <a href="http://www.wonkeedonkeerichardburbidge.co.uk/" target="_blank"><img src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2020/03/wd-burbidge.jpg"/></a>
           <a href="http://www.wonkeedonkeeforestgarden.co.uk/" target="_blank"><img src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2020/03/wd-forest.jpg"/></a>
           <!--<a href="http://www.wonkeedonkeetools.co.uk/" target="_blank"><img src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2020/03/wd-tools.jpg"></a>-->
           <a href="http://www.wonkeedonkeetrend.co.uk/" target="_blank"><img src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2020/03/wd-trend.jpg"/></a>
           <a href="http://www.wonkeedonkeexljoinery.co.uk/" target="_blank"><img src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2020/03/wd-xl.jpg"/></a>
       </div>
   </div>
	
<!-- Outer Start -->
<div class="rh-outer-wrap">
    <div id="top_ankor"></div>
    <!-- HEADER -->
            <header id="main_header" class="white_style">
            <div class="header_wrap">
                                                <!-- Logo section -->
<div class="logo_section_wrap">
    <div class="rh-container">
        <div class="logo-section rh-flex-center-align tabletblockdisplay header_seven_style clearfix">
            <div class="logo">
          		          			<a href="https://www.wonkeedonkeetools.co.uk" class="logo_image"><img src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2020/02/logo.png" alt="Wonkee Donkee Tools" height="" width=""/></a>
          		       
            </div>                       
            <div class="search head_search">
                                <form role="search" method="get" class="search-form" action="https://www.wonkeedonkeetools.co.uk/">
  	<input type="text" name="s" placeholder="Search" data-posttype="post"/>
  	<input type="hidden" name="post_type" value="post"/>  	<button type="submit" class="btnsearch"><i class="fal fa-search"></i></button>
</form>
            </div>
            <div class=" rh-flex-right-align">
                <div class="header-actions-logo rh-flex-right-align">
                    <div class="tabledisplay">
                         
                         
                                                                                   
                                                                        
                    </div>                     
                </div>  
            </div>                        
        </div>
    </div>
</div>
<!-- /Logo section -->  
<!-- Main Navigation -->
<div class="search-form-inheader header_icons_menu main-nav white_style">  
    <div class="rh-container"> 
	        
        <nav class="top_menu"><ul id="menu-mainmenu" class="menu"><li id="menu-item-254051" class="menu-item menu-item-type-post_type menu-item-object-page"><a href="https://www.wonkeedonkeetools.co.uk/product-learning-index">Product Guides A – Z</a></li>
<li id="menu-item-118075" class="menu-item menu-item-type-custom menu-item-object-custom"><a href="https://www.wonkeedonkeetools.co.uk/about-us">About Us</a></li>
<li id="menu-item-118076" class="menu-item menu-item-type-custom menu-item-object-custom"><a href="https://www.wonkeedonkeetools.co.uk/contact-us/">Contact</a></li>
</ul></nav>        <div class="responsive_nav_wrap"></div>
        <div class="search-header-contents">
            <form role="search" method="get" class="search-form" action="https://www.wonkeedonkeetools.co.uk/">
  	<input type="text" name="s" placeholder="Search" data-posttype="post"/>
  	<input type="hidden" name="post_type" value="post"/>  	<button type="submit" class="btnsearch"><i class="fal fa-search"></i></button>
</form>
            
        </div>
    </div>
</div>
<!-- /Main Navigation -->
            </div>  
        </header>
            
<!-- CONTENT -->
<div class="rh-container def"> 
    <div class="rh-content-wrap clearfix">
        <!-- Main Side -->
        <div class="main-side page clearfix" id="content">
            <div class="rh-post-wrapper">
                                    <div class="title"><h1 class="entry-title">Best Bricklayers Tools</h1></div>
                                <article class="post" id="page-125569">       
                                    		<div data-elementor-type="wp-page" data-elementor-id="125569" class="elementor elementor-125569" data-elementor-settings="[]">
						<div class="elementor-inner">
							<div class="elementor-section-wrap">
							<section class="elementor-section elementor-top-section elementor-element elementor-element-2f0f065f elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="2f0f065f" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-1dd28f55" data-id="1dd28f55" data-element_type="column">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-6930c63a elementor-widget elementor-widget-heading" data-id="6930c63a" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h1 class="elementor-heading-title elementor-size-default">Best Bricklayers Tools</h1>		</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-68c9d690 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="68c9d690" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-c0430ab" data-id="c0430ab" data-element_type="column">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-5c9e3883 elementor-widget elementor-widget-text-editor" data-id="5c9e3883" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><p><em>Welcome to the Wonkee Donkee Tools guide for the best bricklaying tools.</em></p><p>Bricklaying jobs constantly change in terms of size and task difficulty. But one thing for certain, the appropriate <strong>bricklayers’ tools</strong> are required to ensure you maintain your own high standards of work.</p><p>A bricklayer’s tool kit must be used with great care and properly maintained – not only for safety but because <strong>bricklaying tools</strong> can be expensive. When purchasing tools, you must consider how often the tools will be used to make sure they can withstand the work.</p></div>
				</div>
				</div>
				<div class="elementor-element elementor-element-e98f7ab elementor-widget elementor-widget-text-editor" data-id="e98f7ab" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><p>Here at Wonkee Donkee Tools, we offer a comprehensive selection of <strong>bricklayer tools</strong>, ranging from trowels to spirit levels, corner blocks and bolsters. You name it, we supply it.</p><p>As local builders merchants, we understand that selecting  the best tools for bricklaying isn’t easy – especially when there are so many to choose from. However, we know tools like the back of our hand, after all, we have been selling them for more than 100 years! Anything we don’t know about <strong>bricklaying tools</strong> isn’t worth knowing.</p><p>To make sure you’re fully prepared for any job that comes your way, we’ve compiled a list of the very best <strong>bricklayer tools</strong> on the market today – and strive to provide the most competitive prices.</p></div>
				</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-63adb5c2 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="63adb5c2" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-81c8086" data-id="81c8086" data-element_type="column" data-settings="{&#34;background_background&#34;:&#34;classic&#34;}">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-ddfaad0 elementor-widget elementor-widget-heading" data-id="ddfaad0" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">Pointing Trowel</h2>		</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-6a47db55 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="6a47db55" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-4ab30e58" data-id="4ab30e58" data-element_type="column">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-74563d4c elementor-widget elementor-widget-image" data-id="74563d4c" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
											<a href="https://amzn.to/2nb8Ssl" rel="nofollow">
							<img width="300" height="200" src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Pointing-Trowel-1-300x200.jpg" class="attachment-medium size-medium" alt="Pointing Trowel" loading="lazy" srcset="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Pointing-Trowel-1-300x200.jpg 300w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Pointing-Trowel-1-767x510.jpg 767w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Pointing-Trowel-1-1024x681.jpg 1024w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Pointing-Trowel-1-1080x718.jpg 1080w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Pointing-Trowel-1-788x524.jpg 788w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Pointing-Trowel-1-600x399.jpg 600w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Pointing-Trowel-1.jpg 1200w" sizes="(max-width: 300px) 100vw, 300px"/>								</a>
											</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-13074018 elementor-align-center elementor-widget elementor-widget-button" data-id="13074018" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
					<div class="elementor-button-wrapper">
			<a href="https://amzn.to/2nb8Ssl" rel="nofollow" class="elementor-button-link elementor-button elementor-size-sm" role="button">
						<span class="elementor-button-content-wrapper">
						<span class="elementor-button-icon elementor-align-icon-right">
				<i aria-hidden="true" class="far fa-arrow-alt-circle-right"></i>			</span>
						<span class="elementor-button-text">See Latest Prices</span>
		</span>
					</a>
		</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-3b2f0c0d elementor-widget elementor-widget-text-editor" data-id="3b2f0c0d" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><p dir="ltr" style="line-height: 1.38; margin-top: 0pt; margin-bottom: 0pt;"><span id="docs-internal-guid-2b8323dd-7fff-c59e-5650-ff7ba9944ca4" style="font-weight: normal;"><span style="font-size: 12pt; font-family: Arial; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; white-space: pre-wrap;">A pointing trowel is the smallest trowel used by bricklayers. It is typically used for pointing work and any other small jobs that may be required. Blades are usually between 5-6 inches (12-15cm) in length.</span></span></p></div>
				</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-4da9e8b4 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="4da9e8b4" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-19cd0ef7" data-id="19cd0ef7" data-element_type="column" data-settings="{&#34;background_background&#34;:&#34;classic&#34;}">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-78b9eb3b elementor-widget elementor-widget-heading" data-id="78b9eb3b" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">Brick Trowel</h2>		</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-ef0f4b0 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="ef0f4b0" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-4990149a" data-id="4990149a" data-element_type="column">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-4d0f610b elementor-widget elementor-widget-image" data-id="4d0f610b" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
											<a href="https://amzn.to/2oMQPZK" rel="nofollow">
							<img width="300" height="179" src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Trowel-300x179.jpg" class="attachment-medium size-medium" alt="Brick Trowel" loading="lazy" srcset="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Trowel-300x179.jpg 300w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Trowel-766x458.jpg 766w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Trowel-1024x612.jpg 1024w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Trowel-1080x645.jpg 1080w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Trowel-788x470.jpg 788w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Trowel-599x358.jpg 599w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Trowel.jpg 1173w" sizes="(max-width: 300px) 100vw, 300px"/>								</a>
											</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-137ce61d elementor-align-center elementor-widget elementor-widget-button" data-id="137ce61d" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
					<div class="elementor-button-wrapper">
			<a href="https://amzn.to/2oMQPZK" rel="nofollow" class="elementor-button-link elementor-button elementor-size-sm" role="button">
						<span class="elementor-button-content-wrapper">
						<span class="elementor-button-icon elementor-align-icon-right">
				<i aria-hidden="true" class="far fa-arrow-alt-circle-right"></i>			</span>
						<span class="elementor-button-text">See Latest Prices</span>
		</span>
					</a>
		</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-4905d69e elementor-widget elementor-widget-text-editor" data-id="4905d69e" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><p dir="ltr" style="line-height: 1.38; margin-top: 0pt; margin-bottom: 0pt;"><span id="docs-internal-guid-6a9d1914-7fff-16fc-5aea-e523b4e8d097" style="font-weight: normal;"><span style="font-size: 12pt; font-family: Arial; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; white-space: pre-wrap;">The brick trowel is larger than the pointing trowel though similar in shape. Used for picking up and spreading the mortar. Their blades are typically between 10-12 inches (25-30) in length.</span></span></p></div>
				</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-59456cf5 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="59456cf5" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-1877e15c" data-id="1877e15c" data-element_type="column" data-settings="{&#34;background_background&#34;:&#34;classic&#34;}">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-3016d083 elementor-widget elementor-widget-heading" data-id="3016d083" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">Finishing Trowel</h2>		</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-76cdbdd elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="76cdbdd" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-7bfc50ae" data-id="7bfc50ae" data-element_type="column">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-6888a44c elementor-widget elementor-widget-image" data-id="6888a44c" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
											<a href="https://amzn.to/2nbcdHT" rel="nofollow">
							<img width="300" height="141" src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Finishing-Trowel-300x141.jpg" class="attachment-medium size-medium" alt="Finishing Trowel" loading="lazy" srcset="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Finishing-Trowel-300x141.jpg 300w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Finishing-Trowel-767x360.jpg 767w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Finishing-Trowel-1024x481.jpg 1024w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Finishing-Trowel-1080x507.jpg 1080w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Finishing-Trowel-788x369.jpg 788w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Finishing-Trowel-599x281.jpg 599w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Finishing-Trowel.jpg 1500w" sizes="(max-width: 300px) 100vw, 300px"/>								</a>
											</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-58e9ac2e elementor-align-center elementor-widget elementor-widget-button" data-id="58e9ac2e" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
					<div class="elementor-button-wrapper">
			<a href="https://amzn.to/2nbcdHT" rel="nofollow" class="elementor-button-link elementor-button elementor-size-sm" role="button">
						<span class="elementor-button-content-wrapper">
						<span class="elementor-button-icon elementor-align-icon-right">
				<i aria-hidden="true" class="far fa-arrow-alt-circle-right"></i>			</span>
						<span class="elementor-button-text">See Latest Prices</span>
		</span>
					</a>
		</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-32431ee2 elementor-widget elementor-widget-text-editor" data-id="32431ee2" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><p dir="ltr" style="line-height: 1.656; background-color: #ffffff; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-weight: normal;"><span style="font-size: 12pt; font-family: Arial; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; white-space: pre-wrap;">The finishing trowel’s large, flat face allows you to smooth, level or texture the surface coat of mortar, plaster or concrete. </span></span><span style="background-color: transparent; font-family: Arial; font-size: 12pt; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; white-space: pre-wrap;">This is vital to achieving smooth and high quality finishes to jobs. A finishing trowel is a must-have tool for any bricklayer or plasterer who takes pride in high-quality work.</span></p></div>
				</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-80cbb73 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="80cbb73" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-51d1437d" data-id="51d1437d" data-element_type="column" data-settings="{&#34;background_background&#34;:&#34;classic&#34;}">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-2b321cfd elementor-widget elementor-widget-heading" data-id="2b321cfd" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">Flooring Trowel</h2>		</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-f6f95ab elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="f6f95ab" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-afbfbf9" data-id="afbfbf9" data-element_type="column">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-1c5a6e3f elementor-widget elementor-widget-image" data-id="1c5a6e3f" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
											<a href="https://amzn.to/32KqQkI" rel="nofollow">
							<img width="300" height="300" src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Flooring-Trowel-300x300.jpg" class="attachment-medium size-medium" alt="Flooring Trowel" loading="lazy" srcset="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Flooring-Trowel-300x300.jpg 300w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Flooring-Trowel-150x150.jpg 150w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Flooring-Trowel-768x768.jpg 768w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Flooring-Trowel-1024x1024.jpg 1024w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Flooring-Trowel-1080x1080.jpg 1080w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Flooring-Trowel-788x788.jpg 788w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Flooring-Trowel-600x600.jpg 600w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Flooring-Trowel-100x100.jpg 100w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Flooring-Trowel.jpg 1000w" sizes="(max-width: 300px) 100vw, 300px"/>								</a>
											</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-9642c7 elementor-align-center elementor-widget elementor-widget-button" data-id="9642c7" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
					<div class="elementor-button-wrapper">
			<a href="https://amzn.to/32KqQkI" rel="nofollow" class="elementor-button-link elementor-button elementor-size-sm" role="button">
						<span class="elementor-button-content-wrapper">
						<span class="elementor-button-icon elementor-align-icon-right">
				<i aria-hidden="true" class="far fa-arrow-alt-circle-right"></i>			</span>
						<span class="elementor-button-text">See Latest Prices</span>
		</span>
					</a>
		</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-48e3a43f elementor-widget elementor-widget-text-editor" data-id="48e3a43f" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><p dir="ltr" style="line-height: 1.656; background-color: #ffffff; margin-top: 0pt; margin-bottom: 0pt;"><span id="docs-internal-guid-2c65ec24-7fff-9ac5-a823-737da66603d3" style="font-weight: normal;"><span style="font-size: 12pt; font-family: Arial; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; white-space: pre-wrap;">The flooring trowel has a flat face which is squared at one end and pointed at the other. The flooring trowel is so important in making sure that you create an even surface. This design allows it to fit neatly into corners ensuring you can achieve a completely flat finish to a surface.</span></span></p></div>
				</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-10c0294a elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="10c0294a" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-5396b673" data-id="5396b673" data-element_type="column" data-settings="{&#34;background_background&#34;:&#34;classic&#34;}">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-40f68fe5 elementor-widget elementor-widget-heading" data-id="40f68fe5" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">Edging Trowel</h2>		</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-30c6ddd1 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="30c6ddd1" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-3dc398a8" data-id="3dc398a8" data-element_type="column">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-24f520fc elementor-widget elementor-widget-image" data-id="24f520fc" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
											<a href="https://amzn.to/2o8jEjl" rel="nofollow">
							<img width="300" height="155" src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Edging-Trowel-300x155.jpg" class="attachment-medium size-medium" alt="Edging Trowel" loading="lazy" srcset="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Edging-Trowel-300x155.jpg 300w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Edging-Trowel-767x396.jpg 767w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Edging-Trowel-1024x528.jpg 1024w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Edging-Trowel-1080x557.jpg 1080w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Edging-Trowel-788x406.jpg 788w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Edging-Trowel-599x309.jpg 599w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Edging-Trowel.jpg 500w" sizes="(max-width: 300px) 100vw, 300px"/>								</a>
											</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-2bcb399a elementor-align-center elementor-widget elementor-widget-button" data-id="2bcb399a" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
					<div class="elementor-button-wrapper">
			<a href="https://amzn.to/2o8jEjl" rel="nofollow" class="elementor-button-link elementor-button elementor-size-sm" role="button">
						<span class="elementor-button-content-wrapper">
						<span class="elementor-button-icon elementor-align-icon-right">
				<i aria-hidden="true" class="far fa-arrow-alt-circle-right"></i>			</span>
						<span class="elementor-button-text">See Latest Prices</span>
		</span>
					</a>
		</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-44316d69 elementor-widget elementor-widget-text-editor" data-id="44316d69" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><p dir="ltr" style="line-height: 1.38; background-color: #ffffff; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-weight: normal;"><span style="font-size: 12pt; font-family: Arial; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; white-space: pre-wrap;">The edging trowel is essentially a finishing trowel that has a rounded edge, this allows you to make smooth finishes to the corners of your walls. </span></span></p><p dir="ltr" style="line-height: 1.38; background-color: #ffffff; margin-top: 0pt; margin-bottom: 0pt;"><span style="background-color: transparent; font-family: Arial; font-size: 12pt; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; white-space: pre-wrap;"> </span></p><p dir="ltr" style="line-height: 1.38; background-color: #ffffff; margin-top: 0pt; margin-bottom: 0pt;"><span style="background-color: transparent; font-family: Arial; font-size: 12pt; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; white-space: pre-wrap;">The edging trowel is similar to the finishing trowel in that it helps you achieve the perfect finishes on all edges of your work area whether you are working with mortar, concrete or plaster.</span></p></div>
				</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-237908ba elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="237908ba" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-55dd1016" data-id="55dd1016" data-element_type="column" data-settings="{&#34;background_background&#34;:&#34;classic&#34;}">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-474d7ce5 elementor-widget elementor-widget-heading" data-id="474d7ce5" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">Brick Bolster</h2>		</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-5ff874b elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="5ff874b" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-15b92b24" data-id="15b92b24" data-element_type="column">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-2d41ab77 elementor-widget elementor-widget-image" data-id="2d41ab77" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
											<a href="https://amzn.to/2pDM8C7" rel="nofollow">
							<img width="300" height="300" src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Bolster-300x300.jpg" class="attachment-medium size-medium" alt="Brick Bolster" loading="lazy" srcset="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Bolster-300x300.jpg 300w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Bolster-150x150.jpg 150w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Bolster-768x768.jpg 768w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Bolster-1024x1024.jpg 1024w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Bolster-1080x1080.jpg 1080w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Bolster-788x788.jpg 788w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Bolster-600x600.jpg 600w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Bolster-100x100.jpg 100w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Bolster.jpg 500w" sizes="(max-width: 300px) 100vw, 300px"/>								</a>
											</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-82a8cc1 elementor-align-center elementor-widget elementor-widget-button" data-id="82a8cc1" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
					<div class="elementor-button-wrapper">
			<a href="https://amzn.to/2pDM8C7" rel="nofollow" class="elementor-button-link elementor-button elementor-size-sm" role="button">
						<span class="elementor-button-content-wrapper">
						<span class="elementor-button-icon elementor-align-icon-right">
				<i aria-hidden="true" class="far fa-arrow-alt-circle-right"></i>			</span>
						<span class="elementor-button-text">See Latest Prices</span>
		</span>
					</a>
		</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-44da9e0 elementor-widget elementor-widget-text-editor" data-id="44da9e0" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><p dir="ltr" style="line-height: 1.38; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-size: 12pt; font-family: Arial; color: #000000; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">The brick bolster is essentially a cold chisel that has a broad cutting blade used for splitting bricks. Typically struck with a lump hammer. </span></p><p dir="ltr" style="line-height: 1.38; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-size: 12pt; font-family: Arial; color: #000000; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;"> </span></p><p dir="ltr" style="line-height: 1.38; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-size: 12pt; font-family: Arial; color: #000000; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">A brick bolster allows you to concentrate the force of your hammer blows on one area to maximise the impact. </span><span style="background-color: transparent; color: #000000; font-family: Arial; font-size: 12pt; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; white-space: pre-wrap;">This makes it a great tool for a demolition stage when you are removing bricks or tiles for example.</span></p></div>
				</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-58ef0400 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="58ef0400" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-4ccde010" data-id="4ccde010" data-element_type="column" data-settings="{&#34;background_background&#34;:&#34;classic&#34;}">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-7ed953db elementor-widget elementor-widget-heading" data-id="7ed953db" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">Lump Hammer</h2>		</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-19a517f0 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="19a517f0" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-16edf38c" data-id="16edf38c" data-element_type="column">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-9a17e9e elementor-widget elementor-widget-image" data-id="9a17e9e" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
											<a href="https://amzn.to/2o5PVHW" rel="nofollow">
							<img width="300" height="212" src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Lump-Hammer-300x212.jpg" class="attachment-medium size-medium" alt="Lump Hammer" loading="lazy" srcset="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Lump-Hammer-300x212.jpg 300w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Lump-Hammer-767x543.jpg 767w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Lump-Hammer-1024x725.jpg 1024w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Lump-Hammer-400x284.jpg 400w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Lump-Hammer-1080x765.jpg 1080w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Lump-Hammer-788x557.jpg 788w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Lump-Hammer-599x424.jpg 599w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Lump-Hammer.jpg 1500w" sizes="(max-width: 300px) 100vw, 300px"/>								</a>
											</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-3071a000 elementor-align-center elementor-widget elementor-widget-button" data-id="3071a000" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
					<div class="elementor-button-wrapper">
			<a href="https://amzn.to/2o5PVHW" rel="nofollow" class="elementor-button-link elementor-button elementor-size-sm" role="button">
						<span class="elementor-button-content-wrapper">
						<span class="elementor-button-icon elementor-align-icon-right">
				<i aria-hidden="true" class="far fa-arrow-alt-circle-right"></i>			</span>
						<span class="elementor-button-text">See Latest Prices</span>
		</span>
					</a>
		</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-79bbd5a8 elementor-widget elementor-widget-text-editor" data-id="79bbd5a8" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><p dir="ltr" style="line-height: 1.38; background-color: #ffffff; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-weight: normal;"><span style="font-size: 12pt; font-family: Arial; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; white-space: pre-wrap;">A heavy hammer typically weighing 1.2kg (42oz) used with a brick bolster for splitting and cutting bricks. </span></span></p><p dir="ltr" style="line-height: 1.38; background-color: #ffffff; margin-top: 0pt; margin-bottom: 0pt;"><span style="background-color: transparent; font-family: Arial; font-size: 12pt; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; white-space: pre-wrap;"> </span></p><p dir="ltr" style="line-height: 1.38; background-color: #ffffff; margin-top: 0pt; margin-bottom: 0pt;"><span style="background-color: transparent; font-family: Arial; font-size: 12pt; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; white-space: pre-wrap;">A lump hammer can also be used in demolition work to help take down walls or existing structures before you begin your work.</span></p></div>
				</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-636bf24 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="636bf24" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-13b7089d" data-id="13b7089d" data-element_type="column" data-settings="{&#34;background_background&#34;:&#34;classic&#34;}">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-77a5aea7 elementor-widget elementor-widget-heading" data-id="77a5aea7" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">Claw Hammer</h2>		</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-e9a6ef2 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="e9a6ef2" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-25b84b53" data-id="25b84b53" data-element_type="column">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-31fe939f elementor-widget elementor-widget-image" data-id="31fe939f" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
											<a href="https://amzn.to/2o62wed" rel="nofollow">
							<img width="300" height="182" src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Claw-Hammer-300x182.jpg" class="attachment-medium size-medium" alt="Claw hammers can be used to hammer nails as well as pull materials apart." loading="lazy" srcset="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Claw-Hammer-300x182.jpg 300w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Claw-Hammer-766x466.jpg 766w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Claw-Hammer-1024x623.jpg 1024w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Claw-Hammer-1080x657.jpg 1080w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Claw-Hammer-788x479.jpg 788w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Claw-Hammer-599x364.jpg 599w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Claw-Hammer.jpg 500w" sizes="(max-width: 300px) 100vw, 300px"/>								</a>
											</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-21b682d2 elementor-align-center elementor-widget elementor-widget-button" data-id="21b682d2" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
					<div class="elementor-button-wrapper">
			<a href="https://amzn.to/2o62wed" rel="nofollow" class="elementor-button-link elementor-button elementor-size-sm" role="button">
						<span class="elementor-button-content-wrapper">
						<span class="elementor-button-icon elementor-align-icon-right">
				<i aria-hidden="true" class="far fa-arrow-alt-circle-right"></i>			</span>
						<span class="elementor-button-text">See Latest Prices</span>
		</span>
					</a>
		</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-66e97a92 elementor-widget elementor-widget-text-editor" data-id="66e97a92" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><p dir="ltr" style="line-height: 1.38; background-color: #ffffff; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-weight: normal;"><span style="font-size: 12pt; font-family: Arial; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; white-space: pre-wrap;">A claw hammer is a standard piece of equipment for any worker. Used for driving in and prying out nails. </span></span></p><p dir="ltr" style="line-height: 1.38; background-color: #ffffff; margin-top: 0pt; margin-bottom: 0pt;"><span style="background-color: transparent; font-family: Arial; font-size: 12pt; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; white-space: pre-wrap;"> </span></p><p dir="ltr" style="line-height: 1.38; background-color: #ffffff; margin-top: 0pt; margin-bottom: 0pt;"><span style="background-color: transparent; font-family: Arial; font-size: 12pt; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; white-space: pre-wrap;">This can also be a great piece of equipment during a demolition stage or to remove nails and dismantle structures quickly and efficiently.</span></p></div>
				</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-4f582b30 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="4f582b30" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-7c8cf68b" data-id="7c8cf68b" data-element_type="column" data-settings="{&#34;background_background&#34;:&#34;classic&#34;}">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-61b17bcb elementor-widget elementor-widget-heading" data-id="61b17bcb" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">Brick Hammer</h2>		</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-553e8e8d elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="553e8e8d" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-2918f1af" data-id="2918f1af" data-element_type="column">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-6fb9ac16 elementor-widget elementor-widget-image" data-id="6fb9ac16" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
											<a href="https://amzn.to/2OJ7PtT" rel="nofollow">
							<img width="300" height="243" src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Hammer-300x243.jpg" class="attachment-medium size-medium" alt="Brick Hammer" loading="lazy" srcset="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Hammer-300x243.jpg 300w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Hammer-768x622.jpg 768w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Hammer-1024x829.jpg 1024w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Hammer-1080x875.jpg 1080w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Hammer-788x638.jpg 788w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Hammer-600x486.jpg 600w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Hammer.jpg 500w" sizes="(max-width: 300px) 100vw, 300px"/>								</a>
											</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-6019a45d elementor-align-center elementor-widget elementor-widget-button" data-id="6019a45d" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
					<div class="elementor-button-wrapper">
			<a href="https://amzn.to/2OJ7PtT" rel="nofollow" class="elementor-button-link elementor-button elementor-size-sm" role="button">
						<span class="elementor-button-content-wrapper">
						<span class="elementor-button-icon elementor-align-icon-right">
				<i aria-hidden="true" class="far fa-arrow-alt-circle-right"></i>			</span>
						<span class="elementor-button-text">See Latest Prices</span>
		</span>
					</a>
		</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-528f3af2 elementor-widget elementor-widget-text-editor" data-id="528f3af2" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><p><span style="font-weight: normal;"><span style="font-size: 12pt; font-family: Arial; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; white-space: pre-wrap;">The brick hammer is purposely designed for dressing masonry and bricks. The hammer is “T” shaped with one end chisel-shaped and the other end blunt. </span></span><span style="background-color: transparent; font-family: Arial; font-size: 12pt; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; white-space: pre-wrap;">The chisel end is used for chipping away at masonry and the blunt end is used for driving. Great for cutting bricks to the correct size.</span></p></div>
				</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-42ba23b9 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="42ba23b9" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-14bba10e" data-id="14bba10e" data-element_type="column" data-settings="{&#34;background_background&#34;:&#34;classic&#34;}">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-2222a342 elementor-widget elementor-widget-heading" data-id="2222a342" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">Spirit Level (Small, Medium and Large)</h2>		</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-3eb85a99 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="3eb85a99" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-4229e3f3" data-id="4229e3f3" data-element_type="column">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-e933986 elementor-widget elementor-widget-image" data-id="e933986" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
											<a href="https://amzn.to/2pDKIHO" rel="nofollow">
							<img width="300" height="202" src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Spirit-Levels-300x202.jpg" class="attachment-medium size-medium" alt="Spirit levels allow you to check your work is aligned correctly." loading="lazy" srcset="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Spirit-Levels-300x202.jpg 300w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Spirit-Levels-767x517.jpg 767w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Spirit-Levels-1024x690.jpg 1024w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Spirit-Levels-1080x728.jpg 1080w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Spirit-Levels-788x531.jpg 788w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Spirit-Levels-599x404.jpg 599w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Spirit-Levels.jpg 500w" sizes="(max-width: 300px) 100vw, 300px"/>								</a>
											</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-6ba4e72b elementor-align-center elementor-widget elementor-widget-button" data-id="6ba4e72b" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
					<div class="elementor-button-wrapper">
			<a href="https://amzn.to/2pDKIHO" rel="nofollow" class="elementor-button-link elementor-button elementor-size-sm" role="button">
						<span class="elementor-button-content-wrapper">
						<span class="elementor-button-icon elementor-align-icon-right">
				<i aria-hidden="true" class="far fa-arrow-alt-circle-right"></i>			</span>
						<span class="elementor-button-text">See Latest Prices</span>
		</span>
					</a>
		</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-150697d0 elementor-widget elementor-widget-text-editor" data-id="150697d0" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><p><span style="font-weight: normal;"><span style="font-size: 12pt; font-family: Arial; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; white-space: pre-wrap;">Another essential tool for any bricklayer. The spirit level is a straight edge used to check the alignment of the wall. </span></span><span style="background-color: transparent; font-family: Arial; font-size: 12pt; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; white-space: pre-wrap;">It typically has two small windows or vials each containing liquid and an air bubble. When the air bubble lines up with the lines on the vial then your wall is perfectly horizontal or vertical.</span></p><p><span style="font-family: Arial; font-size: 16px; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; text-align: start; white-space: pre-wrap;">Some people take a look at </span><a href="https://www.wonkeedonkeetools.co.uk/best-digital-calipers-review" style="font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; font-size: 16px; font-family: Arial; text-align: start; white-space: pre-wrap;">digital calipers</a><span style="font-family: Arial; font-size: 16px; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; text-align: start; white-space: pre-wrap;"> too.</span><span style="background-color: transparent; font-family: Arial; font-size: 12pt; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; white-space: pre-wrap;"><br/></span></p></div>
				</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-704bf548 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="704bf548" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-3fe9328a" data-id="3fe9328a" data-element_type="column" data-settings="{&#34;background_background&#34;:&#34;classic&#34;}">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-6f9d3021 elementor-widget elementor-widget-heading" data-id="6f9d3021" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">Cold Chisel</h2>		</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-27002a36 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="27002a36" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-2507b2e" data-id="2507b2e" data-element_type="column">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-5ca4f5a3 elementor-widget elementor-widget-image" data-id="5ca4f5a3" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
											<a href="https://amzn.to/2ncNEKH" rel="nofollow">
							<img width="300" height="191" src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Cold-Chisel-Set-300x191.jpg" class="attachment-medium size-medium" alt="Cold Chisel" loading="lazy" srcset="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Cold-Chisel-Set-300x191.jpg 300w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Cold-Chisel-Set-766x489.jpg 766w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Cold-Chisel-Set-1024x653.jpg 1024w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Cold-Chisel-Set-1080x689.jpg 1080w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Cold-Chisel-Set-788x502.jpg 788w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Cold-Chisel-Set-599x382.jpg 599w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Cold-Chisel-Set.jpg 500w" sizes="(max-width: 300px) 100vw, 300px"/>								</a>
											</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-109ee08e elementor-align-center elementor-widget elementor-widget-button" data-id="109ee08e" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
					<div class="elementor-button-wrapper">
			<a href="https://amzn.to/2ncNEKH" rel="nofollow" class="elementor-button-link elementor-button elementor-size-sm" role="button">
						<span class="elementor-button-content-wrapper">
						<span class="elementor-button-icon elementor-align-icon-right">
				<i aria-hidden="true" class="far fa-arrow-alt-circle-right"></i>			</span>
						<span class="elementor-button-text">See Latest Prices</span>
		</span>
					</a>
		</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-2c031c58 elementor-widget elementor-widget-text-editor" data-id="2c031c58" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><p><span style="font-weight: normal;"><span style="font-size: 12pt; font-family: Arial; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; white-space: pre-wrap;">A cold chisel is a simple steel rod with a sharp, shaped cutting end used to chip away mortar and to loosen old brickwork. </span></span><span style="background-color: transparent; font-family: Arial; font-size: 12pt; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; white-space: pre-wrap;">This is a great tool to aid in breaking down existing structures before you start building.</span></p></div>
				</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-7c6c11e8 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="7c6c11e8" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-728f84cf" data-id="728f84cf" data-element_type="column" data-settings="{&#34;background_background&#34;:&#34;classic&#34;}">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-1bfacd10 elementor-widget elementor-widget-heading" data-id="1bfacd10" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">Laser Levels</h2>		</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-71099ce8 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="71099ce8" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-5a5b5432" data-id="5a5b5432" data-element_type="column">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-13651f4 elementor-widget elementor-widget-image" data-id="13651f4" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
											<a href="https://amzn.to/38m4B82" rel="nofollow">
							<img width="300" height="300" src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/12/Laser-Level-300x300.jpg" class="attachment-medium size-medium" alt="laser level" loading="lazy" srcset="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/12/Laser-Level-300x300.jpg 300w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/12/Laser-Level-150x150.jpg 150w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/12/Laser-Level-768x768.jpg 768w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/12/Laser-Level-1024x1024.jpg 1024w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/12/Laser-Level-1080x1080.jpg 1080w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/12/Laser-Level-788x788.jpg 788w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/12/Laser-Level-600x600.jpg 600w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/12/Laser-Level-100x100.jpg 100w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/12/Laser-Level.jpg 1500w" sizes="(max-width: 300px) 100vw, 300px"/>								</a>
											</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-ba54389 elementor-align-center elementor-widget elementor-widget-button" data-id="ba54389" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
					<div class="elementor-button-wrapper">
			<a href="https://amzn.to/38m4B82" rel="nofollow" class="elementor-button-link elementor-button elementor-size-sm" role="button">
						<span class="elementor-button-content-wrapper">
						<span class="elementor-button-icon elementor-align-icon-right">
				<i aria-hidden="true" class="far fa-arrow-alt-circle-right"></i>			</span>
						<span class="elementor-button-text">See Latest Prices</span>
		</span>
					</a>
		</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-896c0c7 elementor-widget elementor-widget-text-editor" data-id="896c0c7" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><p dir="ltr" style="line-height: 1.38; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-weight: normal;"><span style="font-size: 12pt; font-family: Arial; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; white-space: pre-wrap;">A laser level is a device that typically contains an internal spirit level or pendulum level which it self-balances before projecting a beam of light on to a surface. </span></span><span style="background-color: transparent; font-family: Arial; font-size: 12pt; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; white-space: pre-wrap;">The laser signal is sent out to a detector and will signal with a bleep when it is level with the laser. Laser levels can be accurate over 300 metres allowing them to be used for small and large bricklaying jobs. </span><span style="background-color: transparent; font-family: Arial; font-size: 12pt; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; white-space: pre-wrap;">The laser level device allows bricklayers to do high quality work with accuracy easily without the need repeatedly use a spirit level bar.</span></p></div>
				</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-33b37496 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="33b37496" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-1529b28b" data-id="1529b28b" data-element_type="column" data-settings="{&#34;background_background&#34;:&#34;classic&#34;}">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-5485a7bb elementor-widget elementor-widget-heading" data-id="5485a7bb" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">String Line</h2>		</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-244b8dca elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="244b8dca" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-2b0d7d9b" data-id="2b0d7d9b" data-element_type="column">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-3d6831da elementor-widget elementor-widget-image" data-id="3d6831da" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
											<a href="https://amzn.to/2pDYo5B" rel="nofollow">
							<img width="300" height="242" src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/String-Line-300x242.jpg" class="attachment-medium size-medium" alt="String Line" loading="lazy" srcset="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/String-Line-300x242.jpg 300w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/String-Line-767x618.jpg 767w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/String-Line-1024x825.jpg 1024w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/String-Line-1080x870.jpg 1080w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/String-Line-788x634.jpg 788w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/String-Line-600x483.jpg 600w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/String-Line.jpg 1181w" sizes="(max-width: 300px) 100vw, 300px"/>								</a>
											</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-350a0a1b elementor-align-center elementor-widget elementor-widget-button" data-id="350a0a1b" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
					<div class="elementor-button-wrapper">
			<a href="https://amzn.to/2pDYo5B" rel="nofollow" class="elementor-button-link elementor-button elementor-size-sm" role="button">
						<span class="elementor-button-content-wrapper">
						<span class="elementor-button-icon elementor-align-icon-right">
				<i aria-hidden="true" class="far fa-arrow-alt-circle-right"></i>			</span>
						<span class="elementor-button-text">See Latest Prices</span>
		</span>
					</a>
		</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-4b723024 elementor-widget elementor-widget-text-editor" data-id="4b723024" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><p dir="ltr" style="line-height: 1.38; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-weight: normal;"><span style="font-size: 12pt; font-family: Arial; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; white-space: pre-wrap;">Sometimes known as a bricklayer’s line, a string line is used to mark out the course of brickwork so as to keep your walls straight. </span></span><span style="background-color: transparent; font-family: Arial; font-size: 12pt; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; white-space: pre-wrap;">String line has been used for years and is the traditional way for bricklayers to ensure the structures they build are perfectly straight.</span></p></div>
				</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-7b8bcca7 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="7b8bcca7" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-663e382f" data-id="663e382f" data-element_type="column" data-settings="{&#34;background_background&#34;:&#34;classic&#34;}">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-39d2d8c elementor-widget elementor-widget-heading" data-id="39d2d8c" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">Shovel</h2>		</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-581981c9 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="581981c9" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-725c7b31" data-id="725c7b31" data-element_type="column">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-419c3fef elementor-widget elementor-widget-image" data-id="419c3fef" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
											<a href="https://amzn.to/3fRv9l0" rel="nofollow">
							<img width="114" height="300" src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Shovel-1-114x300.jpg" class="attachment-medium size-medium" alt="Shovel" loading="lazy" srcset="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Shovel-1-114x300.jpg 114w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Shovel-1-768x2015.jpg 768w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Shovel-1-390x1024.jpg 390w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Shovel-1-1080x2835.jpg 1080w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Shovel-1-788x2068.jpg 788w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Shovel-1-600x1574.jpg 600w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Shovel-1.jpg 381w" sizes="(max-width: 114px) 100vw, 114px"/>								</a>
											</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-4b9643d9 elementor-align-center elementor-widget elementor-widget-button" data-id="4b9643d9" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
					<div class="elementor-button-wrapper">
			<a href="https://amzn.to/3fRv9l0" rel="nofollow" class="elementor-button-link elementor-button elementor-size-sm" role="button">
						<span class="elementor-button-content-wrapper">
						<span class="elementor-button-icon elementor-align-icon-right">
				<i aria-hidden="true" class="far fa-arrow-alt-circle-right"></i>			</span>
						<span class="elementor-button-text">See Latest Prices</span>
		</span>
					</a>
		</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-1b89b1ba elementor-widget elementor-widget-text-editor" data-id="1b89b1ba" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><p dir="ltr" style="line-height: 1.38; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-size: 12pt; font-family: Arial; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; white-space: pre-wrap;">The humble shovel is easily overlooked as an essential piece of equipment but you cannot get by without one. The wider blade of the shovel is ideal for scooping debris and the rough measuring of materials. </span></p><p dir="ltr" style="line-height: 1.38; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-size: 12pt; font-family: Arial; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; white-space: pre-wrap;">The back of the blade can be used to pat down or smooth off. You can also use it to pry plasterboard from walls if demolishing is necessary. Strong and durable, if well looked after, will last a lifetime.</span></p></div>
				</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-3f8024d0 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="3f8024d0" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-13979694" data-id="13979694" data-element_type="column" data-settings="{&#34;background_background&#34;:&#34;classic&#34;}">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-52678dd9 elementor-widget elementor-widget-heading" data-id="52678dd9" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">Digging Spade</h2>		</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-432135bc elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="432135bc" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-2a1009d8" data-id="2a1009d8" data-element_type="column">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-6a592fca elementor-widget elementor-widget-image" data-id="6a592fca" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
											<a href="https://amzn.to/2OydMuu" rel="nofollow">
							<img width="119" height="300" src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Digging-Spade-119x300.jpg" class="attachment-medium size-medium" alt="Digging Spade" loading="lazy" srcset="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Digging-Spade-119x300.jpg 119w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Digging-Spade-768x1942.jpg 768w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Digging-Spade-405x1024.jpg 405w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Digging-Spade-1080x2732.jpg 1080w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Digging-Spade-788x1993.jpg 788w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Digging-Spade-600x1517.jpg 600w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Digging-Spade.jpg 593w" sizes="(max-width: 119px) 100vw, 119px"/>								</a>
											</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-2b53e46b elementor-align-center elementor-widget elementor-widget-button" data-id="2b53e46b" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
					<div class="elementor-button-wrapper">
			<a href="https://amzn.to/2OydMuu" rel="nofollow" class="elementor-button-link elementor-button elementor-size-sm" role="button">
						<span class="elementor-button-content-wrapper">
						<span class="elementor-button-icon elementor-align-icon-right">
				<i aria-hidden="true" class="far fa-arrow-alt-circle-right"></i>			</span>
						<span class="elementor-button-text">See Latest Prices</span>
		</span>
					</a>
		</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-18b1ae3f elementor-widget elementor-widget-text-editor" data-id="18b1ae3f" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><p dir="ltr" style="line-height: 1.38; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-size: 12pt; font-family: Arial; color: #000000; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">The digging spade is designed for cutting down into the ground and is an all-round versatile tool. This is the perfect tool for preparing trenches ready for walls and structures to be built. </span><span style="background-color: transparent; color: #000000; font-family: Arial; font-size: 12pt; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; white-space: pre-wrap;">It is important you get a high quality digging spade to make this part of the job as easy as possible.</span></p></div>
				</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-7964d65a elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="7964d65a" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-573fb8" data-id="573fb8" data-element_type="column" data-settings="{&#34;background_background&#34;:&#34;classic&#34;}">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-1dd6c29 elementor-widget elementor-widget-heading" data-id="1dd6c29" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">Rabbiting Shovel</h2>		</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-2822b778 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="2822b778" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-4588276b" data-id="4588276b" data-element_type="column">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-601cd237 elementor-widget elementor-widget-image" data-id="601cd237" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
											<a href="https://amzn.to/2IpKCdp" rel="nofollow">
							<img width="58" height="300" src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Rabbitting-Shovel-1-58x300.jpg" class="attachment-medium size-medium" alt="Rabbiting Shovel" loading="lazy" srcset="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Rabbitting-Shovel-1-58x300.jpg 58w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Rabbitting-Shovel-1-768x3986.jpg 768w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Rabbitting-Shovel-1-197x1024.jpg 197w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Rabbitting-Shovel-1-1080x5606.jpg 1080w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Rabbitting-Shovel-1-788x4089.jpg 788w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Rabbitting-Shovel-1-600x3114.jpg 600w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Rabbitting-Shovel-1.jpg 289w" sizes="(max-width: 58px) 100vw, 58px"/>								</a>
											</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-6390a94 elementor-align-center elementor-widget elementor-widget-button" data-id="6390a94" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
					<div class="elementor-button-wrapper">
			<a href="https://amzn.to/2IpKCdp" rel="nofollow" class="elementor-button-link elementor-button elementor-size-sm" role="button">
						<span class="elementor-button-content-wrapper">
						<span class="elementor-button-icon elementor-align-icon-right">
				<i aria-hidden="true" class="far fa-arrow-alt-circle-right"></i>			</span>
						<span class="elementor-button-text">See Latest Prices</span>
		</span>
					</a>
		</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-31a76eac elementor-widget elementor-widget-text-editor" data-id="31a76eac" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><p dir="ltr" style="line-height: 1.38; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-size: 12pt; font-family: Arial; color: #000000; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">The rabbiting shovel is designed specifically for digging post holes and deep narrow trenches. Its thin blade makes digging in the hard ground much easier. </span><span style="background-color: transparent; color: #000000; font-family: Arial; font-size: 12pt; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; white-space: pre-wrap;">Rabbiting shovels create neatly dug holes without disturbing the ground below. This makes them useful for ground possibly containing wiring or pipes.</span></p></div>
				</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-44c3017f elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="44c3017f" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-3b54dbb1" data-id="3b54dbb1" data-element_type="column" data-settings="{&#34;background_background&#34;:&#34;classic&#34;}">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-528e7996 elementor-widget elementor-widget-heading" data-id="528e7996" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">SDS Drill</h2>		</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-69ada17a elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="69ada17a" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-1efe1f4d" data-id="1efe1f4d" data-element_type="column">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-4d9519a2 elementor-widget elementor-widget-image" data-id="4d9519a2" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
											<a href="https://amzn.to/38ncJoZ" rel="nofollow">
							<img width="300" height="152" src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/SDS-Drill-300x152.jpg" class="attachment-medium size-medium" alt="SDS Drill" loading="lazy" srcset="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/SDS-Drill-300x152.jpg 300w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/SDS-Drill-768x390.jpg 768w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/SDS-Drill-1024x520.jpg 1024w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/SDS-Drill-1080x549.jpg 1080w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/SDS-Drill-788x400.jpg 788w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/SDS-Drill-598x304.jpg 598w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/SDS-Drill.jpg 500w" sizes="(max-width: 300px) 100vw, 300px"/>								</a>
											</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-6421fc23 elementor-align-center elementor-widget elementor-widget-button" data-id="6421fc23" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
					<div class="elementor-button-wrapper">
			<a href="https://amzn.to/38ncJoZ" rel="nofollow" class="elementor-button-link elementor-button elementor-size-sm" role="button">
						<span class="elementor-button-content-wrapper">
						<span class="elementor-button-icon elementor-align-icon-right">
				<i aria-hidden="true" class="far fa-arrow-alt-circle-right"></i>			</span>
						<span class="elementor-button-text">See Latest Prices</span>
		</span>
					</a>
		</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-3f6d9390 elementor-widget elementor-widget-text-editor" data-id="3f6d9390" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><p dir="ltr" style="line-height: 1.38; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-weight: normal;"><span style="font-size: 12pt; font-family: Arial; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; white-space: pre-wrap;">You will need a heavy-duty, mains supplied power drill for larger projects. </span></span><span style="background-color: transparent; font-family: Arial; font-size: 12pt; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; white-space: pre-wrap;">It is possible to burn out your standard cordless drill’s motor if it is not sufficiently powerful especially on tasks such as drilling numerous holes in concrete or masonry.</span></p></div>
				</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-2aee88b5 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="2aee88b5" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-49144d84" data-id="49144d84" data-element_type="column" data-settings="{&#34;background_background&#34;:&#34;classic&#34;}">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-61fd4204 elementor-widget elementor-widget-heading" data-id="61fd4204" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">Brick Jointer</h2>		</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-838ddb elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="838ddb" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-3dec1192" data-id="3dec1192" data-element_type="column">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-47c64a39 elementor-widget elementor-widget-image" data-id="47c64a39" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
											<a href="https://amzn.to/2D0XeHO" rel="nofollow">
							<img width="285" height="300" src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Jointer-285x300.jpg" class="attachment-medium size-medium" alt="Brick Jointer" loading="lazy" srcset="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Jointer-285x300.jpg 285w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Jointer-767x807.jpg 767w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Jointer-973x1024.jpg 973w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Jointer-1080x1136.jpg 1080w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Jointer-788x828.jpg 788w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Jointer-600x631.jpg 600w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Jointer.jpg 1426w" sizes="(max-width: 285px) 100vw, 285px"/>								</a>
											</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-5470626 elementor-align-center elementor-widget elementor-widget-button" data-id="5470626" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
					<div class="elementor-button-wrapper">
			<a href="https://amzn.to/2D0XeHO" rel="nofollow" class="elementor-button-link elementor-button elementor-size-sm" role="button">
						<span class="elementor-button-content-wrapper">
						<span class="elementor-button-icon elementor-align-icon-right">
				<i aria-hidden="true" class="far fa-arrow-alt-circle-right"></i>			</span>
						<span class="elementor-button-text">See Latest Prices</span>
		</span>
					</a>
		</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-649e294 elementor-widget elementor-widget-text-editor" data-id="649e294" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><p dir="ltr" style="line-height: 1.38; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-family: Arial;"><span style="font-size: 16px; white-space: pre-wrap;">Jointers are simple metal tools designed for use in finishing your mortar joints. There are several types of jointer all of which give different finishes. </span></span><span style="font-size: 16px; white-space: pre-wrap;">The brick jointer is a key tool to provide neat and professional finishes to brickwork and keeping the customer happy.</span></p></div>
				</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-766674c1 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="766674c1" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-163dcb8f" data-id="163dcb8f" data-element_type="column" data-settings="{&#34;background_background&#34;:&#34;classic&#34;}">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-150036c8 elementor-widget elementor-widget-heading" data-id="150036c8" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">Brick Hod</h2>		</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-51611ca6 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="51611ca6" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-861f64d" data-id="861f64d" data-element_type="column">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-7e89d089 elementor-widget elementor-widget-image" data-id="7e89d089" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
											<a href="https://amzn.to/2oIDAJI" rel="nofollow">
							<img width="300" height="225" src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Hod-300x225.jpg" class="attachment-medium size-medium" alt="Brick hod" loading="lazy" srcset="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Hod-300x225.jpg 300w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Hod-768x576.jpg 768w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Hod-1024x768.jpg 1024w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Hod-510x382.jpg 510w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Hod-1080x810.jpg 1080w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Hod-788x591.jpg 788w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Hod-600x450.jpg 600w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Hod.jpg 500w" sizes="(max-width: 300px) 100vw, 300px"/>								</a>
											</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-5b6930fd elementor-align-center elementor-widget elementor-widget-button" data-id="5b6930fd" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
					<div class="elementor-button-wrapper">
			<a href="https://amzn.to/2oIDAJI" rel="nofollow" class="elementor-button-link elementor-button elementor-size-sm" role="button">
						<span class="elementor-button-content-wrapper">
						<span class="elementor-button-icon elementor-align-icon-right">
				<i aria-hidden="true" class="far fa-arrow-alt-circle-right"></i>			</span>
						<span class="elementor-button-text">See Latest Prices</span>
		</span>
					</a>
		</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-3c8d4590 elementor-widget elementor-widget-text-editor" data-id="3c8d4590" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><p dir="ltr" style="line-height: 1.38; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-size: 12pt; font-family: Arial; color: #000000; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">A brick hod is used to carry bricks and sometimes mortar. Brick hods can help speed up jobs by moving bricks to places where you need them for bricklaying faster. </span><span style="background-color: transparent; color: #000000; font-family: Arial; font-size: 12pt; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; white-space: pre-wrap;">The brick hod is easier to carry around than a wheelbarrow and can be carried up floors and scaffolding.</span></p></div>
				</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-16479114 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="16479114" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-6a7bd2b8" data-id="6a7bd2b8" data-element_type="column" data-settings="{&#34;background_background&#34;:&#34;classic&#34;}">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-5c386a20 elementor-widget elementor-widget-heading" data-id="5c386a20" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">Long Nosed Pliers</h2>		</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-1f2a01ab elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="1f2a01ab" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-53fe3354" data-id="53fe3354" data-element_type="column">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-24c4fa72 elementor-widget elementor-widget-image" data-id="24c4fa72" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
											<a href="https://amzn.to/2oL4joW" rel="nofollow">
							<img width="300" height="203" src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Long-Nosed-Pliers-300x203.jpg" class="attachment-medium size-medium" alt="Long Nosed Pliers" loading="lazy" srcset="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Long-Nosed-Pliers-300x203.jpg 300w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Long-Nosed-Pliers-767x520.jpg 767w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Long-Nosed-Pliers-1024x694.jpg 1024w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Long-Nosed-Pliers-1080x732.jpg 1080w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Long-Nosed-Pliers-788x534.jpg 788w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Long-Nosed-Pliers-599x406.jpg 599w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Long-Nosed-Pliers.jpg 497w" sizes="(max-width: 300px) 100vw, 300px"/>								</a>
											</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-7ca4743a elementor-align-center elementor-widget elementor-widget-button" data-id="7ca4743a" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
					<div class="elementor-button-wrapper">
			<a href="https://amzn.to/2oL4joW" rel="nofollow" class="elementor-button-link elementor-button elementor-size-sm" role="button">
						<span class="elementor-button-content-wrapper">
						<span class="elementor-button-icon elementor-align-icon-right">
				<i aria-hidden="true" class="far fa-arrow-alt-circle-right"></i>			</span>
						<span class="elementor-button-text">See Latest Prices</span>
		</span>
					</a>
		</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-6c5b7578 elementor-widget elementor-widget-text-editor" data-id="6c5b7578" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><p dir="ltr" style="line-height: 1.38; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-family: Arial;"><span style="font-size: 16px; white-space: pre-wrap;">Long nosed pliers are an essential tool for both cutting and holding jobs. They can be used to bend, twist, strip, cut, and reposition wire. They provide excellent control and are ideal for reaching into tight spaces and holes where fingers cannot reach.</span></span></p></div>
				</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-7dee367a elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="7dee367a" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-29d0955a" data-id="29d0955a" data-element_type="column" data-settings="{&#34;background_background&#34;:&#34;classic&#34;}">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-6687746 elementor-widget elementor-widget-heading" data-id="6687746" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">Brick Tongs</h2>		</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-667a474 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="667a474" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-97efa54" data-id="97efa54" data-element_type="column">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-20e0969d elementor-widget elementor-widget-image" data-id="20e0969d" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
											<a href="https://amzn.to/2Or9hSD" rel="nofollow">
							<img width="300" height="300" src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Tongs-300x300.jpg" class="attachment-medium size-medium" alt="Brick Tongs" loading="lazy" srcset="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Tongs-300x300.jpg 300w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Tongs-150x150.jpg 150w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Tongs-768x768.jpg 768w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Tongs-1024x1024.jpg 1024w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Tongs-1080x1080.jpg 1080w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Tongs-788x788.jpg 788w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Tongs-600x600.jpg 600w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Tongs-100x100.jpg 100w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Brick-Tongs.jpg 1500w" sizes="(max-width: 300px) 100vw, 300px"/>								</a>
											</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-534e1e7b elementor-align-center elementor-widget elementor-widget-button" data-id="534e1e7b" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
					<div class="elementor-button-wrapper">
			<a href="https://amzn.to/2Or9hSD" rel="nofollow" class="elementor-button-link elementor-button elementor-size-sm" role="button">
						<span class="elementor-button-content-wrapper">
						<span class="elementor-button-icon elementor-align-icon-right">
				<i aria-hidden="true" class="far fa-arrow-alt-circle-right"></i>			</span>
						<span class="elementor-button-text">See Latest Prices</span>
		</span>
					</a>
		</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-3fe14b1c elementor-widget elementor-widget-text-editor" data-id="3fe14b1c" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><p dir="ltr" style="line-height: 1.38; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-size: 12pt; font-family: Arial; color: #000000; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">Brick tongs are a simple tool that uses lever pressure to keep a number of bricks in place so that they can be easily transported from one place to another by hand. </span><span style="background-color: transparent; color: #000000; font-family: Arial; font-size: 12pt; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; white-space: pre-wrap;">This is especially handy when you are working at different levels or you need to get bricks to hard to reach places. </span></p></div>
				</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-4895dbe1 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="4895dbe1" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-32726049" data-id="32726049" data-element_type="column" data-settings="{&#34;background_background&#34;:&#34;classic&#34;}">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-7eaffb44 elementor-widget elementor-widget-heading" data-id="7eaffb44" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">Broom</h2>		</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-c2e60ce elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="c2e60ce" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-d3c2463" data-id="d3c2463" data-element_type="column">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-19c4e48d elementor-widget elementor-widget-image" data-id="19c4e48d" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
											<a href="https://amzn.to/35diJ1Z" rel="nofollow">
							<img width="251" height="300" src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Broom-251x300.jpg" class="attachment-medium size-medium" alt="Broom" loading="lazy" srcset="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Broom-251x300.jpg 251w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Broom-768x916.jpg 768w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Broom-858x1024.jpg 858w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Broom-1080x1289.jpg 1080w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Broom-788x940.jpg 788w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Broom-599x715.jpg 599w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Broom.jpg 1257w" sizes="(max-width: 251px) 100vw, 251px"/>								</a>
											</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-5a4b9513 elementor-align-center elementor-widget elementor-widget-button" data-id="5a4b9513" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
					<div class="elementor-button-wrapper">
			<a href="https://amzn.to/35diJ1Z" rel="nofollow" class="elementor-button-link elementor-button elementor-size-sm" role="button">
						<span class="elementor-button-content-wrapper">
						<span class="elementor-button-icon elementor-align-icon-right">
				<i aria-hidden="true" class="far fa-arrow-alt-circle-right"></i>			</span>
						<span class="elementor-button-text">See Latest Prices</span>
		</span>
					</a>
		</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-47de979d elementor-widget elementor-widget-text-editor" data-id="47de979d" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><p><span style="font-weight: normal;"><span style="font-size: 12pt; font-family: Arial; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; white-space: pre-wrap;">Show your customers your level of professionalism by keeping a clean and tidy site. </span></span><span style="font-weight: normal;"><span style="font-size: 12pt; font-family: Arial; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; white-space: pre-wrap;">The humble broom can do wonders for your reputation as a diligent worker.</span></span></p></div>
				</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-5231aba1 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="5231aba1" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-36e851f0" data-id="36e851f0" data-element_type="column" data-settings="{&#34;background_background&#34;:&#34;classic&#34;}">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-75d2437d elementor-widget elementor-widget-heading" data-id="75d2437d" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">Corner Blocks</h2>		</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-34cf5802 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="34cf5802" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-1d3e0b5d" data-id="1d3e0b5d" data-element_type="column">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-665e9a6 elementor-widget elementor-widget-image" data-id="665e9a6" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
											<a href="https://amzn.to/2VjjXnR" rel="nofollow">
							<img width="300" height="224" src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Linke-Blocks-300x224.jpg" class="attachment-medium size-medium" alt="Corner Blocks" loading="lazy" srcset="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Linke-Blocks-300x224.jpg 300w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Linke-Blocks-767x572.jpg 767w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Linke-Blocks-1024x764.jpg 1024w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Linke-Blocks-510x382.jpg 510w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Linke-Blocks-1080x806.jpg 1080w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Linke-Blocks-788x587.jpg 788w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Linke-Blocks-599x447.jpg 599w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Linke-Blocks.jpg 1500w" sizes="(max-width: 300px) 100vw, 300px"/>								</a>
											</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-559a5a18 elementor-align-center elementor-widget elementor-widget-button" data-id="559a5a18" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
					<div class="elementor-button-wrapper">
			<a href="https://amzn.to/2VjjXnR" rel="nofollow" class="elementor-button-link elementor-button elementor-size-sm" role="button">
						<span class="elementor-button-content-wrapper">
						<span class="elementor-button-icon elementor-align-icon-right">
				<i aria-hidden="true" class="far fa-arrow-alt-circle-right"></i>			</span>
						<span class="elementor-button-text">See Latest Prices</span>
		</span>
					</a>
		</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-4923c1fb elementor-widget elementor-widget-text-editor" data-id="4923c1fb" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><p dir="ltr" style="line-height: 1.38; margin-top: 0pt; margin-bottom: 0pt;"><span id="docs-internal-guid-392496c5-7fff-534b-62a3-536b3a53cd15" style="font-weight: normal;"><span style="font-size: 12pt; font-family: Arial; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; white-space: pre-wrap;">Corner blocks are used in combination with your string line. They keep the line in place so that your walls don’t wander off-course.</span></span></p></div>
				</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-35af75a7 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="35af75a7" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-12b6f87c" data-id="12b6f87c" data-element_type="column" data-settings="{&#34;background_background&#34;:&#34;classic&#34;}">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-2d1d2adb elementor-widget elementor-widget-heading" data-id="2d1d2adb" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">Rubber Mallet</h2>		</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-3e6a7e0 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="3e6a7e0" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-12ba757" data-id="12ba757" data-element_type="column">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-717f418 elementor-widget elementor-widget-image" data-id="717f418" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
											<a href="https://amzn.to/32FpRW1" rel="nofollow">
							<img width="300" height="218" src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Rubber-Mallet-300x218.jpg" class="attachment-medium size-medium" alt="Rubber Mallet" loading="lazy" srcset="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Rubber-Mallet-300x218.jpg 300w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Rubber-Mallet-767x557.jpg 767w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Rubber-Mallet-1024x743.jpg 1024w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Rubber-Mallet-1080x784.jpg 1080w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Rubber-Mallet-788x572.jpg 788w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Rubber-Mallet-599x435.jpg 599w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Rubber-Mallet.jpg 1500w" sizes="(max-width: 300px) 100vw, 300px"/>								</a>
											</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-8d5843d elementor-align-center elementor-widget elementor-widget-button" data-id="8d5843d" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
					<div class="elementor-button-wrapper">
			<a href="https://amzn.to/32FpRW1" rel="nofollow" class="elementor-button-link elementor-button elementor-size-sm" role="button">
						<span class="elementor-button-content-wrapper">
						<span class="elementor-button-icon elementor-align-icon-right">
				<i aria-hidden="true" class="far fa-arrow-alt-circle-right"></i>			</span>
						<span class="elementor-button-text">See Latest Prices</span>
		</span>
					</a>
		</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-8f5f9ee elementor-widget elementor-widget-text-editor" data-id="8f5f9ee" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><p dir="ltr" style="line-height: 1.38; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-size: 12pt; font-family: Arial; color: #000000; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;">The rubber mallet is often used in bricklaying to knock masonry, slabs, bricks and blocks into position. </span><span style="background-color: transparent; color: #000000; font-family: Arial; font-size: 12pt; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; white-space: pre-wrap;">The weight of the rubber means that little effort is needed to use it and the rubber leaves no mark on your workpieces.</span></p></div>
				</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-4a49b410 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="4a49b410" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-70039daf" data-id="70039daf" data-element_type="column" data-settings="{&#34;background_background&#34;:&#34;classic&#34;}">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-3abb0436 elementor-widget elementor-widget-heading" data-id="3abb0436" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">Tape Measure</h2>		</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-474ff7e2 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="474ff7e2" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-7d247189" data-id="7d247189" data-element_type="column">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-8bc6ff elementor-widget elementor-widget-image" data-id="8bc6ff" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
											<a href="https://amzn.to/2pzuIXa" rel="nofollow">
							<img width="300" height="198" src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Tape-Measure-1-300x198.jpg" class="attachment-medium size-medium" alt="Everyone should own a tape measure it is a key hand tool." loading="lazy" srcset="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Tape-Measure-1-300x198.jpg 300w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Tape-Measure-1-767x506.jpg 767w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Tape-Measure-1-1024x675.jpg 1024w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Tape-Measure-1-1080x712.jpg 1080w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Tape-Measure-1-788x519.jpg 788w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Tape-Measure-1-599x395.jpg 599w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Tape-Measure-1.jpg 999w" sizes="(max-width: 300px) 100vw, 300px"/>								</a>
											</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-4f684ab0 elementor-align-center elementor-widget elementor-widget-button" data-id="4f684ab0" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
					<div class="elementor-button-wrapper">
			<a href="https://amzn.to/2pzuIXa" rel="nofollow" class="elementor-button-link elementor-button elementor-size-sm" role="button">
						<span class="elementor-button-content-wrapper">
						<span class="elementor-button-icon elementor-align-icon-right">
				<i aria-hidden="true" class="far fa-arrow-alt-circle-right"></i>			</span>
						<span class="elementor-button-text">See Latest Prices</span>
		</span>
					</a>
		</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-6e59333c elementor-widget elementor-widget-text-editor" data-id="6e59333c" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><p dir="ltr" style="line-height: 1.38; margin-top: 0pt; margin-bottom: 0pt;"><span id="docs-internal-guid-c3647dea-7fff-9bc0-3b5f-403bcf69e1a0" style="font-weight: normal;"><span style="font-size: 12pt; font-family: Arial; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; white-space: pre-wrap;">Every bricklayer needs one of these on their toolbelt. Used to measure distances. Most tape measures extend up to 5 meters but you can get longer tapes. Retracts back into a handy pocket-sized case.</span></span></p></div>
				</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-3911f22c elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="3911f22c" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-2b3419b3" data-id="2b3419b3" data-element_type="column" data-settings="{&#34;background_background&#34;:&#34;classic&#34;}">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-22b8955 elementor-widget elementor-widget-heading" data-id="22b8955" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">Mortar Board / Hawk</h2>		</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-1c6f2f32 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="1c6f2f32" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-669f16dd" data-id="669f16dd" data-element_type="column">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-13a79d5c elementor-widget elementor-widget-image" data-id="13a79d5c" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
											<a href="https://amzn.to/2pzvt2s" rel="nofollow">
							<img width="300" height="185" src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Mortar-Board-300x185.jpg" class="attachment-medium size-medium" alt="Mortar Board" loading="lazy" srcset="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Mortar-Board-300x185.jpg 300w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Mortar-Board-767x472.jpg 767w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Mortar-Board-1024x630.jpg 1024w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Mortar-Board-1080x664.jpg 1080w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Mortar-Board-788x484.jpg 788w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Mortar-Board-600x369.jpg 600w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Mortar-Board.jpg 1000w" sizes="(max-width: 300px) 100vw, 300px"/>								</a>
											</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-10a9e478 elementor-align-center elementor-widget elementor-widget-button" data-id="10a9e478" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
					<div class="elementor-button-wrapper">
			<a href="https://amzn.to/2pzvt2s" rel="nofollow" class="elementor-button-link elementor-button elementor-size-sm" role="button">
						<span class="elementor-button-content-wrapper">
						<span class="elementor-button-icon elementor-align-icon-right">
				<i aria-hidden="true" class="far fa-arrow-alt-circle-right"></i>			</span>
						<span class="elementor-button-text">See Latest Prices</span>
		</span>
					</a>
		</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-7eb29023 elementor-widget elementor-widget-text-editor" data-id="7eb29023" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><p dir="ltr" style="line-height: 1.38; background-color: #ffffff; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-weight: normal;"><span style="font-size: 12pt; font-family: Arial; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; white-space: pre-wrap;">You will want a mortarboard with a minimum diameter of 12 inches. They are usually made from plastic, metal or wood and have a handle centred on its underside. </span></span><span style="background-color: transparent; font-family: Arial; font-size: 12pt; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; white-space: pre-wrap;">Used for holding and carrying mortar when bricklaying or filling holes in walls.</span></p></div>
				</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-6edae756 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="6edae756" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-5d5dcca2" data-id="5d5dcca2" data-element_type="column" data-settings="{&#34;background_background&#34;:&#34;classic&#34;}">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-71ad5d87 elementor-widget elementor-widget-heading" data-id="71ad5d87" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">Bucket</h2>		</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-376702b elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="376702b" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-54376df1" data-id="54376df1" data-element_type="column">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-5abc7a17 elementor-widget elementor-widget-image" data-id="5abc7a17" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
											<a href="https://amzn.to/2nb1c9n" rel="nofollow">
							<img width="300" height="300" src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Bucket-300x300.jpg" class="attachment-medium size-medium" alt="bucket" loading="lazy" srcset="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Bucket-300x300.jpg 300w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Bucket-150x150.jpg 150w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Bucket-768x768.jpg 768w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Bucket-1024x1024.jpg 1024w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Bucket-1080x1080.jpg 1080w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Bucket-788x788.jpg 788w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Bucket-600x600.jpg 600w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Bucket-100x100.jpg 100w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Bucket.jpg 1002w" sizes="(max-width: 300px) 100vw, 300px"/>								</a>
											</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-35b61366 elementor-align-center elementor-widget elementor-widget-button" data-id="35b61366" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
					<div class="elementor-button-wrapper">
			<a href="https://amzn.to/2nb1c9n" rel="nofollow" class="elementor-button-link elementor-button elementor-size-sm" role="button">
						<span class="elementor-button-content-wrapper">
						<span class="elementor-button-icon elementor-align-icon-right">
				<i aria-hidden="true" class="far fa-arrow-alt-circle-right"></i>			</span>
						<span class="elementor-button-text">See Latest Prices</span>
		</span>
					</a>
		</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-987cb9d elementor-widget elementor-widget-text-editor" data-id="987cb9d" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><p dir="ltr" style="line-height: 1.38; margin-top: 0pt; margin-bottom: 0pt;"><span style="background-color: transparent; font-family: Arial; font-size: 12pt; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; white-space: pre-wrap;">A thoroughly handy tool with multiple uses. </span><span style="background-color: transparent; font-family: Arial; font-size: 12pt; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; white-space: pre-wrap;">You can carry pretty much anything you want in a bucket as well as being able to mix in it and roughly measure your mortar materials.</span></p></div>
				</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-bdef039 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="bdef039" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-54f62f4f" data-id="54f62f4f" data-element_type="column" data-settings="{&#34;background_background&#34;:&#34;classic&#34;}">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-7c8b5de9 elementor-widget elementor-widget-heading" data-id="7c8b5de9" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">Builders Square</h2>		</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-2593e293 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="2593e293" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-31873ed3" data-id="31873ed3" data-element_type="column">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-7e369e0d elementor-widget elementor-widget-image" data-id="7e369e0d" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
											<a href="https://amzn.to/2nfkhHC" rel="nofollow">
							<img width="300" height="225" src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Builders-Square-300x225.jpg" class="attachment-medium size-medium" alt="Builders Square" loading="lazy" srcset="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Builders-Square-300x225.jpg 300w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Builders-Square-768x576.jpg 768w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Builders-Square-1024x768.jpg 1024w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Builders-Square-510x382.jpg 510w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Builders-Square-1080x810.jpg 1080w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Builders-Square-788x591.jpg 788w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Builders-Square-600x450.jpg 600w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Builders-Square.jpg 1192w" sizes="(max-width: 300px) 100vw, 300px"/>								</a>
											</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-3d919203 elementor-align-center elementor-widget elementor-widget-button" data-id="3d919203" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
					<div class="elementor-button-wrapper">
			<a href="https://amzn.to/2nfkhHC" rel="nofollow" class="elementor-button-link elementor-button elementor-size-sm" role="button">
						<span class="elementor-button-content-wrapper">
						<span class="elementor-button-icon elementor-align-icon-right">
				<i aria-hidden="true" class="far fa-arrow-alt-circle-right"></i>			</span>
						<span class="elementor-button-text">See Latest Prices</span>
		</span>
					</a>
		</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-4fdd6d8b elementor-widget elementor-widget-text-editor" data-id="4fdd6d8b" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><p dir="ltr" style="line-height: 1.38; margin-top: 0pt; margin-bottom: 0pt;"><span style="background-color: transparent; font-family: Arial; font-size: 12pt; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; white-space: pre-wrap;">A builder’s square is used for marking out brick and block corners to ensure they are perfect right-angles. </span><span style="background-color: transparent; font-family: Arial; font-size: 12pt; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; white-space: pre-wrap;">The builders square is a traditional tool to make sure that the work completed is high quality and professional. Some newer builders square incorporate spirit levels to help with accuracy.</span></p></div>
				</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-244be1f2 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="244be1f2" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-11851f53" data-id="11851f53" data-element_type="column" data-settings="{&#34;background_background&#34;:&#34;classic&#34;}">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-ce16474 elementor-widget elementor-widget-heading" data-id="ce16474" data-element_type="widget" data-widget_type="heading.default">
				<div class="elementor-widget-container">
			<h2 class="elementor-heading-title elementor-size-default">Cordless Combi Drill</h2>		</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-261f1407 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="261f1407" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
							<div class="elementor-row">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-1dde2b0b" data-id="1dde2b0b" data-element_type="column">
			<div class="elementor-column-wrap elementor-element-populated">
							<div class="elementor-widget-wrap">
						<div class="elementor-element elementor-element-7effaa95 elementor-widget elementor-widget-image" data-id="7effaa95" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
					<div class="elementor-image">
											<a href="https://amzn.to/2o5S2eI" rel="nofollow">
							<img width="236" height="300" src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Cordless-Drill-236x300.jpg" class="attachment-medium size-medium" alt="Cordless combi drill" loading="lazy" srcset="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Cordless-Drill-236x300.jpg 236w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Cordless-Drill-768x974.jpg 768w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Cordless-Drill-807x1024.jpg 807w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Cordless-Drill-1080x1371.jpg 1080w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Cordless-Drill-788x1000.jpg 788w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Cordless-Drill-600x761.jpg 600w, https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/10/Cordless-Drill.jpg 394w" sizes="(max-width: 236px) 100vw, 236px"/>								</a>
											</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-261bcb9 elementor-align-center elementor-widget elementor-widget-button" data-id="261bcb9" data-element_type="widget" data-widget_type="button.default">
				<div class="elementor-widget-container">
					<div class="elementor-button-wrapper">
			<a href="https://amzn.to/2o5S2eI" rel="nofollow" class="elementor-button-link elementor-button elementor-size-sm" role="button">
						<span class="elementor-button-content-wrapper">
						<span class="elementor-button-icon elementor-align-icon-right">
				<i aria-hidden="true" class="far fa-arrow-alt-circle-right"></i>			</span>
						<span class="elementor-button-text">See Latest Prices</span>
		</span>
					</a>
		</div>
				</div>
				</div>
				<div class="elementor-element elementor-element-4857e559 elementor-widget elementor-widget-text-editor" data-id="4857e559" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
					<div class="elementor-text-editor elementor-clearfix"><p dir="ltr" style="line-height: 1.38; margin-top: 0pt; margin-bottom: 0pt;"><span style="font-family: Arial;"><span style="font-size: 16px; white-space: pre-wrap;">A combi drill has multiple functions and can be used to drive screws and drill holes. It really is a must have for anyone who works with tools. </span></span><span style="font-size: 16px; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; font-family: Arial; text-align: start; white-space: pre-wrap;">Sometimes an </span><a style="font-size: 16px; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; font-family: Arial; text-align: start; white-space: pre-wrap;" href="https://www.wonkeedonkeetools.co.uk/best-angle-grinders">angle grinder</a><span style="font-size: 16px; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; font-family: Arial; text-align: start; white-space: pre-wrap;"> can be useful too. </span><span style="font-size: 16px; white-space: pre-wrap;">For bricklayers it can help in building structures and general jobs. Being battery powered also makes the cordless combi drill a dream to use as you can use it anywhere as long as it’s charged. This gets rid of the hassle of finding a plug socket as well as the cord getting in the way. </span></p><p dir="ltr" style="line-height: 1.38; margin-top: 0pt; margin-bottom: 0pt;"> </p></div>
				</div>
				</div>
						</div>
					</div>
		</div>
								</div>
					</div>
		</section>
						</div>
						</div>
					</div>
		                                                          
                </article> 
            </div>         
        </div>	
        <!-- /Main Side --> 
         
            <!-- Sidebar -->
            <aside class="sidebar">            
    <!-- SIDEBAR WIDGET AREA -->
			<div id="custom_html-10" class="widget_text widget widget_custom_html"><div class="textwidget custom-html-widget"><script async="" src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
<!-- widget -->
<ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-9035597241048800" data-ad-slot="4788767376" data-ad-format="auto" data-full-width-responsive="true"></ins>
<script>
     (adsbygoogle = window.adsbygoogle || []).push({});
</script></div></div><div id="ai_widget-8" class="widget ai_widget ai-sticky-widget"><div class="code-block code-block-1" style="margin: 8px 0; clear: both;">
<div id="amzn-assoc-ad-757d6d90-39f2-44fc-8e88-d0506863a616"></div><script async="" src="//z-na.amazon-adsystem.com/widgets/onejs?MarketPlace=US&amp;adInstanceId=757d6d90-39f2-44fc-8e88-d0506863a616"></script></div>
</div>	        
</aside>            <!-- /Sidebar --> 
            </div>
</div>
<!-- /CONTENT -->     
<!-- FOOTER -->
	<div class="rh-container mediad_footer"><div class="clearfix"></div><div class="mediad megatop_mediad"><script async="" src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
<!-- footer ad -->
<ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-9035597241048800" data-ad-slot="6165428220" data-ad-format="auto" data<script="" async="" src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js">
<!-- footer ad -->
<ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-9035597241048800" data-ad-slot="6165428220" data-ad-format="auto" data-full-width-responsive="true"></ins>
<script>
     (adsbygoogle = window.adsbygoogle || []).push({});
</script>-full-width-responsive=&#34;true&#34;&gt;</ins>
<script>
     (adsbygoogle = window.adsbygoogle || []).push({});
</script></div><div class="clearfix"></div></div>			<div id="footercustomarea">	
			<div id="text-4" class="footerside widget_text">			<div class="textwidget"><div id="amzn-assoc-ad-fccf0053-e4ce-447a-b0dd-3dae6aca87e3"></div>
<p><script async="" src="//z-na.amazon-adsystem.com/widgets/onejs?MarketPlace=US&amp;adInstanceId=fccf0053-e4ce-447a-b0dd-3dae6aca87e3"></script></p>
</div>
		</div>		</div>
			
	 				<div class="footer-bottom dark_style">
			<div class="rh-container clearfix">
									<div class="rh-flex-eq-height col_wrap_three">
						<div class="footer_widget col_item">
															<div id="custom_html-4" class="widget_text widget widget_custom_html"><div class="textwidget custom-html-widget"><div class="et_pb_column et_pb_column_1_3 et_pb_column_29    et_pb_css_mix_blend_mode_passthrough">
				
		<br/><br/>		
				<div class="et_pb_module et_pb_text et_pb_text_16 et_pb_bg_layout_light  et_pb_text_align_left">
				
				
				<div class="et_pb_text_inner">
					<h3 style="color:white">Amazon Associate Partners</h3>
				</div>
			</div> <!-- .et_pb_text --><div class="et_pb_module et_pb_text et_pb_text_17 et_pb_bg_layout_light  et_pb_text_align_left">
				
				
				<div class="et_pb_text_inner">
					<p style="color:white">We are a participant in the Amazon Services LLC Associates Program, an affiliate advertising program designed to provide a means for us to earn fees by linking to Amazon.com and affiliated sites</p>
				</div>
			</div> <!-- .et_pb_text -->
	<div class="et_pb_module et_pb_text et_pb_text_17 et_pb_bg_layout_light  et_pb_text_align_left">
				
				
				<div class="et_pb_text_inner">
					<p style="color:white">Tel: <a href="tel:01938557733">+44 1938 557733</a></p>
					<p style="color:white">Email: <a href="mailto:info@wonkeedonkeetools.co.uk">info@wonkeedonkee.co.uk</a></p>
				</div>
			</div>
			</div></div></div>							 
						</div>
						<div class="footer_widget col_item">
															<div id="custom_html-3" class="widget_text widget widget_custom_html"><div class="textwidget custom-html-widget"><div id="outercssDIV_1">
	<div id="outercssDIV_2">
		<div id="outercssDIV_3">
			<ul id="outercssUL_4">
				<li id="outercssLI_5">
					<a href="https://www.wonkeedonkeetools.co.uk/about-us">About Us</a>
				</li>
			</ul>
		</div>
	</div>
	<!-- .et_pb_text -->

	<div id="outercssDIV_6">
		<div id="outercssDIV_7">
			<ul id="outercssUL_8">
				<li id="outercssLI_9">
					<a href="https://www.wonkeedonkeetools.co.uk/terms-and-conditions">Terms &amp; Conditions</a>
				</li>
			</ul>
		</div>
	</div>
	<!-- .et_pb_text -->

	<div id="outercssDIV_10">
		<div id="outercssDIV_11">
			<ul id="outercssUL_12">
				<li id="outercssLI_13">
					<a href="https://www.wonkeedonkeetools.co.uk/privacy-policy">Privacy Policy</a>
				</li>
			</ul>
		</div>
	</div>
	<!-- .et_pb_text -->

	<div id="outercssDIV_14">
		<div id="outercssDIV_15">
			<ul id="outercssUL_16">
				<li id="outercssLI_17">
					<a href="https://www.wonkeedonkeetools.co.uk/contact-us">Contact Us</a>
				</li>
			</ul>
		</div>
	</div>
	<!-- .et_pb_text -->

</div>

<style>
#outercssDIV_1 {
    background-position: 50% 50%;
    bottom: 0px;
    box-sizing: border-box;
    color: rgb(102, 102, 102);
    float: left;
    height: 218px;
    left: 0px;
    position: relative;
    right: 0px;
    text-decoration: none solid rgb(102, 102, 102);
    text-size-adjust: 100%;
    top: 0px;
    width: 295.172px;
    z-index: 9;
    column-rule-color: rgb(102, 102, 102);
    perspective-origin: 147.578px 109px;
    transform-origin: 147.586px 109px;
    caret-color: rgb(102, 102, 102);
    background: rgba(0, 0, 0, 0) none repeat scroll 50% 50% / cover padding-box border-box;
    border: 0px none rgb(102, 102, 102);
    font: normal normal 500 normal 14px / 23.8px "Open Sans", Arial, sans-serif;
    margin: 0px 54.7188px 0px 0px;
    outline: rgb(102, 102, 102) none 0px;
}/*#outercssDIV_1*/

#outercssDIV_1:after {
    color: rgb(102, 102, 102);
    text-decoration: none solid rgb(102, 102, 102);
    text-size-adjust: 100%;
    column-rule-color: rgb(102, 102, 102);
    caret-color: rgb(102, 102, 102);
    border: 0px none rgb(102, 102, 102);
    font: normal normal 500 normal 14px / 23.8px "Open Sans", Arial, sans-serif;
    outline: rgb(102, 102, 102) none 0px;
}/*#outercssDIV_1:after*/

#outercssDIV_1:before {
    color: rgb(102, 102, 102);
    text-decoration: none solid rgb(102, 102, 102);
    text-size-adjust: 100%;
    column-rule-color: rgb(102, 102, 102);
    caret-color: rgb(102, 102, 102);
    border: 0px none rgb(102, 102, 102);
    font: normal normal 500 normal 14px / 23.8px "Open Sans", Arial, sans-serif;
    outline: rgb(102, 102, 102) none 0px;
}/*#outercssDIV_1:before*/

#outercssDIV_2 {
    background-position: 50% 50%;
    box-sizing: border-box;
    color: rgb(255, 255, 255);
    height: 42px;
    overflow-wrap: break-word;
    text-align: left;
    text-decoration: none solid rgb(255, 255, 255);
    text-size-adjust: 100%;
    width: 295.172px;
    column-rule-color: rgb(255, 255, 255);
    perspective-origin: 147.578px 21px;
    transform-origin: 147.586px 21px;
    caret-color: rgb(255, 255, 255);
    animation: 0.2s linear 0s 1 normal none running none;
    background: rgba(0, 0, 0, 0) none no-repeat scroll 50% 50% / cover padding-box border-box;
    border: 0px none rgb(255, 255, 255);
    font: normal normal 500 normal 16px / 23.8px "Open Sans", Arial, sans-serif;
    margin: 50px 0px 0px;
    outline: rgb(255, 255, 255) none 0px;
}/*#outercssDIV_2*/

#outercssDIV_2:after {
    color: rgb(255, 255, 255);
    overflow-wrap: break-word;
    text-align: left;
    text-decoration: none solid rgb(255, 255, 255);
    text-size-adjust: 100%;
    column-rule-color: rgb(255, 255, 255);
    caret-color: rgb(255, 255, 255);
    border: 0px none rgb(255, 255, 255);
    font: normal normal 500 normal 16px / 23.8px "Open Sans", Arial, sans-serif;
    outline: rgb(255, 255, 255) none 0px;
}/*#outercssDIV_2:after*/

#outercssDIV_2:before {
    color: rgb(255, 255, 255);
    overflow-wrap: break-word;
    text-align: left;
    text-decoration: none solid rgb(255, 255, 255);
    text-size-adjust: 100%;
    column-rule-color: rgb(255, 255, 255);
    caret-color: rgb(255, 255, 255);
    border: 0px none rgb(255, 255, 255);
    font: normal normal 500 normal 16px / 23.8px "Open Sans", Arial, sans-serif;
    outline: rgb(255, 255, 255) none 0px;
}/*#outercssDIV_2:before*/

#outercssDIV_3, #outercssDIV_7, #outercssDIV_11, #outercssDIV_15 {
    background-position: 0px 0px;
    bottom: 0px;
    box-sizing: border-box;
    color: rgb(255, 255, 255);
    height: 42px;
    left: 0px;
    overflow-wrap: break-word;
    position: relative;
    right: 0px;
    text-align: left;
    text-decoration: none solid rgb(255, 255, 255);
    text-size-adjust: 100%;
    top: 0px;
    width: 295.172px;
    column-rule-color: rgb(255, 255, 255);
    perspective-origin: 147.578px 21px;
    transform-origin: 147.586px 21px;
    caret-color: rgb(255, 255, 255);
    background: rgba(0, 0, 0, 0) none repeat scroll 0px 0px / auto padding-box border-box;
    border: 0px none rgb(255, 255, 255);
    font: normal normal 500 normal 16px / 23.8px "Open Sans", Arial, sans-serif;
    outline: rgb(255, 255, 255) none 0px;
}/*#outercssDIV_3, #outercssDIV_7, #outercssDIV_11, #outercssDIV_15*/

#outercssDIV_3:after, #outercssDIV_7:after, #outercssDIV_11:after, #outercssDIV_15:after {
    color: rgb(255, 255, 255);
    overflow-wrap: break-word;
    text-align: left;
    text-decoration: none solid rgb(255, 255, 255);
    text-size-adjust: 100%;
    column-rule-color: rgb(255, 255, 255);
    caret-color: rgb(255, 255, 255);
    border: 0px none rgb(255, 255, 255);
    font: normal normal 500 normal 16px / 23.8px "Open Sans", Arial, sans-serif;
    outline: rgb(255, 255, 255) none 0px;
}/*#outercssDIV_3:after, #outercssDIV_7:after, #outercssDIV_11:after, #outercssDIV_15:after*/

#outercssDIV_3:before, #outercssDIV_7:before, #outercssDIV_11:before, #outercssDIV_15:before {
    color: rgb(255, 255, 255);
    overflow-wrap: break-word;
    text-align: left;
    text-decoration: none solid rgb(255, 255, 255);
    text-size-adjust: 100%;
    column-rule-color: rgb(255, 255, 255);
    caret-color: rgb(255, 255, 255);
    border: 0px none rgb(255, 255, 255);
    font: normal normal 500 normal 16px / 23.8px "Open Sans", Arial, sans-serif;
    outline: rgb(255, 255, 255) none 0px;
}/*#outercssDIV_3:before, #outercssDIV_7:before, #outercssDIV_11:before, #outercssDIV_15:before*/

#outercssUL_4, #outercssUL_8, #outercssUL_12, #outercssUL_16 {
    background-position: 0px 0px;
    box-sizing: border-box;
    color: rgb(255, 255, 255);
    height: 42px;
    overflow-wrap: break-word;
    text-align: left;
    text-decoration: none solid rgb(255, 255, 255);
    text-size-adjust: 100%;
    width: 295.172px;
    column-rule-color: rgb(255, 255, 255);
    perspective-origin: 147.578px 21px;
    transform-origin: 147.586px 21px;
    caret-color: rgb(255, 255, 255);
    background: rgba(0, 0, 0, 0) none repeat scroll 0px 0px / auto padding-box border-box;
    border: 0px none rgb(255, 255, 255);
    font: normal normal 500 normal 16px / 26px "Open Sans", Arial, sans-serif;
    margin: 0px;
    outline: rgb(255, 255, 255) none 0px;
    padding: 0px 0px 16px 16px;
}/*#outercssUL_4, #outercssUL_8, #outercssUL_12, #outercssUL_16*/

#outercssUL_4:after, #outercssUL_8:after, #outercssUL_12:after, #outercssUL_16:after {
    color: rgb(255, 255, 255);
    overflow-wrap: break-word;
    text-align: left;
    text-decoration: none solid rgb(255, 255, 255);
    text-size-adjust: 100%;
    column-rule-color: rgb(255, 255, 255);
    caret-color: rgb(255, 255, 255);
    border: 0px none rgb(255, 255, 255);
    font: normal normal 500 normal 16px / 26px "Open Sans", Arial, sans-serif;
    outline: rgb(255, 255, 255) none 0px;
}/*#outercssUL_4:after, #outercssUL_8:after, #outercssUL_12:after, #outercssUL_16:after*/

#outercssUL_4:before, #outercssUL_8:before, #outercssUL_12:before, #outercssUL_16:before {
    color: rgb(255, 255, 255);
    overflow-wrap: break-word;
    text-align: left;
    text-decoration: none solid rgb(255, 255, 255);
    text-size-adjust: 100%;
    column-rule-color: rgb(255, 255, 255);
    caret-color: rgb(255, 255, 255);
    border: 0px none rgb(255, 255, 255);
    font: normal normal 500 normal 16px / 26px "Open Sans", Arial, sans-serif;
    outline: rgb(255, 255, 255) none 0px;
}/*#outercssUL_4:before, #outercssUL_8:before, #outercssUL_12:before, #outercssUL_16:before*/

#outercssLI_5, #outercssLI_9, #outercssLI_13, #outercssLI_17 {
    background-position: 0px 0px;
    box-sizing: border-box;
    color: rgb(255, 255, 255);
    height: 26px;
    overflow-wrap: break-word;
    text-decoration: none solid rgb(255, 255, 255);
    text-size-adjust: 100%;
    width: 279.172px;
    column-rule-color: rgb(255, 255, 255);
    perspective-origin: 139.578px 13px;
    transform-origin: 139.586px 13px;
    caret-color: rgb(255, 255, 255);
    background: rgba(0, 0, 0, 0) none repeat scroll 0px 0px / auto padding-box border-box;
    border: 0px none rgb(255, 255, 255);
    font: normal normal 500 normal 16px / 26px "Open Sans", Arial, sans-serif;
    outline: rgb(255, 255, 255) none 0px;
}/*#outercssLI_5, #outercssLI_9, #outercssLI_13, #outercssLI_17*/

#outercssLI_5:after, #outercssLI_9:after, #outercssLI_13:after, #outercssLI_17:after {
    color: rgb(255, 255, 255);
    overflow-wrap: break-word;
    text-decoration: none solid rgb(255, 255, 255);
    text-size-adjust: 100%;
    column-rule-color: rgb(255, 255, 255);
    caret-color: rgb(255, 255, 255);
    border: 0px none rgb(255, 255, 255);
    font: normal normal 500 normal 16px / 26px "Open Sans", Arial, sans-serif;
    outline: rgb(255, 255, 255) none 0px;
}/*#outercssLI_5:after, #outercssLI_9:after, #outercssLI_13:after, #outercssLI_17:after*/

#outercssLI_5:before, #outercssLI_9:before, #outercssLI_13:before, #outercssLI_17:before {
    color: rgb(255, 255, 255);
    overflow-wrap: break-word;
    text-decoration: none solid rgb(255, 255, 255);
    text-size-adjust: 100%;
    column-rule-color: rgb(255, 255, 255);
    caret-color: rgb(255, 255, 255);
    border: 0px none rgb(255, 255, 255);
    font: normal normal 500 normal 16px / 26px "Open Sans", Arial, sans-serif;
    outline: rgb(255, 255, 255) none 0px;
}/*#outercssLI_5:before, #outercssLI_9:before, #outercssLI_13:before, #outercssLI_17:before*/

#outercssDIV_6, #outercssDIV_10 {
    background-position: 50% 50%;
    box-sizing: border-box;
    color: rgb(255, 255, 255);
    height: 42px;
    overflow-wrap: break-word;
    text-align: left;
    text-decoration: none solid rgb(255, 255, 255);
    text-size-adjust: 100%;
    width: 295.172px;
    column-rule-color: rgb(255, 255, 255);
    perspective-origin: 147.578px 21px;
    transform-origin: 147.586px 21px;
    caret-color: rgb(255, 255, 255);
    animation: 0.2s linear 0s 1 normal none running none;
    background: rgba(0, 0, 0, 0) none no-repeat scroll 50% 50% / cover padding-box border-box;
    border: 0px none rgb(255, 255, 255);
    font: normal normal 500 normal 16px / 23.8px "Open Sans", Arial, sans-serif;
    outline: rgb(255, 255, 255) none 0px;
}/*#outercssDIV_6, #outercssDIV_10*/

#outercssDIV_6:after, #outercssDIV_10:after {
    color: rgb(255, 255, 255);
    overflow-wrap: break-word;
    text-align: left;
    text-decoration: none solid rgb(255, 255, 255);
    text-size-adjust: 100%;
    column-rule-color: rgb(255, 255, 255);
    caret-color: rgb(255, 255, 255);
    border: 0px none rgb(255, 255, 255);
    font: normal normal 500 normal 16px / 23.8px "Open Sans", Arial, sans-serif;
    outline: rgb(255, 255, 255) none 0px;
}/*#outercssDIV_6:after, #outercssDIV_10:after*/

#outercssDIV_6:before, #outercssDIV_10:before {
    color: rgb(255, 255, 255);
    overflow-wrap: break-word;
    text-align: left;
    text-decoration: none solid rgb(255, 255, 255);
    text-size-adjust: 100%;
    column-rule-color: rgb(255, 255, 255);
    caret-color: rgb(255, 255, 255);
    border: 0px none rgb(255, 255, 255);
    font: normal normal 500 normal 16px / 23.8px "Open Sans", Arial, sans-serif;
    outline: rgb(255, 255, 255) none 0px;
}/*#outercssDIV_6:before, #outercssDIV_10:before*/

#outercssDIV_14 {
    background-position: 50% 50%;
    box-sizing: border-box;
    color: rgb(255, 255, 255);
    height: 42px;
    overflow-wrap: break-word;
    text-align: left;
    text-decoration: none solid rgb(255, 255, 255);
    text-size-adjust: 100%;
    width: 295.172px;
    column-rule-color: rgb(255, 255, 255);
    perspective-origin: 147.578px 21px;
    transform-origin: 147.586px 21px;
    caret-color: rgb(255, 255, 255);
    animation: 0.2s linear 0s 1 normal none running none;
    background: rgba(0, 0, 0, 0) none no-repeat scroll 50% 50% / cover padding-box border-box;
    border: 0px none rgb(255, 255, 255);
    font: normal normal 500 normal 16px / 23.8px "Open Sans", Arial, sans-serif;
    outline: rgb(255, 255, 255) none 0px;
}/*#outercssDIV_14*/

#outercssDIV_14:after {
    color: rgb(255, 255, 255);
    overflow-wrap: break-word;
    text-align: left;
    text-decoration: none solid rgb(255, 255, 255);
    text-size-adjust: 100%;
    column-rule-color: rgb(255, 255, 255);
    caret-color: rgb(255, 255, 255);
    border: 0px none rgb(255, 255, 255);
    font: normal normal 500 normal 16px / 23.8px "Open Sans", Arial, sans-serif;
    outline: rgb(255, 255, 255) none 0px;
}/*#outercssDIV_14:after*/

#outercssDIV_14:before {
    color: rgb(255, 255, 255);
    overflow-wrap: break-word;
    text-align: left;
    text-decoration: none solid rgb(255, 255, 255);
    text-size-adjust: 100%;
    column-rule-color: rgb(255, 255, 255);
    caret-color: rgb(255, 255, 255);
    border: 0px none rgb(255, 255, 255);
    font: normal normal 500 normal 16px / 23.8px "Open Sans", Arial, sans-serif;
    outline: rgb(255, 255, 255) none 0px;
}/*#outercssDIV_14:before*/


</style></div></div>							 
						</div>
						<div class="footer_widget col_item last">
															<div id="custom_html-2" class="widget_text widget last widget_custom_html"><div class="textwidget custom-html-widget"><div class="foot-logo"> <a href="https://www.wonkeedonkeetools.co.uk/"><img src="https://www.wonkeedonkeetools.co.uk/wp-content/uploads/2019/09/logo-foot-1.png" alt="Wonkee Donkee Logo"/></a></div></div></div><div id="custom_html-9" class="widget_text widget last widget_custom_html"><div class="textwidget custom-html-widget"></div></div>							 
						</div>
					</div>
									
			</div>	
		</div>
				<footer id="theme_footer" class="dark_style">
			<div class="rh-container clearfix">
				<div class="footer_most_bottom">
					<div class="f_text">
						<span class="f_text_span">2020 Wpsoul.com Design. All rights reserved.</span>
							
					</div>		
				</div>
			</div>
		</footer>
				<!-- FOOTER -->
</div><!-- Outer End -->
<span class="rehub_scroll" id="topcontrol" data-scrollto="#top_ankor"><i class="far fa-chevron-up"></i></span>
<a href="tel:+44 1938 557733" id="callnowbutton" onclick="gtag(&#39;event&#39;, &#39;Call Now Button&#39;, {event_category: &#39;contact&#39;, event_label: &#39;phone&#39;});return gtag_report_conversion(&#39;tel:+44 1938 557733&#39;);"><span>Call Now Button</span></a><div id="amzn-assoc-ad-fccf0053-e4ce-447a-b0dd-3dae6aca87e3"></div><script async="" src="//z-na.amazon-adsystem.com/widgets/onejs?MarketPlace=US&amp;adInstanceId=fccf0053-e4ce-447a-b0dd-3dae6aca87e3"></script>       

     

          

	<script data-wpacu-script-handle="theme_name_scripts" type="text/javascript" src="https://www.wonkeedonkeetools.co.uk/wp-content/plugins/helios-solutions-woocommerce-hide-price-and-add-to-cart-button/js/custom_frontend.js?ver=1.0" id="theme_name_scripts-js"></script>
<script data-wpacu-script-handle="smush-lazy-load" type="text/javascript" src="https://www.wonkeedonkeetools.co.uk/wp-content/plugins/wp-smush-pro/app/assets/js/smush-lazy-load.min.js?ver=3.6.3" id="smush-lazy-load-js"></script>
<script data-wpacu-script-handle="smush-lazy-load" type="text/javascript" id="smush-lazy-load-js-after">
lazySizes.cfg.nativeLoading={setLoadingAttribute:false,disableListeners:{scroll:true}};lazySizes.init();
</script>
<script data-wpacu-script-handle="page-links-to" type="text/javascript" src="https://www.wonkeedonkeetools.co.uk/wp-content/plugins/page-links-to/dist/new-tab.js?ver=3.3.5" id="page-links-to-js"></script>
<script type="text/javascript" id="rehub-js-extra">
/* <![CDATA[ */
var translation = {"back":"back","ajax_url":"\/wp-admin\/admin-ajax.php","templateurl":"https:\/\/www.wonkeedonkeetools.co.uk\/wp-content\/themes\/rehub-theme","fin":"That's all","your_rating":"Your Rating:","nonce":"e38956d91b","hotnonce":"675330b4f8","wishnonce":"1de431c649","rating_tabs_id":"0a85ce026b","max_temp":"10","min_temp":"-10","helpnotnonce":"4211c036df"};
/* ]]> */
</script>
<script data-wpacu-script-handle="rehub" type="text/javascript" src="https://www.wonkeedonkeetools.co.uk/wp-content/themes/rehub-theme/js/custom.js?ver=9.1.3" id="rehub-js"></script>
<script data-wpacu-script-handle="comment-reply" type="text/javascript" src="https://www.wonkeedonkeetools.co.uk/wp-includes/js/comment-reply.min.js?ver=5.7.1" id="comment-reply-js"></script>
<script data-wpacu-script-handle="wp-embed" type="text/javascript" src="https://www.wonkeedonkeetools.co.uk/wp-includes/js/wp-embed.min.js?ver=5.7.1" id="wp-embed-js"></script>
<script data-wpacu-script-handle="elementor-webpack-runtime" type="text/javascript" src="https://www.wonkeedonkeetools.co.uk/wp-content/plugins/elementor/assets/js/webpack.runtime.min.js?ver=3.1.4" id="elementor-webpack-runtime-js"></script>
<script data-wpacu-script-handle="elementor-frontend-modules" type="text/javascript" src="https://www.wonkeedonkeetools.co.uk/wp-content/plugins/elementor/assets/js/frontend-modules.min.js?ver=3.1.4" id="elementor-frontend-modules-js"></script>
<script data-wpacu-script-handle="jquery-ui-core" type="text/javascript" src="https://www.wonkeedonkeetools.co.uk/wp-includes/js/jquery/ui/core.min.js?ver=1.12.1" id="jquery-ui-core-js"></script>
<script data-wpacu-script-handle="elementor-dialog" type="text/javascript" src="https://www.wonkeedonkeetools.co.uk/wp-content/plugins/elementor/assets/lib/dialog/dialog.min.js?ver=4.8.1" id="elementor-dialog-js"></script>
<script data-wpacu-script-handle="elementor-waypoints" type="text/javascript" src="https://www.wonkeedonkeetools.co.uk/wp-content/plugins/elementor/assets/lib/waypoints/waypoints.min.js?ver=4.0.2" id="elementor-waypoints-js"></script>
<script data-wpacu-script-handle="share-link" type="text/javascript" src="https://www.wonkeedonkeetools.co.uk/wp-content/plugins/elementor/assets/lib/share-link/share-link.min.js?ver=3.1.4" id="share-link-js"></script>
<script data-wpacu-script-handle="swiper" type="text/javascript" src="https://www.wonkeedonkeetools.co.uk/wp-content/plugins/elementor/assets/lib/swiper/swiper.min.js?ver=5.3.6" id="swiper-js"></script>
<script data-wpacu-script-handle="elementor-frontend" type="text/javascript" id="elementor-frontend-js-before">
var elementorFrontendConfig = {"environmentMode":{"edit":false,"wpPreview":false,"isScriptDebug":false,"isImprovedAssetsLoading":false},"i18n":{"shareOnFacebook":"Share on Facebook","shareOnTwitter":"Share on Twitter","pinIt":"Pin it","download":"Download","downloadImage":"Download image","fullscreen":"Fullscreen","zoom":"Zoom","share":"Share","playVideo":"Play Video","previous":"Previous","next":"Next","close":"Close"},"is_rtl":false,"breakpoints":{"xs":0,"sm":480,"md":768,"lg":1025,"xl":1440,"xxl":1600},"version":"3.1.4","is_static":false,"experimentalFeatures":[],"urls":{"assets":"https:\/\/www.wonkeedonkeetools.co.uk\/wp-content\/plugins\/elementor\/assets\/"},"settings":{"page":[],"editorPreferences":[]},"kit":{"global_image_lightbox":"yes","lightbox_enable_counter":"yes","lightbox_enable_fullscreen":"yes","lightbox_enable_zoom":"yes","lightbox_enable_share":"yes","lightbox_title_src":"title","lightbox_description_src":"description"},"post":{"id":125569,"title":"Best%20Bricklayers%20Tools%20%E2%80%93%20Wonkee%20Donkee%20Tools","excerpt":"","featuredImage":"https:\/\/www.wonkeedonkeetools.co.uk\/wp-content\/uploads\/2019\/10\/Pointing-Trowel-1-1024x681.jpg"}};
</script>
<script data-wpacu-script-handle="elementor-frontend" type="text/javascript" src="https://www.wonkeedonkeetools.co.uk/wp-content/plugins/elementor/assets/js/frontend.min.js?ver=3.1.4" id="elementor-frontend-js"></script>
<script data-wpacu-script-handle="preloaded-elements-handlers" type="text/javascript" src="https://www.wonkeedonkeetools.co.uk/wp-content/plugins/elementor/assets/js/preloaded-elements-handlers.min.js?ver=3.1.4" id="preloaded-elements-handlers-js"></script>
<script>
/* <![CDATA[ */
ai_front = {"insertion_before":"BEFORE","insertion_after":"AFTER","insertion_prepend":"PREPEND CONTENT","insertion_append":"APPEND CONTENT","insertion_replace_content":"REPLACE CONTENT","insertion_replace_element":"REPLACE ELEMENT","visible":"VISIBLE","hidden":"HIDDEN","fallback":"FALLBACK","automatically_placed":"Automatically placed by AdSense Auto ads code","cancel":"Cancel","use":"Use","add":"Add","parent":"Parent","cancel_element_selection":"Cancel element selection","select_parent_element":"Select parent element","css_selector":"CSS selector","use_current_selector":"Use current selector","element":"ELEMENT","path":"PATH","selector":"SELECTOR"};
/* ]]> */
jQuery(document).ready(function(n){var m=function(c){var g=0,h=15,k=c(document).width();c(".ai-sticky-widget").each(function(){for(var b=c(this),l=b.width(),d=!1,a=b.parent();"BODY"!=a.prop("tagName");){if(a.hasClass("theiaStickySidebar")){d=!0;break}var e=a.parent(),f=e.width();if(f>1.2*l||f>k/2)break;a=e}d||(b=a.offset().top-b.offset().top+h,0==g?("sticky"!=a.css("position")||isNaN(parseInt(a.css("top")))||a.css("top")<b)&&a.css("position",
"sticky").css("position","-webkit-sticky").css("top",b):a.theiaStickySidebar({additionalMarginTop:b,sidebarBehavior:"stick-to-top"}))})};"undefined"==typeof ai_sticky_sidebar_delay&&(ai_sticky_sidebar_delay=200);setTimeout(function(){m(jQuery)},ai_sticky_sidebar_delay)});

ai_js_code = true;

</script>
<span style="display: none;" data-name="wpacu-delimiter" data-content="ASSET CLEANUP NOSCRIPT FOR ASYNC PRELOADS"></span><span style="display: none;" data-name="wpacu-delimiter" content="ASSET CLEANUP NOSCRIPT WEB FONT LOADER"></span>
<script type='text/javascript' style='display:none;' async>
</script>

<script type="text/javascript" data-cfasync="false"></script></body></html>
