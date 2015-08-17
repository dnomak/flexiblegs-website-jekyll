---
layout: default
title: wrap(masonry,@width)
permalink: /learn/masonry/
---

<div id="css">
  <div class="dn-browser">
    <div class="dn-browser-header">
      {% include browser-button.html %}
      <div class="dn-style--title">{% include learn/masonry/title.html %} (css)</div>
      {% include logo.html %}
    </div>
    <div class="dn-browser-body">
      <div class="dn-browser-body__pre">
        <pre class="not-compiled"><div class="dn-tag dn-tag--gray dn-tag--top dn-tag--button"><i class="fa fa-magic fa-lg"></i></div><div class="dn-tag dn-tag--gray dn-tag--bottom">.html</div><!--
          -->&lt;div class="wrap xl-gutter-24 xl-top <span>xl-masonry-3</span>"&gt;<br/><!--
          -->  &lt;div class="col xl-1-1"&gt;01&lt;/div&gt;<br/><!--
          -->  &lt;div class="col xl-1-3"&gt;02&lt;/div&gt;<br/><!--
          -->  &lt;div class="col xl-1-3"&gt;03&lt;/div&gt;<br/><!--
          -->  &lt;div class="col xl-1-3"&gt;04&lt;/div&gt;<br/><!--
          -->  &lt;div class="col xl-1-1"&gt;05&lt;/div&gt;<br/><!--
          -->  &lt;div class="col xl-1-2"&gt;06&lt;/div&gt;<br/><!--
          -->  &lt;div class="col xl-1-2"&gt;07&lt;/div&gt;<br/><!--
          -->  &lt;div class="col xl-1-1"&gt;08&lt;/div&gt;<br/><!--
          -->&lt;/div&gt;<!--
          --><div class="comment">&lt;!-- 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12 --&gt;</div><!--
        --></pre>
        {% include learn/masonry/compiled.html %}
      </div>
      {% include learn/masonry/preview.html %}
      <div class="dn-browser-footer">
        <div class="wrap xl-gutter-24 xl-outside-24 xl-center xl-auto">
          <div class="col">
            <a href="http://codepen.io/dnomak/pen/yNGxyZ?editors=110" class="dn-button dn-button--link">http://codepen.io/dnomak/pen/yNGxyZ</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<div id="bem">
  <div class="dn-browser">
    <div class="dn-browser-header">
      {% include browser-button.html %}
      <div class="dn-style--title">{% include learn/masonry/title.html %} (bem)</div>
      {% include logo.html %}
    </div>
    <div class="dn-browser-body">
      <div class="dn-browser-body__pre">
        <pre class="not-compiled"><div class="dn-tag dn-tag--gray dn-tag--top dn-tag--button"><i class="fa fa-magic fa-lg"></i></div><div class="dn-tag dn-tag--gray dn-tag--bottom">.html</div><!--
          -->&lt;div class="wrap wrap--xl-gutter-24 wrap--xl-top <span>wrap--xl-masonry-3</span>"&gt;<br/><!--
          -->  &lt;div class="wrap__col wrap__col--xl-1-1"&gt;01&lt;/div&gt;<br/><!--
          -->  &lt;div class="wrap__col wrap__col--xl-1-3"&gt;02&lt;/div&gt;<br/><!--
          -->  &lt;div class="wrap__col wrap__col--xl-1-3"&gt;03&lt;/div&gt;<br/><!--
          -->  &lt;div class="wrap__col wrap__col--xl-1-3"&gt;04&lt;/div&gt;<br/><!--
          -->  &lt;div class="wrap__col wrap__col--xl-1-1"&gt;05&lt;/div&gt;<br/><!--
          -->  &lt;div class="wrap__col wrap__col--xl-1-2"&gt;06&lt;/div&gt;<br/><!--
          -->  &lt;div class="wrap__col wrap__col--xl-1-2"&gt;07&lt;/div&gt;<br/><!--
          -->  &lt;div class="wrap__col wrap__col--xl-1-1"&gt;08&lt;/div&gt;<br/><!--
          -->&lt;/div&gt;<!--
          --><div class="comment">&lt;!-- 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12 --&gt;</div><!--
        --></pre>
        {% include learn/masonry/compiled.html %}
      </div>
      {% include learn/masonry/preview.html %}
      <div class="dn-browser-footer">
        <div class="wrap xl-gutter-24 xl-outside-24 xl-center xl-auto">
          <div class="col">
            <a href="https://github.com/flexiblegs/flexiblegs-bem" class="dn-button dn-button--link">https://github.com/flexiblegs/flexiblegs-bem</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<div id="scss-plus">
  <div class="dn-browser">
    <div class="dn-browser-header">
      {% include browser-button.html %}
      <div class="dn-style--title">{% include learn/masonry/title.html %} (scss-plus)</div>
      {% include logo.html %}
    </div>
    <div class="dn-browser-body">
      <div class="dn-browser-body__pre">
        <div class="wrap xl-top xl-gutter-24 xl-2 lg-1">
          {% include learn/masonry/dynamic.html %}
          <div class="col">
            <pre class="not-compiled"><div class="dn-tag dn-tag--gray dn-tag--top dn-tag--button"><i class="fa fa-magic fa-lg"></i></div><div class="dn-tag dn-tag--gray dn-tag--bottom">.scss</div><!--
              -->.example {<br/><!--
              -->  @include wrap;<br/><!--
              -->  @include wrap(gutter,24px);<br/><!--
              -->  @include wrap(top);<br/><!--
              -->  @include <span>wrap(masonry,3)</span>;<br/><!--
              -->  &__item {<br/><!--
              -->    @include col;<br/><!--
              -->    &.one {<br/><!--
              -->      @include col(1,1);<br/><!--
              -->    }<br/><!--
              -->    &.two {<br/><!--
              -->      @include col(1,2);<br/><!--
              -->    }<br/><!--
              -->    &.three {<br/><!--
              -->      @include col(1,3);<br/><!--
              -->    }<br/><!--
              -->  }<br/><!--
              -->}<!--
            --></pre>
            {% include learn/masonry/compiled.html %}
          </div>
        </div>
      </div>
      {% include learn/masonry/preview.html %}
      <div class="dn-browser-footer">
        <div class="wrap xl-gutter-24 xl-outside-24 xl-center xl-auto">
          <div class="col">
            <a href="https://github.com/flexiblegs/flexiblegs-scss-plus" class="dn-button dn-button--link">https://github.com/flexiblegs/flexiblegs-scss-plus</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<div id="sass-plus">
  <div class="dn-browser">
    <div class="dn-browser-header">
      {% include browser-button.html %}
      <div class="dn-style--title">{% include learn/masonry/title.html %} (sass-plus)</div>
      {% include logo.html %}
    </div>
    <div class="dn-browser-body">
      <div class="dn-browser-body__pre">
        <div class="wrap xl-top xl-gutter-24 xl-2 lg-1">
          {% include learn/masonry/dynamic.html %}
          <div class="col">
            <pre class="not-compiled"><div class="dn-tag dn-tag--gray dn-tag--top dn-tag--button"><i class="fa fa-magic fa-lg"></i></div><div class="dn-tag dn-tag--gray dn-tag--bottom">.sass</div><!--
              -->.example<br/><!--
              -->  +wrap<br/><!--
              -->  +wrap(gutter,24px)<br/><!--
              -->  +wrap(top)<br/><!--
              -->  +<span>wrap(masonry,3)</span><br/><!--
              -->  &__item<br/><!--
              -->    +col<br/><!--
              -->    &.one<br/><!--
              -->      +col(1,1)<br/><!--
              -->    &.two<br/><!--
              -->      +col(1,2)<br/><!--
              -->    &.three<br/><!--
              -->      +col(1,3)<br/><!--
            --></pre>
            {% include learn/masonry/compiled.html %}
          </div>
        </div>
      </div>
      {% include learn/masonry/preview.html %}
      <div class="dn-browser-footer">
        <div class="wrap xl-gutter-24 xl-outside-24 xl-center xl-auto">
          <div class="col">
            <a href="https://github.com/flexiblegs/flexiblegs-sass-plus" class="dn-button dn-button--link">https://github.com/flexiblegs/flexiblegs-sass-plus</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<div id="less-plus">
  <div class="dn-browser">
    <div class="dn-browser-header">
      {% include browser-button.html %}
      <div class="dn-style--title">{% include learn/masonry/title.html %} (less-plus)</div>
      {% include logo.html %}
    </div>
    <div class="dn-browser-body">
      <div class="dn-browser-body__pre">
        <div class="wrap xl-top xl-gutter-24 xl-2 lg-1">
          {% include learn/masonry/dynamic.html %}
          <div class="col">
            <pre class="not-compiled"><div class="dn-tag dn-tag--gray dn-tag--top dn-tag--button"><i class="fa fa-magic fa-lg"></i></div><div class="dn-tag dn-tag--gray dn-tag--bottom">.less</div><!--
              -->.example {<br/><!--
              -->  .wrap;<br/><!--
              -->  .wrap(gutter,24px);<br/><!--
              -->  .wrap(top);<br/><!--
              -->  .<span>wrap(masonry,3)</span>;<br/><!--
              -->  &__item {<br/><!--
              -->    .col;<br/><!--
              -->    &.one {<br/><!--
              -->      .col(1,1);<br/><!--
              -->    }<br/><!--
              -->    &.two {<br/><!--
              -->      .col(1,2);<br/><!--
              -->    }<br/><!--
              -->    &.three {<br/><!--
              -->      .col(1,3);<br/><!--
              -->    }<br/><!--
              -->  }<br/><!--
              -->}<!--
              -->}<!--
            --></pre>
            {% include learn/masonry/compiled.html %}
          </div>
        </div>
      </div>
      {% include learn/masonry/preview.html %}
      <div class="dn-browser-footer">
        <div class="wrap xl-gutter-24 xl-outside-24 xl-center xl-auto">
          <div class="col">
            <a href="https://github.com/flexiblegs/flexiblegs-less-plus" class="dn-button dn-button--link">https://github.com/flexiblegs/flexiblegs-less-plus</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<div id="stylus-plus">
  <div class="dn-browser">
    <div class="dn-browser-header">
      {% include browser-button.html %}
      <div class="dn-style--title">{% include learn/masonry/title.html %} (stylus-plus)</div>
      {% include logo.html %}
    </div>
    <div class="dn-browser-body">
      <div class="dn-browser-body__pre">
        <div class="wrap xl-top xl-gutter-24 xl-2 lg-1">
          {% include learn/masonry/dynamic.html %}
          <div class="col">
            <pre class="not-compiled"><div class="dn-tag dn-tag--gray dn-tag--top dn-tag--button"><i class="fa fa-magic fa-lg"></i></div><div class="dn-tag dn-tag--gray dn-tag--bottom">.styl</div><!--
              -->.example<br/><!--
              -->  wrap()<br/><!--
              -->  wrap(gutter,24px)<br/><!--
              -->  wrap(top)<br/><!--
              -->  <span>wrap(masonry,3)</span><br/><!--
              -->  &__item<br/><!--
              -->    col()<br/><!--
              -->    &.one<br/><!--
              -->      col(1,1)<br/><!--
              -->    &.two<br/><!--
              -->      col(1,2)<br/><!--
              -->    &.three<br/><!--
              -->      col(1,3)<br/><!--
            --></pre>
            {% include learn/masonry/compiled.html %}
          </div>
        </div>
      </div>
      {% include learn/masonry/preview.html %}
      <div class="dn-browser-footer">
        <div class="wrap xl-gutter-24 xl-outside-24 xl-center xl-auto">
          <div class="col">
            <a href="https://github.com/flexiblegs/flexiblegs-stylus-plus" class="dn-button dn-button--link">https://github.com/flexiblegs/flexiblegs-stylus-plus</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
