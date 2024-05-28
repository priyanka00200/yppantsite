---
layout: home
lang-ref: home-page
title: ""
background:
    class: inverted
    image:
        url: "assets/css/images/pillars-of-creation.webp"
        position: right
        size: 100% 100%
header:
    title: "Dr. Y.P. Pant"
    subtitle: "Research And Development Foundation"
banner:
    title: ""
    subtitle: ""
    description: 
        
    button:
        url: "#contact"
        label: "Contact Us"
---
{%- assign facts = site.data.home.facts[page.lang] -%}
{%- assign features = site.data.home.features[page.lang] -%}
<!-- Section -->
<section>
       <div class="posts">
      {% include post.html target-url="en/generic" image-src="assets/images/placeholder/team.jpg" image-placeholder-src="assets/images/content/team.jpg" image-alt-text="" title="Our Team" content="Dr. Y.P. Pant Foundation has been established in memory of late Dr. Yadav Prasad Pant." %}
         {% include post.html target-url="en/vitae" image-src="assets/images/placeholder/ypmain.png" image-placeholder-src="assets/images/content/ypmain.png" image-alt-text="" title="Dr. Yadav Pant" content="Dr. Pant was the first Ph.D in Nepal" %}
          {% include post.html target-url="home/priyanka/Documents/ypsite_design/yp_site/contact" image-src="assets/images/placeholder/con.png" image-placeholder-src="assets/images/content/con.png" image-alt-text="" title="Contact" content="" %}
     </div>
</section>
{% include contact.html show_name=true show_email=true show_phone=true show_street_address=true %}
