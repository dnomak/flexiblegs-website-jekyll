---
layout: flexiblegs
title: wrap(around)
permalink: /learn/around/
---

<div id="css">
  <div class="dn-browser">
    <div class="dn-browser-header">
      <div class="dn-style--title">{% include flexiblegs/learn/around/title.html %} (css)</div>
      {% include flexiblegs/logo.html %}
    </div>
    <div class="dn-browser-body">
      <div class="dn-browser-body__pre">
        <pre class="not-compiled"><div class="dn-tag dn-tag--gray dn-tag--top dn-tag--button"><i class="fa fa-rocket fa-lg"></i></div><div class="dn-tag dn-tag--gray dn-tag--bottom">.html</div><!--
          -->&lt;div class="wrap xl-flexbox <span>xl-around</span> xl-5"&gt;<br/><!--
          -->  &lt;div class="col"&gt;01&lt;/div&gt;<br/><!--
          -->  &lt;div class="col"&gt;02&lt;/div&gt;<br/><!--
          -->  &lt;div class="col"&gt;03&lt;/div&gt;<br/><!--
          -->  &lt;div class="col xl-1-1"&gt;04&lt;/div&gt;<br/><!--
          -->  &lt;div class="col"&gt;05&lt;/div&gt;<br/><!--
          -->  &lt;div class="col"&gt;06&lt;/div&gt;<br/><!--
          -->  &lt;div class="col"&gt;07&lt;/div&gt;<br/><!--
          -->&lt;/div&gt;<!--
        --></pre>
        {% include flexiblegs/learn/around/compiled.html %}
      </div>
      {% include flexiblegs/learn/around/preview.html %}
      <div class="dn-browser-footer">
        <div class="wrap xl-gutter-24 xl-outside-24 xl-center xl-auto">
          <div class="col">
            <a href="http://codepen.io/dnomak/pen/doaZba?editors=110" class="dn-button dn-button--link">http://codepen.io/dnomak/pen/doaZba</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<div id="bem">
  <div class="dn-browser">
    <div class="dn-browser-header">
      <div class="dn-style--title">{% include flexiblegs/learn/around/title.html %} (bem)</div>
      {% include flexiblegs/logo.html %}
    </div>
    <div class="dn-browser-body">
      <div class="dn-browser-body__pre">
        <pre class="not-compiled"><div class="dn-tag dn-tag--gray dn-tag--top dn-tag--button"><i class="fa fa-rocket fa-lg"></i></div><div class="dn-tag dn-tag--gray dn-tag--bottom">.html</div><!--
          -->&lt;div class="wrap wrap--xl-flexbox <span>wrap--xl-around</span> wrap--xl-5"&gt;<br/><!--
          -->  &lt;div class="wrap__col"&gt;01&lt;/div&gt;<br/><!--
          -->  &lt;div class="wrap__col"&gt;02&lt;/div&gt;<br/><!--
          -->  &lt;div class="wrap__col"&gt;03&lt;/div&gt;<br/><!--
          -->  &lt;div class="wrap__col wrap__col--xl-1-1"&gt;04&lt;/div&gt;<br/><!--
          -->  &lt;div class="wrap__col"&gt;05&lt;/div&gt;<br/><!--
          -->  &lt;div class="wrap__col"&gt;06&lt;/div&gt;<br/><!--
          -->  &lt;div class="wrap__col"&gt;07&lt;/div&gt;<br/><!--
          -->&lt;/div&gt;<!--
        --></pre>
        {% include flexiblegs/learn/around/compiled.html %}
      </div>
      {% include flexiblegs/learn/around/preview.html %}
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

