---
layout: compress
permalink: /roadmap-landing/
callforaction:
  url:
  text: YES! I want the ROADMAP
  style: success    
callforaction2:
    url:
    text: YES! I want this!
    style: warning    
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
  .buttcent {
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

<body id="top-of-page" class="{{ layout.format }}">
	{% include _navigation.html %}

<!--
  <div class="panel radius" style="background-image: url('/images/racer2.jpg'); background-repeat: no-repeat; background-attachment: fixed;  background-size: 100% 100%; ">
-->

  <div class="row"> <!--display two columns-->
    <div class="column-first left" style="background-color:none;">
        <img src="{{ site.url }}{{ site.baseurl }}/images/roadmap.jpg" alt="">
    </div> <!-- end column left-->
    <div class="column-first right" style="background: #F6DF01; text-align: center">
      <h1>FIX YOUR MARKETING</h1>
      <p><h2>
  		And Increase<br><br>Your Sales & Profits<br><br>In Less Than 45 Minutes As Our<br><br> Software Pinpoints Your 'Opportunity Areas' &<br><br>Shows You Exactly What To Improve</h2>
  		<h4>Simply click on the button below to get started</h4></p>
  		<h4>THIS IS A FREE SERVICE. NO CREDIT CARD REQUIRED</h4><br>
      <h4>We respect your privacy and will never share your details</h4>
    </div> <!-- end column right-->
   <!-- end display two columns-->
  {% comment %}
  *
  * call for action-button
  *
  {% endcomment %}
  <!-- modal 1 -->
    <a href="#m1-o"  class="link-1" id="m1-c" style="float:right">YES!!! I want the ROADMAP ASAP</a>
    <div class="modal-container" id="m1-o" style="--m-background: transparent;">
        <div class="modal">
          <h2 align=center class="modal__title">Please Enter Your Details Here for the Free Roadmap Meeting</h2>
          {% include contactroadmapzoho.html %}
          <h4 align=center >This service is free of charge. We respect your privacy and will never share your details</h4>
          <a href="#m1-c" class="link-2"></a>
        </div> <!--/modal class-->
    </div> <!-- /modal 1 -->
 </div>

<!--</div><!-- end background image-->

<div class="row" style="background-color: rgba(0, 0, 255, 1); background-attachment: fixed;  background-size: 100% 100%;" ><!--Plain background-->

  <div class="row"> <!--display three columns-->

    <div class="column-three" style="background: rgba(0, 0, 255, 1);   text-align: center; color: white;">
    <h1><span style="color:white; font-weight:bold">FREE SERVICE</span></h1><br><br>
    <h5><span style="color:white; font-weight:bold">The Sales Accelerator ROADMAP is normally priced at £495. For a limited time this leading-edge service is <strong>FREE</strong></span></h5>
    </div> <!-- end left3 column-->
    <div class="column-three" style="background: rgba(0, 0, 255, 1);   text-align: center; color: white;">
    <h1><span style="color:white; font-weight:bold">PINPOINT ACCURACY</span></h1>
    <h5><span style="color:white; font-weight:bold">After answering a series of 'yes/no' type questions our software will accurately analyse your sales and marketing</span></h5>
    </div><!-- end center3 column-->
    <div class="column-three" style="background: rgba(0, 0, 255, 1);   text-align: center; color: white;">
    <h1><span style="color:white; font-weight:bold">STEP-BY-STEP</span></h1><br><br>
    <h5><span style="color:white; font-weight:bold">Our software will then give you a step-by-step ROADMAP on what to improve/add in sequential order    </span></h5>
   </div><!-- end right3 column -->
  </div><!-- end display three columns -->
</div><!--end Plain background-->
<div class="row">
    <div class="column" style="background: rgba(255, 255, 255, 1);   text-align: center; color: black;">

    <h1>The ROADMAP Uses 'The FORMULA' Our Proven Business-Building System To Fix Your Marketing, Pinpoint All The Gaps & Provide A Step-By-Step Solution To Grow Quickly</h1>
    <h2>Over 26,000 Businesses Benefiting Right Now</h2><hr>
    </div>
</div> <!--end of row-->

<div class="row" > <!--display two columns-->
  <div class="column-first left" style="background-color:none;">
      <img src="{{ site.url }}{{ site.baseurl }}/images/formula-vert.jpg" alt="">
  </div> <!-- end column left-->
  <div class="column-first right" style="background: rgba(141, 209, 247, 0.8);  text-align: left">
    <h2><span style="color:black; align:center; font-weight:bold">Introducing The FORMULA</span></h2><br><ul>

    <li><h6><strong>PROVEN:</strong>Growing a business isn't rocket science... but it IS a science. The FORMULA is our proven time-tested and robust system for quickly growing any business.</h6></li>

    <li><h6><strong>5 KEY AREAS:</strong> The FORMULA works because it focuses on the 5 primary parts of every business’s sales and marketing. Other than acquisition of other businesses this is the only way to grow a business. Concentrate on these 5 key areas and your business will flourish in any economic climate.</h6></li>

    <li><h6><strong>GAP ANALYSIS:</strong> The Sales Accelerator ROADMAP focuses on each of the 5 key areas of The FORMULA and pinpoints any weaknesses, gaps and areas which will give you the quickest results.</h6></li>

    <li><h6><strong>SPECIAL ALGORITHM:</strong> Because the software uses a special algorithm developed from tens of thousands of businesses in hundreds of different industries, it will identify the areas where you'll see the quickest and biggest returns and provide you with a step-by-step ROADMAP to getting those results.</h6></li>

    <li><h6><strong>QUICK RESULTS:</strong> Most of the solutions identified by our software are quick and easy to put in place. You should start to see results within just a couple of days!</h6></li>

    <li><h6><strong>LOW-COST TO IMPLEMENT:</strong> Better still, the solutions are low-cost – often even zero cost - to implement. With the Sales Accelerator ROADMAP you can grow your business without breaking the bank and still achieve outstanding results even on a shoestring budget if necessary.</h6></li></ul>
  </div> <!-- end column right-->
</div> <!-- end display two columns-->
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
  <a href="#m3-o" class="link-1" id="m3-c">YES! I want the ROADMAP</a>
    <div class="modal-container" id="m3-o" style="--m-background: transparent;">
    <div class="modal" style="--m-shadow: 0 0 10rem 0">
      <h2 align=center class="modal__title">Please Enter Your Details Here for the Free Roadmap Meeting</h2>
      {% include contactroadmapzoho.html %}
      <a href="#m3-c" class="link-2"></a>
    </div>
  </div>
</div>
<!-- /modal 2 -->
{% endif %}
<hr>
<div class="row">
    <div class="column" style="background: rgba(255, 255, 255, 1);  text-align: center; color: black; ">
    <h1>How To Get Started <br>Significant Improvements Within 48 Hours...</h1>
    </div>
</div> <!--end of row-->

<div class="row" > <!--display two columns-->

  <div class="column-second left2" style="background: rgba(141, 209, 247, 0.8);  text-align: left">
  <h3>Within 48 Hours Of Completing The ROADMAP You Can Start Getting Results...</h3><ul>
  <li><h5><strong>STEP #1:</strong> To take advantage of the Sales Accelerator ROADMAP free offer, simply click on the button below (this is a free service, no credit card details are required)...</h5></li>
  <li><h5><strong>STEP #2:</strong> Complete your details on the form.</h5></li>
  <li><h5><strong>STEP #3:</strong> As soon as you complete your details, we'll call you to set up the ROADMAP meeting. This is normally carried out online via Skype.</h5></li>
  <li><h5><strong>STEP #4:</strong> We'll then login to our software and go through the ROADMAP together. There are a series of 'yes/no' type questions that I'll take you through.</h5></li>
  <li><h5><strong>STEP #5:</strong> Once the ROADMAP questions have been completed, our system analyses all the data and uses its special algorithm to create your results.</h5></li>
  <figure>
    <img src="/images/roadmap-result.png/ " class="responsive">
    <figcaption>Partial results from the ROADMAP.</figcaption>
  </figure>
  <li><h5><strong>STEP #6:</strong> Our software then produces the step-by-step ROADMAP to show you exactly what you need to fix your marketing and then what to implement first, second and third to quickly grow your business!</h5></li></ul>

  </div> <!-- end column right-->
  <div class="column-second right2" style="background-color:none;">
      <img src="{{ site.url }}{{ site.baseurl }}/images/roadmap-process.jpg" alt="">
  </div> <!-- end column left-->
</div> <!-- end display two columns-->

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
  <a href="#m3-o" class="link-1" id="m3-c">YES! I want the ROADMAP</a>
    <div class="modal-container" id="m3-o" style="--m-background: transparent;">
    <div class="modal" style="--m-shadow: 0 0 10rem 0">
      <h2 align=center class="modal__title">Please Enter Your Details Here for the Free Roadmap Meeting</h2>
      {% include contactroadmapzoho.html %}
      <a href="#m3-c" class="link-2"></a>
    </div>
  </div>
</div>
<!-- /modal 3 -->
{% endif %}







</body>

{% include _footer.html %}



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
