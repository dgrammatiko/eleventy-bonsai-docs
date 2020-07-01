---
title: "Typography"
bookToc: false
---

## Typography Helpers

#### Bonsai includes a collection of typography helpers for creating beautiful shadow effects to any box element.

<br>

### \-\-line-clamp
The `--line-clamp` helper allows you to easily set a line clamp on an element. The value of this helper defines the number of lines at which text will be clamped.

{{< helper-demo property="line-clamp" min="1" max="10" value="4" target="target-line-clamp" >}}
<div style="--maxw:400px; --br:5px; --bg:#fff; --of:hidden;">
    <div id="target-line-clamp" style="--line-clamp:4; --m:1rem">
        Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Phasellus hendrerit. Pellentesque aliquet nibh nec urna. In nisi neque, aliquet vel, dapibus id, mattis vel, nisi. Sed pretium, ligula sollicitudin laoreet viverra, tortor libero sodales leo, eget blandit nunc tortor eu nibh. Nullam mollis. Ut justo. Suspendisse potenti. Sed egestas, ante et vulputate volutpat, eros pede semper est, vitae luctus metus libero eu augue. Morbi purus libero, faucibus adipiscing, commodo quis, gravida id, est.
    </div>
</div>
{{< /helper-demo >}}

### \-\-text-3d
The `--text-3d` helper gives text a 3D. Value of this helper sets the 3D color using the text-shadow CSS property. This can be used alongside the `--c` ulility to set the text color as demonstrated below.

<div style="--d:flex; --mb:4rem;">
    <div style="--p:1rem; --fx:1; --bg:#eee; --as:flex-start; --maxw:600px;">
        <div style="--fx:1; --p:3rem; --mb:.5rem; --d:flex; --jc:center;">
            <span id="target-text-3d" style="--text-3d:#406DC4; --c:#57A1DB; --weight:bold; --size: 5rem">Hello World!</span>
        </div>
            <div>
                <input type="color" id="color" name="color" value="#57A1DB" style="--d:inline-block;">
                <input type="color" id="text-3d" name="text-3d" value="#406DC4" style="--d:inline-block;">
            </div>
            <div class="markdown" style="--maxw:800px; --w:100%; --pos:relative;">
<div class="highlight" style="--mb:0;"><pre class="chroma" style="--mt:.75rem;"><code class="language-html" data-lang="html"><span class="p">&lt;</span><span class="nt">div</span> <span class="na">style</span><span class="o">=</span><span class="s">"<span id="text-3d-label">--text-3d:#406DC4;</span> <span id="color-label">--c:#57A1DB;</span>"</span></span><span class="p"></span><span class="p">&gt;</span> ... <span class="p">&lt;</span><span class="p">/</span><span class="nt">div</span><span class="p">&gt;</span></code></pre>
            </div>
        </div>
    </div>  
</div>
<script>liveprop('text-3d', '--text-3d', '', 'target-text-3d');</script>
<script>liveprop('color', '--c', '', 'target-text-3d');</script>