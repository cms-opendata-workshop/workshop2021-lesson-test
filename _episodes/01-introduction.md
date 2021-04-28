---
title: "Introduction"
teaching: 0
exercises: 0
questions:
- "Key question (FIXME)"
objectives:
- "First learning objective. (FIXME)"
keypoints:
- "First key point. Brief Answer to questions. (FIXME)"
---
<div id="docker">
  <h3>Docker instructions</h3>
  <p>
    I guess Jekyll can parse markdown and/or straight html in the same file.  The only problem is once one is inside a html ambience, like a div, you can't use markdown.  The workaround is to hack the html code from the blockquotes and just paste them here.  The headers will know about the css classes.
  </p>

  <div>
    <ul class="nav nav-tabs" role="tablist">
      <li role="presentation" class="active"><a data-os="windows" href="#shell-windows" aria-controls="Windows" role="tab" data-toggle="tab">Windows</a></li>
      <li role="presentation"><a data-os="macos" href="#shell-macos" aria-controls="MacOS" role="tab" data-toggle="tab">MacOS</a></li>
      <li role="presentation"><a data-os="linux" href="#shell-linux" aria-controls="Linux" role="tab" data-toggle="tab">Linux</a></li>
    </ul>

    <div class="tab-content">
      <article role="tabpanel" class="tab-pane active" id="shell-windows">
    `Windows` sucks and I do not like it.       
      </article>
      <article role="tabpanel" class="tab-pane" id="shell-macos">
       
      </article>
      <article role="tabpanel" class="tab-pane" id="shell-linux">
<p>This does not work:</p>
~~~
docker run hello-world
~~~
{: .bash}

<p>This works</p>
<div class="language-plaintext bash highlighter-rouge"><div class="highlight"><pre class="highlight"><code>docker run hello-world
</code></pre></div></div>


      </article>
    </div>
  </div>
</div>

{% include links.md %}

