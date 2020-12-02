---
permalink: /modaltest/
---

<head>
<link rel= "stylesheet" href="/assets/css/modalstyle.css">
</head>
<body>
<!-- title -->
<div class="box">
  <h1 class="box__title">Modals</h1>
  <p class="box__p">Click / Enter the buttons to open modals.</p>
</div>
<!-- /title -->


<!-- modal 1 -->
<div class="box">
  <a href="#m1-o" class="link-1" id="m1-c">YES! I want the ROADMAP</a>
  <div class="modal-container" id="m1-o" style="--m-background: transparent;">
    	<div class="modal">
      	<h2 align=center class="modal__title">Please Enter Your Details Here for the Free Roadmap Meeting</h2>
				{%include contactzoho.html%}
      	<a href="#m1-c" class="link-2"></a>
    	</div> <!--/modal class-->
  </div>
</div>
<!-- /modal 1 -->


<!-- modal 2 -->
<div class="box">
  <a href="#m2-o" class="link-1" id="m2-c">I Want This!</a>
    <div class="modal-container" id="m2-o" style="--m-background: transparent;">
    <div class="modal">
      <h2 align=center class="modal__title">Please Enter Your Details Here for the Free Roadmap Meeting</h2>
      {%include contactzoho.html%}
      <a href="#m2-c" class="link-2"></a>
    </div>
  </div>
</div>
<!-- /modal 2 -->

<!-- modal 3 -->
<div class="box">
  <a href="#m3-o" class="link-1" id="m3-c">YES! I want the ROADMAP</a>
    <div class="modal-container" id="m3-o" style="--m-background: transparent;">
    <div class="modal" style="--m-shadow: 0 0 10rem 0">
      <h2 align=center class="modal__title">Please Enter Your Details Here for the Free Roadmap Meeting</h2>
			{%include contactzoho.html%}
      <a href="#m3-c" class="link-2"></a>
    </div>
  </div>
</div>
<!-- /modal 3 -->



</body>
