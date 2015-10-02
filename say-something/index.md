---
layout: default
dynamic_title: say-something
permalink: /say-something/
---

<script type="text/javascript">
  var disqus_shortname = 'flexiblegs';
  (function() {
    var dsq = document.createElement('script'); dsq.type = 'text/javascript'; dsq.async = true;
    dsq.src = '//' + disqus_shortname + '.disqus.com/embed.js';
    (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(dsq);
  })();
</script>
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
            <div class="dn-disqus">
              <div id="disqus_thread"></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