<div id="scss">
  <div class="dn-browser">
    <div class="dn-browser-header">
      <div class="dn-style--title">{% include flexiblegs/learn/around/title.html %} (scss)</div>
      {% include flexiblegs/logo.html %}
    </div>
    <div class="dn-browser-body">
      <div class="dn-browser-body__pre">
        <div class="wrap xl-top xl-gutter-24 xl-2 md-1">
          {% include flexiblegs/learn/around/dynamic.html %}
          <div class="col">
            <pre class="not-compiled"><div class="dn-tag dn-tag--gray dn-tag--top dn-tag--button"><i class="fa fa-rocket fa-lg"></i></div><div class="dn-tag dn-tag--gray dn-tag--bottom">.scss</div><!--
              -->.example {<br/><!--
              -->  @include wrap;<br/><!--
              -->  @include wrap("flexbox");<br/><!--
              -->  @include <span>wrap("around")</span>;<br/><!--
              -->  @include wrap(5);<br/><!--
              -->  &__item {<br/><!--
              -->    @include col;<br/><!--
              -->    &.four {<br/><!--
              -->      @include col(1,1);<br/><!--
              -->    }<br/><!--
              -->  }<br/><!--
              -->}<!--
            --></pre>
            {% include flexiblegs/learn/around/compiled.html %}
          </div>
        </div>
      </div>
      {% include flexiblegs/learn/around/preview.html %}
      <div class="dn-browser-footer">
        <div class="wrap xl-gutter-24 xl-outside-24 xl-center xl-auto">
          <div class="col">
            <a href="https://github.com/flexiblegs/flexiblegs-scss" class="dn-button dn-button--link">https://github.com/flexiblegs/flexiblegs-scss</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<div id="sass">
  <div class="dn-browser">
    <div class="dn-browser-header">
      <div class="dn-style--title">{% include flexiblegs/learn/around/title.html %} (sass)</div>
      {% include flexiblegs/logo.html %}
    </div>
    <div class="dn-browser-body">
      <div class="dn-browser-body__pre">
        <div class="wrap xl-top xl-gutter-24 xl-2 md-1">
          {% include flexiblegs/learn/around/dynamic.html %}
          <div class="col">
            <pre class="not-compiled"><div class="dn-tag dn-tag--gray dn-tag--top dn-tag--button"><i class="fa fa-rocket fa-lg"></i></div><div class="dn-tag dn-tag--gray dn-tag--bottom">.sass</div><!--
              -->.example<br/><!--
              -->  +wrap<br/><!--
              -->  +wrap("flexbox")<br/><!--
              -->  +<span>wrap("around")</span><br/><!--
              -->  +wrap(5)<br/><!--
              -->  &__item<br/><!--
              -->    +col<br/><!--
              -->    &.four<br/><!--
              -->      +col(1,1)<br/><!--
            --></pre>
            {% include flexiblegs/learn/around/compiled.html %}
          </div>
        </div>
      </div>
      {% include flexiblegs/learn/around/preview.html %}
      <div class="dn-browser-footer">
        <div class="wrap xl-gutter-24 xl-outside-24 xl-center xl-auto">
          <div class="col">
            <a href="https://github.com/flexiblegs/flexiblegs-sass" class="dn-button dn-button--link">https://github.com/flexiblegs/flexiblegs-sass</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<div id="less">
  <div class="dn-browser">
    <div class="dn-browser-header">
      <div class="dn-style--title">{% include flexiblegs/learn/around/title.html %} (less)</div>
      {% include flexiblegs/logo.html %}
    </div>
    <div class="dn-browser-body">
      <div class="dn-browser-body__pre">
        <div class="wrap xl-top xl-gutter-24 xl-2 md-1">
          {% include flexiblegs/learn/around/dynamic.html %}
          <div class="col">
            <pre class="not-compiled"><div class="dn-tag dn-tag--gray dn-tag--top dn-tag--button"><i class="fa fa-rocket fa-lg"></i></div><div class="dn-tag dn-tag--gray dn-tag--bottom">.less</div><!--
              -->.example {<br/><!--
              -->  .wrap;<br/><!--
              -->  .wrap("flexbox");<br/><!--
              -->  .<span>wrap("around")</span>;<br/><!--
              -->  .wrap(5);<br/><!--
              -->  &__item {<br/><!--
              -->    .col;<br/><!--
              -->    &.four {<br/><!--
              -->      .col(1,1);<br/><!--
              -->    }<br/><!--
              -->  }<br/><!--
              -->}<!--
            --></pre>
            {% include flexiblegs/learn/around/compiled.html %}
          </div>
        </div>
      </div>
      {% include flexiblegs/learn/around/preview.html %}
      <div class="dn-browser-footer">
        <div class="wrap xl-gutter-24 xl-outside-24 xl-center xl-auto">
          <div class="col">
            <a href="https://github.com/flexiblegs/flexiblegs-less" class="dn-button dn-button--link">https://github.com/flexiblegs/flexiblegs-less</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<div id="stylus">
  <div class="dn-browser">
    <div class="dn-browser-header">
      <div class="dn-style--title">{% include flexiblegs/learn/around/title.html %} (stylus)</div>
      {% include flexiblegs/logo.html %}
    </div>
    <div class="dn-browser-body">
      <div class="dn-browser-body__pre">
        <div class="wrap xl-top xl-gutter-24 xl-2 md-1">
          {% include flexiblegs/learn/around/dynamic.html %}
          <div class="col">
            <pre class="not-compiled"><div class="dn-tag dn-tag--gray dn-tag--top dn-tag--button"><i class="fa fa-rocket fa-lg"></i></div><div class="dn-tag dn-tag--gray dn-tag--bottom">.styl</div><!--
              -->.example<br/><!--
              -->  wrap()<br/><!--
              -->  wrap("flexbox")<br/><!--
              -->  <span>wrap("around")</span><br/><!--
              -->  wrap(5)<br/><!--
              -->  &__item<br/><!--
              -->    col()<br/><!--
              -->    &.four<br/><!--
              -->      col(1,1)<br/><!--
            --></pre>
            {% include flexiblegs/learn/around/compiled.html %}
          </div>
        </div>
      </div>
      {% include flexiblegs/learn/around/preview.html %}
      <div class="dn-browser-footer">
        <div class="wrap xl-gutter-24 xl-outside-24 xl-center xl-auto">
          <div class="col">
            <a href="https://github.com/flexiblegs/flexiblegs-stylus" class="dn-button dn-button--link">https://github.com/flexiblegs/flexiblegs-stylus</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
