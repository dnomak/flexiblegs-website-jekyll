---
layout: flexiblegs
dynamic_title: future
permalink: /future/
---

<div class="dn-browser">
  <div class="dn-browser-header">
    <div class="dn-style--title">{{ site.t.[page.language].[page.dynamic_title].title }}</div>
    {% include flexiblegs/logo.html %}
  </div>
  <div class="dn-browser-body">
    <div class="dn-browser-body__item">
      <div class="wrap xl-table xl-gutter-40 xl-top xl-center md-normal">
        <div class="col xl-width-360 md-1-1">
          {% include flexiblegs/social-media.html %}
        </div>
        <div class="col xl-1-1">
          <div class="dn-content">
            {% if page.language == 'en' %}
              <ul>
                <li><a href="https://github.com/flexiblegs/flexiblecss-scss">Flexible Front End Framework</a></li>
                <li><a href="https://github.com/flexiblegs/grid-builder">Flexible Grid Builder</a></li>
                <li>Flexible Front End Editor</li>
                <li>Flexible Cloud (Content Management System)</li>
                <li>Flexible Shop
                  <ul>
                    <li>Mug</li>
                    <li>Shirt</li>
                    <li>Sticker and more :)</li>
                  </ul>
                </li>
                <li>Flexible Space &amp; Cafe
                  <ul>
                    <li>Coffee (Flexible Blend)</li>
                    <li>Carrot Cake and more :)</li>
                  </ul>
                </li>
              </ul>
            {% endif %}
            {% if page.language == 'tr' %}
              <ul>
                <li><a href="https://github.com/flexiblegs/flexiblecss-scss">Flexible Front End Framework</a></li>
                <li><a href="https://github.com/flexiblegs/grid-builder">Flexible Grid Builder</a></li>
                <li>Flexible Front End Editor</li>
                <li>Flexible Cloud (İçerik Yönetim Sistemi)</li>
                <li>Flexible Shop
                  <ul>
                    <li>Mug</li>
                    <li>Shirt</li>
                    <li>Sticker ve daha fazlası :)</li>
                  </ul>
                </li>
                <li>Flexible Space &amp; Cafe
                  <ul>
                    <li>Kahve (Flexible Blend)</li>
                    <li>Havuçlu Kek ve daha fazlası :)</li>
                  </ul>
                </li>
              </ul>
            {% endif %}
            <div class="dn-height-16"></div>
            {% if page.language == 'en' %}
              <p>To make our future plans a reality you can support us via PayPal.</p>
            {% endif %}
            {% if page.language == 'tr' %}
              <p>Gelecek planlarını daha hızlı uygulayabilmemiz için PayPal aracılığıyla bağış yapabilirsiniz.</p>
            {% endif %}
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
