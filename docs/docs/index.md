---
title: "Bonsai CSS - A Utility Complete CSS Framework for less than 10kb"
description: "A complete CSS solution allowing you to build beautifully crafted web interfaces with ease."
layout: default

eleventyNavigation:
  key: BonsaiCSS
  title: Docs Bonsai CSS
  has_children: true
  order: 30
---

<div id="learn-more"></div>

### Why build with Bonsai

<h4 style="--lh:2.2rem">Bonsai CSS is a super lightweight, fully responsive, utlity complete framework. All you need to build beautifully crafted web interfaces with ease.</h4>

- A utility complete CSS framework solution
- Classless base styling of semantic HTML elements
- All packed inside a gzipped size of just **8kb**
- Drop n Build - No compiling required

<br>

### Classless Base Element Styling

Before you even start adding class or style attributes, **Bonsai CSS** applies a base styling to your semantic HTML elements. Simply load **Bonsai CSS** in to your project and your base HTML elements will be beautifully styled with zero effort.

<br>

### Utility Complete CSS

In terms of CSS frameworks, utilities commonly refer to a CSS class which applies a single CSS property to an element. For example a class name of `.bg-green` would apply `background-color: green` to that element. A **Utility Complete** framework provide a complete set of utilites for the majority of CSS properties.

- Super quick protyping with out leaving your HTML
- CSS size remains constant as your project grows

There is nothing new about the concept of utility complete CSS and today you will find any number of utility first frameworks to pick from. What is unique about Bonsai however, is how these utilities are implemented. Traditionally utility complete frameworks include a rule for every common CSS property/value combination. Not only does this result in an incredibly large CSS filesize it also means you are restricted to a set number of property/value combinations as defined by the framework developers. Bonsai CSS uses a different approach. Instead utilities are defined by just the property and you the developer define the value. Not only is the resulting CSS a fraction of the size, you also have full access to the CSS spec for each property.

##### Style based utilities

```html
<div style="--bg:var(--dark)">
  <div>
    <div style="--bg:#2A2A2A">
      <div>
        <div style="--bg:rgb(42,42,42)">
          <div>
            <div style="--bg:rgba(0,0,0,.8)"><div></div></div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
```

<br>

### Responsive design and media queries

Where relavent utilities can be applied conditionally to each screensize. This allows you to apply utilities to specific screen size making responsive design a walk in the park.

By default there are four breakpoints set in correspondance with the most common device resolutions.

```html
<!-- Small '-sm' -->
@media (min-width: 640px) { ... }

<!--Medium '-md' -->
@media (min-width: 768px) { ... }

<!--Large '-lg' -->
@media (min-width: 1024px) { ... }

<!-- Extra Large '-xl' -->
@media (min-width: 1280px) { ... }
```

To assign a utility to a set screensize breakpoint simply prepend with a `-` followed by the breakpoint shorthand name. Media queries by default use a mobile-first approach, which as it sounds is designing for the smallest screen and working your way up.

Consider the following example where `--d` is the Bonsai utility for the `display` CSS property. Button is `disply:block` by default. `display:none` from medium size screens up.

```html
<button style="--d:block; --d-md:none">Only visible on small screens</button>
```

<br>

<h2 style="--ta: center;">Discover limitless possibilites</h2>

<br>

