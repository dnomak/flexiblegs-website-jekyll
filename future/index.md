---
layout: default
dynamic_title: future
permalink: /future/
---

<div class="dn-browser">
  <div class="dn-browser-header">
    {% include browser-button.html %}
    <div class="dn-style--title">{{ site.t.[page.language].[page.dynamic_title].title }}</div>
    {% include logo.html %}
  </div>
  <div class="dn-browser-body">
    <div class="dn-browser-body__item">
      <div class="wrap xl-gutter-24 xl-top xl-center">
        <!-- <div class="col xl-3-10">
          <div class="dn-height-8"></div>
          <iframe width="100%" height="180" src="https://www.youtube.com/embed/Vj7NZ6FiQvo?autoplay=0&amp;showinfo=0&amp;rel=0&amp;start=9" frameborder="0" allowfullscreen="" data-reactid=".0.0.0.0"></iframe>
        </div> -->
        <div class="col xl-7-10 lg-1-1">
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
            <div class="dn-height-16"></div>
            <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top" style="text-align: left;">
              <input type="hidden" name="cmd" value="_s-xclick">
              <input type="hidden" name="hosted_button_id" value="NHEUHUB8863NS">
              <input type="image" src="/img/paypal-logo.svg" border="0" name="submit" alt="PayPal - The safer, easier way to pay online!">
              <img alt="" border="0" src="https://www.paypalobjects.com/tr_TR/i/scr/pixel.gif" width="1" height="1" alt="PayPal">
            </form>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
