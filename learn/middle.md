---
layout: flexiblegs
title: wrap(middle)
permalink: /learn/middle/
---

<div id="css">
  <div class="dn-browser">
    <div class="dn-browser-header">
      <div class="dn-style--title">{% include flexiblegs/learn/middle/title.html %} (css)</div>
      {% include flexiblegs/logo.html %}
    </div>
    <div class="dn-browser-body">
      <div class="dn-browser-body__pre">
        <pre class="not-compiled"><div class="dn-tag dn-tag--gray dn-tag--top dn-tag--button"><i class="fa fa-rocket fa-lg"></i></div><div class="dn-tag dn-tag--gray dn-tag--bottom">.html</div><!--
          -->&lt;div class="wrap <span>xl-middle</span>"&gt;<br/><!--
          -->  &lt;div class="col xl-3-12"&gt;01&lt;/div&gt;<br/><!--
          -->  &lt;div class="col xl-6-12"&gt;02&lt;/div&gt;<br/><!--
          -->  &lt;div class="col xl-3-12"&gt;03&lt;/div&gt;<br/><!--
          -->&lt;/div&gt;<!--
        --></pre>
        {% include flexiblegs/learn/middle/compiled.html %}
      </div>
      {% include flexiblegs/learn/middle/preview.html %}
      <div class="dn-browser-footer">
        <div class="wrap xl-gutter-24 xl-outside-24 xl-center xl-auto">
          <div class="col">
            <a href="http://codepen.io/dnomak/pen/mJvBYZ?editors=110" class="dn-button dn-button--link">http://codepen.io/dnomak/pen/mJvBYZ</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<div id="bem">
  <div class="dn-browser">
    <div class="dn-browser-header">
      <div class="dn-style--title">{% include flexiblegs/learn/middle/title.html %} (bem)</div>
      {% include flexiblegs/logo.html %}
    </div>
    <div class="dn-browser-body">
      <div class="dn-browser-body__pre">
        <pre class="not-compiled"><div class="dn-tag dn-tag--gray dn-tag--top dn-tag--button"><i class="fa fa-rocket fa-lg"></i></div><div class="dn-tag dn-tag--gray dn-tag--bottom">.html</div><!--
          -->&lt;div class="wrap <span>wrap--xl-middle</span>"&gt;<br/><!--
          -->  &lt;div class="wrap__col wrap__col--xl-3-12"&gt;01&lt;/div&gt;<br/><!--
          -->  &lt;div class="wrap__col wrap__col--xl-6-12"&gt;02&lt;/div&gt;<br/><!--
          -->  &lt;div class="wrap__col wrap__col--xl-3-12"&gt;03&lt;/div&gt;<br/><!--
          -->&lt;/div&gt;<!--
        --></pre>
        {% include flexiblegs/learn/middle/compiled.html %}
      </div>
      {% include flexiblegs/learn/middle/preview.html %}
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
      <div class="dn-style--title">{% include flexiblegs/learn/middle/title.html %} (scss)</div>
      {% include flexiblegs/logo.html %}
    </div>
    <div class="dn-browser-body">
      <div class="dn-browser-body__pre">
        <div class="wrap xl-top xl-gutter-24 xl-2 md-1">
          {% include flexiblegs/learn/middle/dynamic.html %}
          <div class="col">
            <pre class="not-compiled"><div class="dn-tag dn-tag--gray dn-tag--top dn-tag--button"><i class="fa fa-rocket fa-lg"></i></div><div class="dn-tag dn-tag--gray dn-tag--bottom">.scss</div><!--
              -->.example {<br/><!--
              -->  @include wrap;<br/><!--
              -->  @include <span>wrap("middle")</span>;<br/><!--
              -->  &__item {<br/><!--
              -->    @include col;<br/><!--
              -->    &.one {<br/><!--
              -->      @include col(3,12);<br/><!--
              -->    }<br/><!--
              -->    &.two {<br/><!--
              -->      @include col(6,12);<br/><!--
              -->    }<br/><!--
              -->    &.three {<br/><!--
              -->      @include col(3,12);<br/><!--
              -->    }<br/><!--
              -->  }<br/><!--
              -->}<!--
            --></pre>
            {% include flexiblegs/learn/middle/compiled.html %}
          </div>
        </div>
      </div>
      {% include flexiblegs/learn/middle/preview.html %}
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
      <div class="dn-style--title">{% include flexiblegs/learn/middle/title.html %} (sass)</div>
      {% include flexiblegs/logo.html %}
    </div>
    <div class="dn-browser-body">
      <div class="dn-browser-body__pre">
        <div class="wrap xl-top xl-gutter-24 xl-2 md-1">
          {% include flexiblegs/learn/middle/dynamic.html %}
          <div class="col">
            <pre class="not-compiled"><div class="dn-tag dn-tag--gray dn-tag--top dn-tag--button"><i class="fa fa-rocket fa-lg"></i></div><div class="dn-tag dn-tag--gray dn-tag--bottom">.sass</div><!--
              -->.example<br/><!--
              -->  +wrap<br/><!--
              -->  +<span>wrap("middle")</span><br/><!--
              -->  &__item<br/><!--
              -->    +col<br/><!--
              -->    &.one<br/><!--
              -->      +col(3,12)<br/><!--
              -->    &.two<br/><!--
              -->      +col(6,12)<br/><!--
              -->    &.three<br/><!--
              -->      +col(3,12)<br/><!--
            --></pre>
            {% include flexiblegs/learn/middle/compiled.html %}
          </div>
        </div>
      </div>
      {% include flexiblegs/learn/middle/preview.html %}
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
      <div class="dn-style--title">{% include flexiblegs/learn/middle/title.html %} (less)</div>
      {% include flexiblegs/logo.html %}
    </div>
    <div class="dn-browser-body">
      <div class="dn-browser-body__pre">
        <div class="wrap xl-top xl-gutter-24 xl-2 md-1">
          {% include flexiblegs/learn/middle/dynamic.html %}
          <div class="col">
            <pre class="not-compiled"><div class="dn-tag dn-tag--gray dn-tag--top dn-tag--button"><i class="fa fa-rocket fa-lg"></i></div><div class="dn-tag dn-tag--gray dn-tag--bottom">.less</div><!--
              -->.example {<br/><!--
              -->  .wrap;<br/><!--
              -->  .<span>wrap("middle")</span>;<br/><!--
              -->  &__item {<br/><!--
              -->    .col;<br/><!--
              -->    &.one {<br/><!--
              -->      .col(3,12);<br/><!--
              -->    }<br/><!--
              -->    &.two {<br/><!--
              -->      .col(6,12);<br/><!--
              -->    }<br/><!--
              -->    &.three {<br/><!--
              -->      .col(3,12);<br/><!--
              -->    }<br/><!--
              -->  }<br/><!--
              -->}<!--
            --></pre>
            {% include flexiblegs/learn/middle/compiled.html %}
          </div>
        </div>
      </div>
      {% include flexiblegs/learn/middle/preview.html %}
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
      <div class="dn-style--title">{% include flexiblegs/learn/middle/title.html %} (stylus)</div>
      {% include flexiblegs/logo.html %}
    </div>
    <div class="dn-browser-body">
      <div class="dn-browser-body__pre">
        <div class="wrap xl-top xl-gutter-24 xl-2 md-1">
          {% include flexiblegs/learn/middle/dynamic.html %}
          <div class="col">
            <pre class="not-compiled"><div class="dn-tag dn-tag--gray dn-tag--top dn-tag--button"><i class="fa fa-rocket fa-lg"></i></div><div class="dn-tag dn-tag--gray dn-tag--bottom">.styl</div><!--
              -->.example<br/><!--
              -->  wrap()<br/><!--
              -->  <span>wrap("middle")</span><br/><!--
              -->  &__item<br/><!--
              -->    col()<br/><!--
              -->    &.one<br/><!--
              -->      col(3,12)<br/><!--
              -->    &.two<br/><!--
              -->      col(6,12)<br/><!--
              -->    &.three<br/><!--
              -->      col(3,12)<br/><!--
            --></pre>
            {% include flexiblegs/learn/middle/compiled.html %}
          </div>
        </div>
      </div>
      {% include flexiblegs/learn/middle/preview.html %}
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
