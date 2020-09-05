---
layout: splash
permalink: /
hidden: true
title: "Budgeting as Easy as ABC"
tagline: "Download on your device for free!"
header:
  overlay_image: /assets/images/bg-pattern.png
  actions:
    - label: "<i class='fab fa-apple'></i> <span class='badge__storename'>App Store</span>"
      url: "https://itunes.apple.com/us/app/budget-badger/id1436425263"
    - label: "<i class='fab fa-google-play'></i> <span class='badge__storename'>Google Play</span>"
      url: "https://play.google.com/store/apps/details?id=com.BayWolfStudios.BudgetBadger"
    - label: "<i class='fab fa-apple'></i> <span class='badge__storename'>Mac App Store</span>"
      url: "https://itunes.apple.com/us/app/budget-badger-expense-tracker/id1462666544?mt=12"
    - label: "<i class='fab fa-windows'></i> <span class='badge__storename'>Microsoft Store</span>"
      url: "https://www.microsoft.com/store/apps/9NPS726FKXTT"

feature_row1:
  - image_path: /assets/images/web-add-the-money-you-have-now.png
    title: "Add the money you have now"
    excerpt: 'Add all of the cash, bank, and credit card account balances in the app to see how much money you have right now'
feature_row2:
  - image_path: /assets/images/web-budget-it-into-envelopes.png
    title: "Budget it into envelopes"
    excerpt: 'Using the money you have right now, budget it into the envelopes based on your priority'
feature_row3:
  - image_path: /assets/images/web-cover-the-unexpected.png
    title: "Cover the unexpected"
    excerpt: "Life throws curve balls, Budget Badger makes them easier to handle by allowing you to adjust your budget on the fly"
feature_row4:
  - image_path: /assets/images/mary.jpg
    excerpt: "Mary"
    title: "I love Budget Badger Pro! It's simple to use. It's not so highly structured --it's MY budget."
  - image_path: /assets/images/elliot.jpg
    excerpt: "Elliot"
    title: "This has so much potential. It is already so much better than the vast majority of others out there."
  - image_path: /assets/images/rockmysocks42.jpg
    excerpt: "Rockmysocks42"
    title: "This is exactly what we have been looking for in a budget app for the last 5 or so years."
feature_row5:
  - image_path: /assets/images/web-add-the-money-you-have-now.png
    title: "Add the money you have now"
    excerpt: 'Add all of the cash, bank, and credit card account balances in the app to see how much money you have right now'
  - image_path: /assets/images/web-budget-it-into-envelopes.png
    title: "Budget it into envelopes"
    excerpt: 'Using the money you have right now, budget it into the envelopes based on your priority'
  - image_path: /assets/images/web-cover-the-unexpected.png
    title: "Cover the unexpected"
    excerpt: "Life throws curve balls, Budget Badger makes them easier to handle by allowing you to adjust your budget on the fly"
---

{% include feature_row id="feature_row1" type="left" %}

{% include feature_row id="feature_row2" type="right" %}

{% include feature_row id="feature_row3" type="left" %}

<div class="feature__wrapper" style="border-bottom: 0px;">
    <div class="feature__item--center">
        <div class="archive__item">
            <div class="archive__item-body">
                <h1 class="archive__item-title" style="text-align: center;">What people are saying</h1>
            </div>
        </div>
    </div>
</div>

{% include testimonial_row id="feature_row4" %}

<div class="feature__wrapper" style="border-bottom: 0px;">
    <div class="feature__item--center">
        <div class="archive__item">
            <div class="archive__item-body">
                <h1 class="archive__item-title" style="text-align: center;">{{ site.data.ui-text[site.locale].recent_posts | default: "Recent Posts" }}</h1>
            </div>
        </div>
    </div>
</div>

<div class="grid__wrapper">
  {% for post in site.posts limit:4 %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
