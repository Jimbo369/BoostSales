---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
# Black background "#262930"
layout: default
offer: false
#header:
#  image-fullwidth: "/images/blueback.webp"
#  background-color:  "#6AB4D9"
#  title: Need To Boost Sales<br> and Grow Profits?<br>This Masterclass shows you how<br> GUARANTEED!!
#  subtitle:
#  description: <h2>...learn the secrets right here! </h2>

#callforaction2:
#  url: '/roadmap-landing/'
#  text: Limited Offer - FREE Bespoke Roadmap for your Business Worth over £495! Click NOW!
#  style: success
permalink: /oldindex.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---


<div class="container" style="height:200px;width:100%; text-align:center; background-color: light-blue">
  <p><h1>How To Boost Sales and Grow Profits!<br><br>This Masterclass shows you how<br> ...GUARANTEED!!</h1></p>

  <iframe src="/images/gallery-example-1.jpg" width="80%" height="300" title="Masterclass Introduction">
  </iframe>

  <div class="row"> <!--Call to callforaction-->
    <button type="button" class="btn btn-success btn-lg btn-block" data-toggle="modal" data-target="#rmModal1" data-backdrop="static">Reserve Your Place Now!</button>
    <!-- Modal -->
    <div class="modal fade" id="rmModal1" role="dialog">
      <div class="modal-dialog">
        <!-- Modal content-->
        <div class="modal-content">
          <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal">&times;</button>
            <h4 class="modal-title">Please Enter Your Details - Get Immediate Access</h4>
          </div> <!--Close Modal header-->
          <div class="modal-body">
            {% include payment-master.html %}
          </div> <!--Close modal body-->
          <div class="modal-footer">
            <a class="text-align:left">We respect your privacy and will never share your details   </a>
            <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
          </div> <!--Close Modal Footer-->
        </div>
      </div> <!--close modal dialog-->
    </div>
  </div> <!--end of Call to Action-->   
</div>
