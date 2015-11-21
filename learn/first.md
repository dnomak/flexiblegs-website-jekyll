---
layout: flexiblegs
title: col(first)
permalink: /learn/first/
---

<div id="css">
  <div class="dn-browser">
    <div class="dn-browser-header">
      <div class="dn-style--title">{% include flexiblegs/learn/first/title.html %} (css)</div>
      {% include flexiblegs/logo.html %}
    </div>
    <div class="dn-browser-body">
      <div class="dn-browser-body__pre">
        <pre class="not-compiled"><div class="dn-tag dn-tag--gray dn-tag--top dn-tag--button"><i class="fa fa-rocket fa-lg"></i></div><div class="dn-tag dn-tag--gray dn-tag--bottom">.html</div><!--
          -->&lt;div class="wrap xl-flexbox xl-gutter-24 xl-3"&gt;<br/><!--
          -->  &lt;div class="col"&gt;01&lt;/div&gt;<br/><!--
          -->  &lt;div class="col"&gt;02&lt;/div&gt;<br/><!--
          -->  &lt;div class="col <span>xl-first</span>"&gt;03&lt;/div&gt;<br/><!--
          -->&lt;/div&gt;<!--
        --></pre>
        {% include flexiblegs/learn/first/compiled.html %}
      </div>
      {% include flexiblegs/learn/first/preview.html %}
      <div class="dn-browser-footer">
        <div class="wrap xl-gutter-24 xl-outside-24 xl-center xl-auto">
          <div class="col">
            <a href="http://codepen.io/dnomak/pen/gpqXbO?editors=110" class="dn-button dn-button--link">http://codepen.io/dnomak/pen/gpqXbO</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<div id="bem">
  <div class="dn-browser">
    <div class="dn-browser-header">
      <div class="dn-style--title">{% include flexiblegs/learn/first/title.html %} (bem)</div>
      {% include flexiblegs/logo.html %}
    </div>
    <div class="dn-browser-body">
      <div class="dn-browser-body__pre">
        <pre class="not-compiled"><div class="dn-tag dn-tag--gray dn-tag--top dn-tag--button"><i class="fa fa-rocket fa-lg"></i></div><div class="dn-tag dn-tag--gray dn-tag--bottom">.html</div><!--
          -->&lt;div class="wrap wrap--xl-flexbox wrap--xl-gutter-24 wrap--xl-3"&gt;<br/><!--
          -->  &lt;div class="wrap__col"&gt;01&lt;/div&gt;<br/><!--
          -->  &lt;div class="wrap__col"&gt;02&lt;/div&gt;<br/><!--
          -->  &lt;div class="wrap__col <span>wrap__col--xl-first</span>"&gt;03&lt;/div&gt;<br/><!--
          -->&lt;/div&gt;<!--
        --></pre>
        {% include flexiblegs/learn/first/compiled.html %}
      </div>
      {% include flexiblegs/learn/first/preview.html %}
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
      <div class="dn-style--title">{% include flexiblegs/learn/first/title.html %} (scss)</div>
      {% include flexiblegs/logo.html %}
    </div>
    <div class="dn-browser-body">
      <div class="dn-browser-body__pre">
        <div class="wrap xl-top xl-gutter-24 xl-2 md-1">
          {% include flexiblegs/learn/first/dynamic.html %}
          <div class="col">
            <pre class="not-compiled"><div class="dn-tag dn-tag--gray dn-tag--top dn-tag--button"><i class="fa fa-rocket fa-lg"></i></div><div class="dn-tag dn-tag--gray dn-tag--bottom">.scss</div><!--
              -->.example {<br/><!--
              -->  @include wrap;<br/><!--
              -->  @include wrap("flexbox");<br/><!--
              -->  @include wrap("gutter",24);<br/><!--
              -->  @include wrap(3);<br/><!--
              -->  &__item {<br/><!--
              -->    @include col;<br/><!--
              -->    &.three {<br/><!--
              -->      @include <span>col("first")</span>;<br/><!--
              -->    }<br/><!--
              -->  }<br/><!--
              -->}<!--
            --></pre>
            {% include flexiblegs/learn/first/compiled.html %}
          </div>
        </div>
      </div>
      {% include flexiblegs/learn/first/preview.html %}
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
      <div class="dn-style--title">{% include flexiblegs/learn/first/title.html %} (sass)</div>
      {% include flexiblegs/logo.html %}
    </div>
    <div class="dn-browser-body">
      <div class="dn-browser-body__pre">
        <div class="wrap xl-top xl-gutter-24 xl-2 md-1">
          {% include flexiblegs/learn/first/dynamic.html %}
          <div class="col">
            <pre class="not-compiled"><div class="dn-tag dn-tag--gray dn-tag--top dn-tag--button"><i class="fa fa-rocket fa-lg"></i></div><div class="dn-tag dn-tag--gray dn-tag--bottom">.sass</div><!--
              -->.example<br/><!--
              -->  +wrap<br/><!--
              -->  +wrap("flexbox")<br/><!--
              -->  +wrap("gutter",24)<br/><!--
              -->  +wrap(3)<br/><!--
              -->  &__item<br/><!--
              -->    +col<br/><!--
              -->    &.three<br/><!--
              -->      +<span>col("first")</span><!--
            --></pre>
            {% include flexiblegs/learn/first/compiled.html %}
          </div>
        </div>
      </div>
      {% include flexiblegs/learn/first/preview.html %}
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
      <div class="dn-style--title">{% include flexiblegs/learn/first/title.html %} (less)</div>
      {% include flexiblegs/logo.html %}
    </div>
    <div class="dn-browser-body">
      <div class="dn-browser-body__pre">
        <div class="wrap xl-top xl-gutter-24 xl-2 md-1">
          {% include flexiblegs/learn/first/dynamic.html %}
          <div class="col">
            <pre class="not-compiled"><div class="dn-tag dn-tag--gray dn-tag--top dn-tag--button"><i class="fa fa-rocket fa-lg"></i></div><div class="dn-tag dn-tag--gray dn-tag--bottom">.less</div><!--
              -->.example {<br/><!--
              -->  .wrap;<br/><!--
              -->  .wrap("flexbox");<br/><!--
              -->  .wrap("gutter",24);<br/><!--
              -->  .wrap(3);<br/><!--
              -->  &__item {<br/><!--
              -->    .col;<br/><!--
              -->    &.three {<br/><!--
              -->      .<span>col("first")</span>;<br/><!--
              -->    }<br/><!--
              -->  }<br/><!--
              -->}<!--
            --></pre>
            {% include flexiblegs/learn/first/compiled.html %}
          </div>
        </div>
      </div>
      {% include flexiblegs/learn/first/preview.html %}
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
      <div class="dn-style--title">{% include flexiblegs/learn/first/title.html %} (stylus)</div>
      {% include flexiblegs/logo.html %}
    </div>
    <div class="dn-browser-body">
      <div class="dn-browser-body__pre">
        <div class="wrap xl-top xl-gutter-24 xl-2 md-1">
          {% include flexiblegs/learn/first/dynamic.html %}
          <div class="col">
            <pre class="not-compiled"><div class="dn-tag dn-tag--gray dn-tag--top dn-tag--button"><i class="fa fa-rocket fa-lg"></i></div><div class="dn-tag dn-tag--gray dn-tag--bottom">.styl</div><!--
              -->.example<br/><!--
              -->  wrap()<br/><!--
              -->  wrap("flexbox")<br/><!--
              -->  wrap("gutter",24)<br/><!--
              -->  wrap(3)<br/><!--
              -->  &__item<br/><!--
              -->    col()<br/><!--
              -->    &.three<br/><!--
              -->      <span>col("first")</span><!--
            --></pre>
            {% include flexiblegs/learn/first/compiled.html %}
          </div>
        </div>
      </div>
      {% include flexiblegs/learn/first/preview.html %}
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