<div style="--cc:1; --cc-sm:2; --cc-xl:3; --cg:1.5rem; --bg:#eee; --p:1.5rem; --pos:relative">
    <figure class="accent" style="--mb:1.5rem;">
        <img src="https://source.unsplash.com/e0qLqlrmEHk/340x220" alt="Aliquam erat volutpat">
        <figcaption>
          <h4>Nullam malesuada erat</h4>
          <p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Donec odio. Quisque volutpat mattis eros. Nullam malesuada erat ut turpis. </p>
          <button aria-label="Sample Button">Read More</button>
        </figcaption>
    </figure>
    <figure class="accent" style="--mb:1.5rem;">
        <img src="https://source.unsplash.com/9UVmlIb0wJU/130x130" alt="Aliquam erat volutpat" style="--mt:2rem; --mr:auto;--ml:auto;--br:50%">
        <figcaption style="--ta:center">
          <h4>Sarah Drake</h4>
          <p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Donec odio. Quisque volutpat mattis eros.</p>
        </figcaption>
    </figure>
    <div style="--d:grid; --mb:1.5rem;">
      <div style="--gc:1/4; --gr:1/4">
        <img src="https://source.unsplash.com/IP1rSwr8R6o/400x400" alt="Aliquam erat volutpat">
      </div>
      <div style="--gc:2/5; --gr:2/5;">
        <img src="https://source.unsplash.com/5WqxUM2cERo/400x400" alt="Aliquam erat volutpat">   
      </div>
    </div>
    <figure class="accent" style="--mb:1.5rem; --w:100%">
        <figcaption>
            <label>First Name
                <input type="text" placeholder="John">
            </label>
            <label>Last Name
                <input type="text" placeholder="John">
            </label>
            <button style="--w:100%" aria-label="Sample Button">Submit</button>
        </figcaption>
    </figure>
    <figure class="accent" style="--mb:1.5rem;">
        <figcaption>
            <img src="https://source.unsplash.com/1IXs-hiCqts/50x50" alt="Aliquam erat volutpat" style="--br: 4px; --mt:1rem">
            <h4>Donec odio</h4>
            <p>Donec odio. Quisque volutpat mattis eros. Nullam malesuada erat ut turpis. </p>
        </figcaption>
    </figure>
    <figure style="--mb:1.5rem;">
        <img src="https://source.unsplash.com/IP1rSwr8R6o/340x280" alt="Aliquam erat volutpat" style="--br:4px">
        <figcaption class="accent" style="--mt:-3rem;--ml:1rem;--mr:1rem;--pb:2rem">
          Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Donec odio. Quisque volutpat mattis eros.
        </figcaption>
    </figure>
    <div class="accent" style="--mb:1.5rem; --p:1rem">
      <div style="--d:flex; --ai:flex-start; --bb:1px solid #ddd; --my:.5rem">
          <img src="https://source.unsplash.com/4nulm-JUYFo/55x55" alt="Aliquam erat volutpat" style="--mt:1rem; --br:50%">
          <div style="--ml:1rem; --fx:1">
              <h5 style="--mb:0">Jane Doe</h5>
              <p style="--size: .85em">Lorem ipsum dolor sit amet, consectetuer adipiscing elit.</p>
          </div>
      </div>
      <div style="--d:flex; --ai:flex-start; --bb:1px solid #ddd; --my:.5rem">
          <img src="https://source.unsplash.com/6anudmpILw4/55x55" alt="Aliquam erat volutpat" style="--mt:1rem; --br:50%">
          <div style="--ml:1rem; --fx:1">
              <h5 style="--mb:0">Viktor Jones</h5>
              <p style="--size: .85em">Lorem ipsum dolor sit amet, consectetuer adipiscing elit.</p>
          </div>
      </div>
      <div style="--d:flex; --ai:flex-start; --bb:1px solid #ddd; --my:.5rem">
          <img src="https://source.unsplash.com/b1Hg7QI-zcc/55x55" alt="Aliquam erat volutpat" style="--mt:1rem; --br:50%">
          <div style="--ml:1rem; --fx:1">
              <h5 style="--mb:0">Marcia Stanley</h5>
              <p style="--size: .85em">Lorem ipsum dolor sit amet, consectetuer adipiscing elit.</p>
          </div>
      </div>
      <div style="--d:flex; --ai:flex-start; --mt:.5rem">
          <img src="https://source.unsplash.com/95UF6LXe-Lo/55x55" alt="Aliquam erat volutpat" style="--mt:1rem; --br:50%">
          <div style="--ml:1rem; --fx:1">
              <h5 style="--mb:0">Giovanni Santana</h5>
              <p style="--size: .85em">Lorem ipsum dolor sit amet, consectetuer adipiscing elit.</p>
          </div>
      </div>
    </div>
    <figure class="accent" style="--mb:1.5rem;">
      <img src="https://source.unsplash.com/0gTyPRZXnho/340x220" alt="Aliquam erat volutpat">
      <figcaption>
        <h4 style="--m:0">Nullam malesuada erat</h4>
        <span style="--size:.85em; --c:#777">18 hours ago | <a href="#">Entertainment</a></span>
      </figcaption>
    </figure>
    <div class="accent primary" style="--p:2rem 1rem; --ta:center; --mb:1.5rem;">
      <svg xmlns="https://www.w3.org/2000/svg" style="--w:50px; --h:auto" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 16V8a2 2 0 0 0-1-1.73l-7-4a2 2 0 0 0-2 0l-7 4A2 2 0 0 0 3 8v8a2 2 0 0 0 1 1.73l7 4a2 2 0 0 0 2 0l7-4A2 2 0 0 0 21 16z"></path><polyline points="7.5 4.21 12 6.81 16.5 4.21"></polyline><polyline points="7.5 19.79 7.5 14.6 3 12"></polyline><polyline points="21 12 16.5 14.6 16.5 19.79"></polyline><polyline points="3.27 6.96 12 12.01 20.73 6.96"></polyline><line x1="12" y1="22.08" x2="12" y2="12"></line></svg>
      <h4>Sarah Drake</h4>
      <p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Quisque volutpat mattis eros.</p>
    </div>
    <span class="accent group" style="--m:0 0 1.5rem; --w:100%">
      <button aria-label="upload">
        <svg aria-hidden="true" focusable="false" role="img" xmlns="https://www.w3.org/2000/svg" viewBox="0 0 576 512" class="svg-inline--fa fa-download fa-w-18" style="transform-origin: 0.5625em 0.4375em 0px;"><g transform="translate(288 256)" class=""><g transform="translate(0, -32)  scale(1, 1)  rotate(0 0 0)" class=""><path fill="currentColor" d="M528 288h-92.1l46.1-46.1c30.1-30.1 8.8-81.9-33.9-81.9h-64V48c0-26.5-21.5-48-48-48h-96c-26.5 0-48 21.5-48 48v112h-64c-42.6 0-64.2 51.7-33.9 81.9l46.1 46.1H48c-26.5 0-48 21.5-48 48v128c0 26.5 21.5 48 48 48h480c26.5 0 48-21.5 48-48V336c0-26.5-21.5-48-48-48zm-400-80h112V48h96v160h112L288 368 128 208zm400 256H48V336h140.1l65.9 65.9c18.8 18.8 49.1 18.7 67.9 0l65.9-65.9H528v128zm-88-64c0-13.3 10.7-24 24-24s24 10.7 24 24-10.7 24-24 24-24-10.7-24-24z" transform="translate(-288 -256)" class=""></path></g></g></svg>
      </button>
      <input type="text" placeholder="filename.txt" aria-label="Filename">
    </span>
    <div class="accent primary" style="--mb:1.5rem; --pos:relative; --pt: 75%;">
        <div style="--pos:absolute; --inset:0">
          <img style="--objf:cover; --h:100%; --w:100%;" src="https://source.unsplash.com/eluzJSfkNCk/300x400" alt="Aliquam erat volutpat">
        </div>
        <div style="--p:1rem">
          <button class="white" style="--w:100%" aria-label="Sample Button">Sign in</button>
          <button style="--w:100%; --bc:var(--primary);" aria-label="Sample Button">Create an account</button>
        </div>
    </div>
    <div style="--p:2rem 1rem; --ta:center; --mb:1.5rem;">
      <svg xmlns="https://www.w3.org/2000/svg" style="--w:50px; --h:auto" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 16V8a2 2 0 0 0-1-1.73l-7-4a2 2 0 0 0-2 0l-7 4A2 2 0 0 0 3 8v8a2 2 0 0 0 1 1.73l7 4a2 2 0 0 0 2 0l7-4A2 2 0 0 0 21 16z"></path><polyline points="7.5 4.21 12 6.81 16.5 4.21"></polyline><polyline points="7.5 19.79 7.5 14.6 3 12"></polyline><polyline points="21 12 16.5 14.6 16.5 19.79"></polyline><polyline points="3.27 6.96 12 12.01 20.73 6.96"></polyline><line x1="12" y1="22.08" x2="12" y2="12"></line></svg>
      <h3>Be Inspired</h3>
      <p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Quisque volutpat mattis eros.</p>
    </div>
    <div class="accent primary" style="--mb:1.5rem; --pos:relative; --pt: 75%;">
      <div style="--pos:absolute; --inset:0">
        <img style="--objf:cover; --h:100%; --w:100%;" src="https://source.unsplash.com/aExT3y92x5o/400x350" alt="Aliquam erat volutpat">
      </div>
      <button style="--pos:absolute; --top:8px; --right:0; --bg:var(--primary); --p:8px 5px;" aria-label="Sample Button">
        <svg xmlns="https://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-heart"><path d="M20.84 4.61a5.5 5.5 0 0 0-7.78 0L12 5.67l-1.06-1.06a5.5 5.5 0 0 0-7.78 7.78l1.06 1.06L12 21.23l7.78-7.78 1.06-1.06a5.5 5.5 0 0 0 0-7.78z"></path></svg>
      </button>
      <div style="--p:1rem; --pos:relative">
        <h6 style="--m:0;">Quisque volutpat mattis eros.</h6>
        <h4 style="--mb:.2rem; --weight:bold;">New Beginnings</h4>
      </div>
    </div>
    <div class="accent "style="--p:4rem 1.5rem; --mb:1.5rem;">
      <h4 style="--c:var(--primary); --m:0;">Welcome</h4>
      <h3 style="--weight:600">Quisque imperdiet</h3>
      <p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Quisque volutpat mattis eros.</p>
      <button aria-label="Sample Button">View More</button>
    </div>
    <div class="accent" style="--mb:1.5rem; --p:1rem; --cc:2;">
      <div style="--mb:1rem; --d:inline-block; --bi:avoid;">
        <img src="https://source.unsplash.com/4nulm-JUYFo/120x120" alt="Aliquam erat volutpat" style="--br:4px">
        <h6 style="--m:0">Quisque volutpat</h6>
        <h5 style="--m:0; --weight:bold">€30.00</h5>
      </div>
      <div style="--mb:1rem; --d:inline-block; --bi:avoid;">
        <img src="https://source.unsplash.com/juESZxMhtXk/120x120" alt="Aliquam erat volutpat" style="--br:4px">
        <h6 style="--m:0">Lorem ipsum dolor sit amet</h6>
        <h5 style="--m:0; --weight:bold">€90.00</h5>
      </div>
      <div style="--mb:1rem; --mt:3rem; --d:inline-block; --bi:avoid;">
        <img src="https://source.unsplash.com/mWYhrOiAgmA/120x120" alt="Aliquam erat volutpat" style="--br:4px">
        <h6 style="--m:0">Consectetuer adipiscing elit</h6>
        <h5 style="--m:0; --weight:bold">€60.00</h5>
      </div>
      <div style="--d:inline-block; --bi:avoid;">
        <img src="https://source.unsplash.com/Pd585pphU-4/120x120" alt="Aliquam erat volutpat" style="--br:4px">
        <h6 style="--m:0">Quisque volutpat mattis</h6>
        <h5 style="--m:0; --weight:bold">€120.00</h5>
      </div>
    </div>
    <div class="accent" style="--mb:1.5rem; --p:1rem; --bg:#fafafa;">
      <div style="--d:flex; --ai:flex-start; --bb:1px solid #ddd; --my:.5rem">
          <div style="--size:2em; --bg:#eee; --w:60px; --lh:60px; --ta:center; --mt: .75rem; --c:var(--primary)">1</div>
          <div style="--ml:1rem; --fx:1">
              <h5 style="--mb:0">Quisque volutpat</h5>
              <p style="--size: .85em">Lorem ipsum dolor sit amet, consectetuer adipiscing elit.</p>
          </div>
      </div>
      <div style="--d:flex; --ai:flex-start; --bb:1px solid #ddd; --my:.5rem">
          <div style="--size:2em; --bg:#eee; --w:60px; --lh:60px; --ta:center; --mt: .75rem; --c:var(--primary)">2</div>
          <div style="--ml:1rem; --fx:1">
              <h5 style="--mb:0">Nunc dignissim risus</h5>
              <p style="--size: .85em">Lorem ipsum dolor sit amet, consectetuer adipiscing elit.</p>
          </div>
      </div>
      <div style="--d:flex; --ai:flex-start; --bb:1px solid #ddd; --my:.5rem">
          <div style="--size:2em; --bg:#eee; --w:60px; --lh:60px; --ta:center; --mt: .75rem; --c:var(--primary)">3</div>
          <div style="--ml:1rem; --fx:1">
              <h5 style="--mb:0">Cras ornare tristique</h5>
              <p style="--size: .85em">Lorem ipsum dolor sit amet, consectetuer adipiscing elit.</p>
          </div>
      </div>
      <div style="--d:flex; --ai:flex-start; --mt:.5rem">
          <div style="--size:2em; --bg:#eee; --w:60px; --lh:60px; --ta:center; --mt: .75rem; --c:var(--primary)">4</div>
          <div style="--ml:1rem; --fx:1">
              <h5 style="--mb:0">Praesent placerat</h5>
              <p style="--size: .85em">Lorem ipsum dolor sit amet, consectetuer adipiscing elit.</p>
          </div>
      </div>
    </div>
    <div class="accent" style="--mb:1.5rem;">
      <div style="--p:1.5rem;">
        <h4 style="--weight: bold; --mb:.5rem;">Join us today!</h4>
        <p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Donec odio. Quisque volutpat mattis eros.</p>
      </div>
      <div class="group" style="--m:0; --w:100%;">
        <button class="grey" style="--fx:1; --btlr:0; --b:0" aria-label="Sample Button">Learn More</button>
        <button style="--fx:1; --btrr:0; --b:0" aria-label="Sample Button">Sign Up</button>
      </div>
    </div>
    <div style="--mb:1.5rem; --p:1rem">
      <div style="--d:flex; --ai:flex-start; --bb:1px solid #ddd; --my:.5rem">
          <img src="https://source.unsplash.com/cNTK6s8Rurc/55x55" alt="Aliquam erat volutpat" style="--mt:1rem; --br:var(--border-radius)">
          <div style="--ml:1rem; --fx:1">
              <h5 style="--mb:0 --weight:bold">Lorem ipsum dolor sit amet</h5>
              <p style="--size: .85em; --op:.5">January 18, 2020</p>
          </div>
      </div>
      <div style="--d:flex; --ai:flex-start; --bb:1px solid #ddd; --my:.5rem">
          <img src="https://source.unsplash.com/vKK6sWu_4YY/55x55" alt="Aliquam erat volutpat" style="--mt:1rem; --br:var(--border-radius)">
          <div style="--ml:1rem; --fx:1">
              <h5 style="--mb:0 --weight:bold"> Ut enim ad minim veniam</h5>
              <p style="--size: .85em; --op:.5">March 24, 2020</p>
          </div>
      </div>
      <div style="--d:flex; --ai:flex-start; --my:.5rem">
          <img src="https://source.unsplash.com/2jyJLvWWQOk/55x55" alt="Aliquam erat volutpat" style="--mt:1rem; --br:var(--border-radius)">
          <div style="--ml:1rem; --fx:1">
              <h5 style="--mb:0 --weight:bold">Nemo enim ipsam voluptatem</h5>
              <p style="--size: .85em; --op:.5">Arpil 04, 2020</p>
          </div>
      </div>
    </div>
    <div class="accent" style="--p:1.5rem; --mb:1.5rem;">
      <h3>Questionaire</h3>
      <p>Pellentesque odio nisi, euismod in, pharetra a, ultricies in, diam. Sed arcu.</p>
      <div style="--m:.5rem">
        <input type="checkbox" id="checkbox-1">
        <label for="checkbox-1">Cras ornare tristique elit</label>
      </div>
      <div style="--m:.5rem">
        <input type="checkbox" id="checkbox-1">
        <label for="checkbox-1">Praesent placerat risus quis</label>
      </div>
      <div style="--m:.5rem">
        <input type="checkbox" id="checkbox-1">
        <label for="checkbox-1">Fusce pellentesque suscipit</label>
      </div>
      <div style="--m:.5rem">
        <input type="checkbox" id="checkbox-1">
        <label for="checkbox-1">Vestibulum commodo felis</label>
      </div>
      <button style="--mt:1rem" aria-label="Sample Button">Submit</button>
    </div>
    <div class="accent primary" style="--mb:1.5rem; --pos:relative; --pt: 75%;">
      <div style="--pos:absolute; --inset:0">
        <img style="--objf:cover; --h:100%; --w:100%; --op:.7" src="https://source.unsplash.com/76-58HpxvpQ/350x400" alt="Image">
      </div>
      <button class="white" style="--pos:absolute; --top:8px; --right:0; --p:8px 5px; --bc:transparent" aria-label="Sample Button">
        <svg xmlns="https://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-bookmark"><path d="M19 21l-7-5-7 5V5a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2z"></path></svg>
      </button>
      <div style="--p:1rem; --pos:relative">
        <h6 style="--m:0; --tt:uppercase; --ls:1px">CULTURE</h6>
        <h4 style="--m:0 0 .2rem;">Lorem ipsum dolor</h4>
        <span style="--c:gold">
          5.0
          <svg xmlns="https://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-star"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon></svg>
        </span>
        <span style="--size:.85em">(48 Reviews)</span>
      </div>
    </div>
    <div style="--d:grid; --gar:200px; --gg:10px;  --mb:1.5rem;">
      <div style="--gc:1/2; --gr:1/3;">
        <img style="--h:100%; --objf:cover;" src="https://source.unsplash.com/z9vnGEGZPjw/400x400" alt="Aliquam erat volutpat">
      </div>
      <div style="--gc:2/3; --gr:1/2;">
        <img style="--h:100%; --objf:cover;" src="https://source.unsplash.com/jSVBtxVAV8U/400x400" alt="Aliquam erat volutpat">   
      </div>
      <div style="--gc:1/2; --gr:3/4;">
        <img style="--h:100%; --objf:cover;" src="https://source.unsplash.com/gnG1q2d0mbA/400x400" alt="Aliquam erat volutpat">
      </div>
      <div style="--gc:2/3; --gr:2/4;">
        <img style="--h:100%; --objf:cover;" src="https://source.unsplash.com/Dz6HuHE2Ki0/400x400" alt="Aliquam erat volutpat">   
      </div>
    </div>
    <div class="accent" style="--bg:white; --p:1.5rem; --mb:1.5rem;">
      <p style="--c:#aaa">Our site uses cookies. Learn more about our use of cookies: <a href="#">Cookie policy</a></p>
      <button style="--w:100%" aria-label="Sample Button">Submit</button>
    </div>
    <div style="--d:flex; --p:2rem 1rem; --mb:1.5rem;">
      <svg xmlns="https://www.w3.org/2000/svg" style="--w:50px; --h:auto; --mr:.5rem" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 16V8a2 2 0 0 0-1-1.73l-7-4a2 2 0 0 0-2 0l-7 4A2 2 0 0 0 3 8v8a2 2 0 0 0 1 1.73l7 4a2 2 0 0 0 2 0l7-4A2 2 0 0 0 21 16z"></path><polyline points="7.5 4.21 12 6.81 16.5 4.21"></polyline><polyline points="7.5 19.79 7.5 14.6 3 12"></polyline><polyline points="21 12 16.5 14.6 16.5 19.79"></polyline><polyline points="3.27 6.96 12 12.01 20.73 6.96"></polyline><line x1="12" y1="22.08" x2="12" y2="12"></line></svg>
      <div>
        <h3 style="--m:0">Be Creative</h3>
        <p style="--m:0">Lorem ipsum dolor sit amet</p>
      </div>
    </div>
    <div class="accent primary" style="--d:flex; --fd:column; --mb:1.5rem;">
        <img src="https://source.unsplash.com/-4kwrnRrk-E/340x220" alt="Aliquam erat volutpat">
        <a href="#" style="--c:white; --px:10px; --ml:auto; --size:2rem" aria-label="Sample Link">
          <svg style="--ml:auto;" xmlns="https://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-arrow-right"><line x1="5" y1="12" x2="19" y2="12"></line><polyline points="12 5 19 12 12 19"></polyline></svg>
        </a>
    </div>
    <div class="accent" style="--mb:1.5rem">
      <h5 style="--p:.25rem 1.5rem .75rem; --bb:1px solid #ddd">Beautiful Designs</h5>
      <div style="--p:.25rem 1.5rem 1.5rem; --bg:white;">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Explicabo ex fugiat quisquam. </p>
        <button aria-label="Sample Button">Read More...</button>
      </div>
    </div>
    <div style="--d:grid; --gtc:auto 2.2rem; --mb:1.5rem;">
      <div style="--gc:1/2;">
        <img style="--h:100%; --objf:cover" src="https://source.unsplash.com/jSVBtxVAV8U/400x400" alt="Aliquam erat volutpat">   
      </div>
      <div style="--gc:2/3">
        <h3 style="--wm:vertical-lr">A Perfect Place</h3>
      </div>
    </div>
    <div style="--pos:absolute; --left:0; --right:0; --bottom:0; --grad-bottom:white; --p: 600px 0 200px">
      <img src="logo.png" alt="bonsaicss" style="--m:40px auto 0; --d: block;">
      <h1 style="--ta:center;">Get creative with Bonsai CSS</h1>
    </div>
</div>
