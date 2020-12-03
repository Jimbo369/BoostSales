---
layout: compress
permalink: /formula-landing/
callforaction:
  url:
  text:
  style:     
callforaction2:
    url:
    text:
    style:   
do_not_compress: true      
---

<html class="no-js" lang="{% if site.language == nil %}en{% else %}{{ site.language }}{% endif %}">
<head>

	{% include _head.html %}
	<meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel= "stylesheet" href="/assets/css/modalstyle.css">

<style>
* { box-sizing: border-box;
}
.buttcent{
  margin: 0;
  position: absolute;

  left: 75%;
  -ms-transform: translate(50%, 50%);
  transform: translate(-100%, -100%);
}
@media screen and (max-width: 900px) {
  .butcent {
    width: 100%;
  }}
<!--/* Create two unequal columns that floats next to each other */ -->
.column-first {
  float: left;
  padding: 10px;
}

.left {
  width: 40%;
}

.right {
  width: 60%;
}

.column-second {
  float: left;
  padding: 10px;
}
.left2 {
  width: 60%;
}

.right2 {
  width: 40%;
}
/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

<!--/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */ -->
@media screen and (max-width: 600px) {
  .column-first {
    width: 100%;
  }
@media screen and (max-width: 600px) {
  .column-second {
    width: 100%;
  }
}

body {
  font-size: 100%
}
</style>
<style>
* {
  box-sizing: border-box;
}
/* Create single floating column */
.column {
  float: center;
  width: 100%;
  padding: 10px;
  }
@media screen and (max-width: 900px) {
    .column {
      width: 100%;
    }
  }
/* Create three equal columns that floats next to each other */
.column-three {
  float: left;
  width: 33.33%;
  padding: 10px;
}


@media screen and (max-width: 600px) {
  .column-three {
    width: 100%;
  }
}
/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
</style>


  <link rel="stylesheet" type="text/css" href="https://cdn.wpcc.io/lib/1.0.2/cookieconsent.min.css"/><script src="https://cdn.wpcc.io/lib/1.0.2/cookieconsent.min.js" defer></script><script>window.addEventListener("load", function(){window.wpcc.init({"border":"thin","corners":"small","colors":{"popup":{"background":"#edfdfa","text":"#000000","border":"#5ec2b6"},"button":{"background":"#5ec2b6","text":"#ffffff"}},"position":"bottom","content":{"href":"https://www.superneconsulting.co.uk/cookies","message":"This website uses cookies to ensure you get the best experience.  ","button":"OK I understand!"}})});</script>

</head>

<body >
	{% include _navigation.html %}

<div class="panel radius" style="background-image: url('/images/onepagebackground.png'); background-repeat: repeat; background-attachment: fixed;  background-size: 100% 100%; ">
    <div class="row"> <!--display two columns-->
        <div class="column-first left" style="background-color:none;">
        <!-- Empty left column-->
        </div> <!-- end column left-->
        <div class="column-first right" style="background: rgba(255, 255, 255, 0.6);  text-align: center">
          <h2 color="white">1-Page BUSINESS GROWTH FORMULA</h2><br>
          <h1>FREE DOWNLOAD</h1>
          <p><h2>Everything You Need To Grow<br><br>Your Business Quickly & Cost<br><br> Effectively On One Page<br><br></h2>
      		<h4>Simply click on the button below to get started</h4></p>
          <h4>We respect your privacy and will never share your details</h4>
        </div> <!-- end column right-->
    </div>   <!-- end display two columns-->
    {% comment %}
    *
    * call for action-button
    *
    {% endcomment %}
    {% if page.callforaction.url contains 'http' %}
    {% assign url = '' %}
    {% else %}

    {% capture url %}{{ site.url }}{{ site.baseurl }}{% endcapture %}
    {% endif %}
    {% if page.callforaction %}
    <!-- modal 3 -->
    <div class="box">
      <a href="#m3-o" class="link-1" >DOWNLOAD HERE</a>
        <div class="modal-container" id="m3-o" style="--m-background: hsla(0, 0%, 0%, 0.4);">
        <div class="modal" style="--m-shadow: 0 0 10rem 0">
          <h4 align=center class="modal__title">Please Enter Your Details Here to Get The Download</h4>
          {% include contactonepagezoho.html %}
          <h4 align=center >This service is FREE of charge <br>We respect your privacy and will never share your details</h4>
          <a href="#m3-c" class="link-2"></a>
        </div>
      </div>
    </div>
    <!-- /modal 2 -->
    {% endif %}
</div> <!--end of background-->
</body>


<!-- Include LinkedIn script -->
<script type="text/javascript">
		_linkedin_partner_id = "1107945";
		window._linkedin_data_partner_ids = window._linkedin_data_partner_ids || [];
		window._linkedin_data_partner_ids.push(_linkedin_partner_id);
		</script><script type="text/javascript">
		(function(){var s = document.getElementsByTagName("script")[0];
		var b = document.createElement("script");
		b.type = "text/javascript";b.async = true;
		b.src = "https://snap.licdn.com/li.lms-analytics/insight.min.js";
		s.parentNode.insertBefore(b, s);})();
</script>

<noscript>
	<img height="1" width="1" style="display:none;" alt="" src="https://px.ads.linkedin.com/collect/?pid=1107945&fmt=gif" />
</noscript>

</html>
