---
layout: default
dynamic_title: install
permalink: /install/
---

<div class="dn-browser">
  <div class="dn-browser-header">
    {% include browser-button.html %}
    <div class="dn-style--title">{{ site.t.[page.language].[page.dynamic_title].title }}</div>
    {% include logo.html %}
  </div>
  <div class="dn-browser-body">
    <div class="dn-browser-body__item">
      <div class="dn-content">
        {% if page.language == 'en' %}
          <p>Before installation, we assume that you know <b>HTML</b>, <b>CSS</b>, <b>Sass</b>, <b>Less</b> or <b>Stylus</b>.</p>
        {% endif %}
        {% if page.language == 'tr' %}
          <p>Kuruluma başlamadan önce <b>HTML</b>, <b>CSS</b> veya <b>Sass</b>, <b>Less</b> yada <b>Stylus</b> bilmeniz gerekmektedir.</p>
        {% endif %}
        <div class="dn-space-16"></div>
        {% if page.language == 'en' %}
          <p>There are two methods of developing with Flexible Grid System. These methods are Static and Dynamic. You can use the both method at the same time or independently.</p>
        {% endif %}
        {% if page.language == 'tr' %}
          <p>Flexible Grid System ile kod yazmanın iki yöntemi bulunmaktadır. Bunlar Statik ve Dinamik olmak üzere ikiye ayrılır. İki yöntemi aynı anda yada ayrı ayrı kullanmanız mümkündür.</p>
        {% endif %}
        <div class="wrap xl-gutter-24 xl-top xl-2 lg-1">
          <div class="col">
            <div class="dn-space-24"></div>
            {% if page.language == 'en' %}
              <p><b>Static</b></p>
            {% endif %}
            {% if page.language == 'tr' %}
              <p><b>Statik</b></p>
            {% endif %}
            <div class="dn-space-8"></div>
            {% if page.language == 'en' %}
              <p>If you choose the Static method. You can use CSS <b>class</b>es to code your <b>HTML</b>.</p>
            {% endif %}
            {% if page.language == 'tr' %}
              <p>Statik yönetimi tercih ederseniz Flexible Grid System'in CSS ile hazırlanmış sabit <b>class</b>larını kullanarak <b>HTML</b> kısmında kodlama yapabilirsiniz.</p>
            {% endif %}
            <div class="dn-space-16"></div>
            {% if page.language == 'en' %}
              <ul>
                <li><a href="/install/css/">CSS</a> or <a href="/install/bem/">BEM</a></li>
                <li><span class="line-through">Scss</span></li>
                <li><span class="line-through">Sass <a href="https://github.com/flexiblegs/flexiblegs-sass">(Preparing)</a></span></li>
                <li><span class="line-through">Less</span></li>
                <li><span class="line-through">Stylus</span></li>
              </ul>
            {% endif %}
            {% if page.language == 'tr' %}
              <ul>
                <li><a href="/tr/install/css/">CSS</a> veya <a href="/tr/install/bem/">BEM</a></li>
                <li><span class="line-through">Scss</span></li>
                <li><span class="line-through">Sass <a href="https://github.com/flexiblegs/flexiblegs-sass">(Hazırlanıyor)</a></span></li>
                <li><span class="line-through">Less</span></li>
                <li><span class="line-through">Stylus</span></li>
              </ul>
            {% endif %}
          </div>
          <div class="col">
            <div class="dn-space-24"></div>
            {% if page.language == 'en' %}
              <p><b>Dynamic</b></p>
            {% endif %}
            {% if page.language == 'tr' %}
              <p><b>Dinamik</b></p>
            {% endif %}
            <div class="dn-space-8"></div>
            {% if page.language == 'en' %}
              <p>If you choose the Dynamic method. You can use Sass, Less or Stylus <b>mixin</b>s to code your <b>CSS</b>.</p>
            {% endif %}
            {% if page.language == 'tr' %}
              <p>Dinamik yöntemi tercih ederseniz Flexible Grid System'in Sass, Less veya Stylus ile hazırlanmış <b>mixin</b>lerini kullanarak <b>CSS</b> kısmında kodlama yapabilirsiniz.</p>
            {% endif %}
            <div class="dn-space-16"></div>
            {% if page.language == 'en' %}
              <ul>
                <li><a href="/install/scss-plus/">Scss Plus</a></li>
                <li><a href="/install/sass-plus/">Sass Plus</a></li>
                <li><a href="/install/less-plus/">Less Plus</a></li>
                <li><a href="/install/stylus-plus/">Stylus Plus</a></li>
              </ul>
            {% endif %}
            {% if page.language == 'tr' %}
              <ul>
                <li><a href="/tr/install/scss-plus/">Scss Plus</a></li>
                <li><a href="/tr/install/sass-plus/">Sass Plus</a></li>
                <li><a href="/tr/install/less-plus/">Less Plus</a></li>
                <li><a href="/tr/install/stylus-plus/">Stylus Plus</a></li>
              </ul>
            {% endif %}
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
