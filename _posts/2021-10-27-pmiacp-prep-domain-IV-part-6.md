---
layout: post
title:  "PMI ACP Prep Test Question - Domain IV - Part 6"
author: hiepvh
categories: [ PMI ACP ]
tags: [ pmi-acp, pm ]
image: assets/images/domain4.png
description: "Quản lý dự án là nghề làm dâu trăm họ, nhưng niềm vui là được học hỏi mỗi ngày, mỗi giờ, mỗi thời điểm."
featured: false
hidden: false
# rating: 4.5
---

{% include  buttonCustomize.html %}

<!-- Title Block -->
<div id="titleBlock" style="text-align: center;">
  <h4 style="margin-bottom: 0px;"> PREP TEST QUESTION - DOMAIN IV - PART 6</h4>
  <hr style="width: 50%;">
</div>

{:#tblContent}
| PREP TEST QUESTION - DOMAIN IV |
|-----|
| [PREP TEST QUESTION - DOMAIN IV - PART 1]({{ site.baseurl }}/pmiacp-prep-domain-IV-part-1) |
| [PREP TEST QUESTION - DOMAIN IV - PART 2]({{ site.baseurl }}/pmiacp-prep-domain-IV-part-2) |
| [PREP TEST QUESTION - DOMAIN IV - PART 3]({{ site.baseurl }}/pmiacp-prep-domain-IV-part-3) |
| [PREP TEST QUESTION - DOMAIN IV - PART 4]({{ site.baseurl }}/pmiacp-prep-domain-IV-part-4) |
| [PREP TEST QUESTION - DOMAIN IV - PART 5]({{ site.baseurl }}/pmiacp-prep-domain-IV-part-5) |
| [PREP TEST QUESTION - DOMAIN IV - PART 6]({{ site.baseurl }}/pmiacp-prep-domain-IV-part-6) |

{% for ques in site.data.domain004.questions limit:11 offset:49 %}
<!-- QUESTION -->
<div class="text-card">
  <div class="heading">
    <h5>Question {{ques.quesNo ques.answer}} </h5>
    <h6>{{ques.content}}</h6>
  </div>

  <div class="headingAnswer">
    <!-- Answer A -->
    <div class="flip">
      <div class="flipContent">
        <div class="front">
          {{ques.A}}
        </div>
        {% if (ques.answer == 'A') %}
          <div class="back" style="display: block">Correct</div>
        {% else %}  
          <div class="back">NOOOOOOOO</div>
        {% endif %}
      </div>
    </div>
    <br class="clear" />
    <!-- Answer B -->
    <div class="flip">
      <div class="flipContent">
        <div class="front">
          {{ques.B}}
        </div>
        {% if (ques.answer == 'B') %}
          <div class="back" style="display: block">Correct</div>
        {% else %}  
          <div class="back">NOOOOOOOO</div>
        {% endif %}
      </div>
    </div>
    <!-- Answer C -->
    <div class="flip">
      <div class="flipContent">
        <div class="front">
          {{ques.C}}
        </div>
        {% if (ques.answer == 'C') %}
          <div class="back">Correct</div>
        {% else %}  
          <div class="back">NOOOOOOOO</div>
        {% endif %}
      </div>
    </div>
    <!-- Answer D -->
    <div class="flip">
      <div class="flipContent">
        <div class="front">
          {{ques.D}}
        </div>
        {% if (ques.answer == 'D') %}
          <div class="back">Correct</div>
        {% else %}  
          <div class="back">NOOOOOOOO</div>
        {% endif %}
      </div>
    </div>
    <!-- Note--> 
    <div class="text-box-note">
      <h6>{{ques.note}}</h6>
    </div>
  </div>

</div>
{% endfor %}