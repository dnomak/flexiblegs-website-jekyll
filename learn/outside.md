---
layout: default
title: wrap(outside,@width)
permalink: /learn/outside/
---

<div id="css">
  <div class="dn-browser">
    <div class="dn-browser-header">
      {% include browser-button.html %}
      <div class="dn-style--title">wrap(<span>outside</span>,@width) (css)</div>
      {% include logo.html %}
    </div>
    <div class="dn-browser-body">
      <div class="dn-browser-body__pre">
        <pre class="not-compiled"><div class="dn-tag dn-tag--gray dn-tag--top dn-tag--button"><i class="fa fa-magic fa-lg"></i></div><div class="dn-tag dn-tag--gray dn-tag--bottom">.html</div><!--
          -->&lt;div class="wrap xl-gutter-24 <span>xl-outside-24</span>"&gt;<br/><!--
          -->  &lt;div class="col xl-3-12"&gt;01&lt;/div&gt;<br/><!--
          -->  &lt;div class="col xl-6-12"&gt;02&lt;/div&gt;<br/><!--
          -->  &lt;div class="col xl-3-12"&gt;03&lt;/div&gt;<br/><!--
          -->&lt;/div&gt;<!--
          --><div class="comment">&lt;!-- 0, 8, 16, 24, 40 --&gt;</div><!--
        --></pre>
        {% include outside/compiled.html %}
      </div>
      {% include outside/preview.html %}
      <div class="dn-browser-footer">
        <div class="wrap xl-gutter-24 xl-outside-24 xl-center xl-auto">
          <div class="col">
            <a href="http://codepen.io/dnomak/pen/bdObpN?editors=110" class="dn-button dn-button--link">http://codepen.io/dnomak/pen/bdObpN</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<div id="bem-css">
  <div class="dn-browser">
    <div class="dn-browser-header">
      {% include browser-button.html %}
      <div class="dn-style--title">wrap(<span>outside</span>,@width) (bem-css)</div>
      {% include logo.html %}
    </div>
    <div class="dn-browser-body">
      <div class="dn-browser-body__pre">
        <pre class="not-compiled"><div class="dn-tag dn-tag--gray dn-tag--top dn-tag--button"><i class="fa fa-magic fa-lg"></i></div><div class="dn-tag dn-tag--gray dn-tag--bottom">.html</div><!--
          -->&lt;div class="wrap wrap--xl-gutter-24 <span>wrap--xl-outside-24</span>"&gt;<br/><!--
          -->  &lt;div class="wrap__col wrap__col--xl-3-12"&gt;01&lt;/div&gt;<br/><!--
          -->  &lt;div class="wrap__col wrap__col--xl-6-12"&gt;02&lt;/div&gt;<br/><!--
          -->  &lt;div class="wrap__col wrap__col--xl-3-12"&gt;03&lt;/div&gt;<br/><!--
          -->&lt;/div&gt;<!--
          --><div class="comment">&lt;!-- 0, 8, 16, 24, 40 --&gt;</div><!--
        --></pre>
        {% include outside/compiled.html %}
      </div>
      {% include outside/preview.html %}
      <div class="dn-browser-footer">
        <div class="wrap xl-gutter-24 xl-outside-24 xl-center xl-auto">
          <div class="col">
            <a href="https://github.com/flexiblegs/flexiblegs-bem-css" class="dn-button dn-button--link">https://github.com/flexiblegs/flexiblegs-bem-css</a>
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
      <div class="dn-style--title">wrap(<span>outside</span>,@width) (scss-plus)</div>
      {% include logo.html %}
    </div>
    <div class="dn-browser-body">
      <div class="dn-browser-body__pre">
        <div class="wrap xl-top xl-gutter-24 xl-2 lg-1">
          <div class="col">
            <pre><div class="dn-tag dn-tag--gray dn-tag--bottom">.html</div><!--
              -->&lt;div class="example"&gt;<br/><!--
              -->  &lt;div class="example__item one"&gt;01&lt;/div&gt;<br/><!--
              -->  &lt;div class="example__item two"&gt;02&lt;/div&gt;<br/><!--
              -->  &lt;div class="example__item three"&gt;03&lt;/div&gt;<br/><!--
              -->&lt;/div&gt;<!--
            --></pre>
            <br class="xl-hidden lg-not-hidden" />
          </div>
          <div class="col">
            <pre class="not-compiled"><div class="dn-tag dn-tag--gray dn-tag--top dn-tag--button"><i class="fa fa-magic fa-lg"></i></div><div class="dn-tag dn-tag--gray dn-tag--bottom">.scss</div><!--
              -->.example {<br/><!--
              -->  @include wrap;<br/><!--
              -->  @include wrap(gutter,24px);<br/><!--
              -->  @include <span>wrap(outside,24px)</span>;<br/><!--
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
            {% include outside/compiled.html %}
          </div>
        </div>
      </div>
      {% include outside/preview.html %}
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
      <div class="dn-style--title">wrap(<span>outside</span>,@width) (sass-plus)</div>
      {% include logo.html %}
    </div>
    <div class="dn-browser-body">
      <div class="dn-browser-body__pre">
        <div class="wrap xl-top xl-gutter-24 xl-2 lg-1">
          <div class="col">
            <pre><div class="dn-tag dn-tag--gray dn-tag--bottom">.html</div><!--
              -->&lt;div class="example"&gt;<br/><!--
              -->  &lt;div class="example__item one"&gt;01&lt;/div&gt;<br/><!--
              -->  &lt;div class="example__item two"&gt;02&lt;/div&gt;<br/><!--
              -->  &lt;div class="example__item three"&gt;03&lt;/div&gt;<br/><!--
              -->&lt;/div&gt;<!--
            --></pre>
            <br class="xl-hidden lg-not-hidden" />
          </div>
          <div class="col">
            <pre class="not-compiled"><div class="dn-tag dn-tag--gray dn-tag--top dn-tag--button"><i class="fa fa-magic fa-lg"></i></div><div class="dn-tag dn-tag--gray dn-tag--bottom">.sass</div><!--
              -->.example<br/><!--
              -->  +wrap<br/><!--
              -->  +wrap(gutter,24px)<br/><!--
              -->  +<span>wrap(outside,24px)</span><br/><!--
              -->  &__item<br/><!--
              -->    +col<br/><!--
              -->    &.one<br/><!--
              -->      +col(3,12)<br/><!--
              -->    &.two<br/><!--
              -->      +col(6,12)<br/><!--
              -->    &.three<br/><!--
              -->      +col(3,12)<!--
            --></pre>
            {% include outside/compiled.html %}
          </div>
        </div>
      </div>
      {% include outside/preview.html %}
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
      <div class="dn-style--title">wrap(<span>outside</span>,@width) (less-plus)</div>
      {% include logo.html %}
    </div>
    <div class="dn-browser-body">
      <div class="dn-browser-body__pre">
        <div class="wrap xl-top xl-gutter-24 xl-2 lg-1">
          <div class="col">
            <pre><div class="dn-tag dn-tag--gray dn-tag--bottom">.html</div><!--
              -->&lt;div class="example"&gt;<br/><!--
              -->  &lt;div class="example__item one"&gt;01&lt;/div&gt;<br/><!--
              -->  &lt;div class="example__item two"&gt;02&lt;/div&gt;<br/><!--
              -->  &lt;div class="example__item three"&gt;03&lt;/div&gt;<br/><!--
              -->&lt;/div&gt;<!--
            --></pre>
            <br class="xl-hidden lg-not-hidden" />
          </div>
          <div class="col">
            <pre class="not-compiled"><div class="dn-tag dn-tag--gray dn-tag--top dn-tag--button"><i class="fa fa-magic fa-lg"></i></div><div class="dn-tag dn-tag--gray dn-tag--bottom">.less</div><!--
              -->.example {<br/><!--
              -->  .wrap;<br/><!--
              -->  .wrap(gutter,24px);<br/><!--
              -->  .<span>wrap(outside,24px)</span>;<br/><!--
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
            {% include outside/compiled.html %}
          </div>
        </div>
      </div>
      {% include outside/preview.html %}
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
      <div class="dn-style--title">wrap(<span>outside</span>,@width) (stylus-plus)</div>
      {% include logo.html %}
    </div>
    <div class="dn-browser-body">
      <div class="dn-browser-body__pre">
        <div class="wrap xl-top xl-gutter-24 xl-2 lg-1">
          <div class="col">
            <pre><div class="dn-tag dn-tag--gray dn-tag--bottom">.html</div><!--
              -->&lt;div class="example"&gt;<br/><!--
              -->  &lt;div class="example__item one"&gt;01&lt;/div&gt;<br/><!--
              -->  &lt;div class="example__item two"&gt;02&lt;/div&gt;<br/><!--
              -->  &lt;div class="example__item three"&gt;03&lt;/div&gt;<br/><!--
              -->&lt;/div&gt;<!--
            --></pre>
            <br class="xl-hidden lg-not-hidden" />
          </div>
          <div class="col">
            <pre class="not-compiled"><div class="dn-tag dn-tag--gray dn-tag--top dn-tag--button"><i class="fa fa-magic fa-lg"></i></div><div class="dn-tag dn-tag--gray dn-tag--bottom">.styl</div><!--
              -->.example<br/><!--
              -->  wrap()<br/><!--
              -->  wrap(gutter,24px)<br/><!--
              -->  <span>wrap(outside,24px)</span><br/><!--
              -->  &__item<br/><!--
              -->    col()<br/><!--
              -->    &.one<br/><!--
              -->      col(3,12)<br/><!--
              -->    &.two<br/><!--
              -->      col(6,12)<br/><!--
              -->    &.three<br/><!--
              -->      col(3,12)<!--
            --></pre>
            {% include outside/compiled.html %}
          </div>
        </div>
      </div>
      {% include outside/preview.html %}
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