---
layout: page-fullwidth
title: "Lead Generation"
subheadline: "The L "
meta_teaser: "The methodology of lead generation."
teaser: "<em>Lead Generation</em> is not just important to a business, it is critical.  Leads are the lifeblood of a company because they develop into sales."
breadcrumb: false
header:
    image: gallery-example-1.jpg
    background-color: "#262930"
    caption:
    caption_url:
image:
    thumb:  gallery-example-1-thumb.jpg
    homepage: homepage_typography.jpg
    caption:
    caption_url: ""
categories:
  - The Formula
  - Marketing Elements
callforaction2:
    url: /contact/
    text: Learn How to Boost Lead Generation - Contact us Now!
    style: success

---
<div id="header-home">
    <div class="row">
        <div class="small-12 columns">
        </div><!-- /.medium-4.columns -->
    </div><!-- /.row -->
</div><!-- /#header-home -->
<!--more-->
<div class="row">
<div class="medium-4 medium-push-8 columns" markdown="1">
<div class="panel radius" markdown="1">
****
{: #toc }
> <span class="teaser">"Make sure to choose the correct media to suit the target market!"</span><cite>[Steve Hackney, The Core Asset]</cite>
{:toc}
</div>
</div><!-- /.medium-4.columns -->

<div class="medium-8 medium-pull-4 columns" markdown="1">

## Lead Generation - Business Lifeblood

There are multiple ways to generate sales leads.  One of the most common mistakes many organisations make is to stick to just one or two avenues for lead generation.  It is vitally important to use as many ways as possible to obtain more leads.  Some will be better than others for your particular business or industry.  

So how do you find these dozens of ways to generate leads?  

Our programme will not just show you what they are but will guide you through using and implementing them.  What to use and when...the infrastructure you need to have in place - what to do and when to do it.

> <span class="teaser">"This system shows you all you need to know to grow your sales - from acquiring clients to looking after them, it has changed my business massively!"</span><cite>[Brendon Jones,Lansdorne]</cite>

{% comment %}
*
* First check, if there is a call for action-button
*
{% endcomment %}

{% if page.callforaction.url contains 'http' %}
{% assign url = '' %}
{% else %}
{% capture url %}{{ site.url }}{{ site.baseurl }}{% endcapture %}
{% endif %}

{% if page.callforaction %}
    <div class="row t60 b60">
        <div class="small-12 text-center columns">
            <a class="button large radius {{ page.callforaction.style }}" href="{{ url }}{{ page.callforaction.url }}"{% if page.callforaction.url contains 'http' %} target="_blank" {% endif %}>{{ page.callforaction.text }}</a>
        </div><!-- /.small-12.columns -->
    </div><!-- /.row -->
{% endif %}


 <hr>
  <!-- Display list of blog posts - marketing components -->
 <div class="medium-10 columns">
         <p><strong>{{ site.data.language.more_articles }}</strong></p>
         {% include list-posts entries='8' offset='0' %}
 </div><!-- /.medium-10.columns -->


</div><!-- /.medium-8.columns -->
</div><!-- /.row -->
