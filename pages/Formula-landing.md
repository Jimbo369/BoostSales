---
layout: default
permalink: /formula-landing/
offer: true

do_not_compress: true      
---
<div class="container-float" style="background-image: url('/images/onepagebackground.png'); background-repeat: cover; background-attachment: float;  background-size: 100% 100%; ">
    <div class="row"> <!--display two columns-->
        <div class="col-sm-4" style="background-color:none; margin: 50px 0px; padding:5px">
        <img src="{{ site.url }}{{ site.baseurl }}/images/onepageblur.png" alt="">
        </div> <!-- end column left-->
        <div class="col-sm-8" style="background: rgba(255, 255, 255, 0.7); margin: 30px 0px; padding:5px; text-align: center">
          <h2 color="white">1-Page BUSINESS GROWTH FORMULA</h2><br>
          <h1>FREE DOWNLOAD</h1>
          <p><h2>Everything You Need To Grow<br>Your Business Quickly & Cost<br> Effectively On One Page<br></h2>
      		<h4>Simply click on the button below to get started</h4></p>
          <div class="row"> <!--Call to callforaction-->
            <button type="button" class="btn btn-success btn-lg " data-toggle="modal" data-target="#rmModal1" data-backdrop="static">Download NOW!</button>
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
                    {% include contactonepagezoho.html %}
                  </div> <!--Close modal body-->
                  <div class="modal-footer">
                    <a class="text-align:left">We respect your privacy and will never share your details   </a>
                    <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
                  </div> <!--Close Modal Footer-->
                </div>
              </div> <!--close modal dialog-->
            </div>
          </div> <!--end of Call to Action-->   
          <h6>We respect your privacy and will never share your details</h6>          
        </div> <!-- end column right-->
    </div>   <!-- end display two columns-->
</div> <!--end of background-->
