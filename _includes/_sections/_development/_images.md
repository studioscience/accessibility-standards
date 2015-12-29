### Images  

- Use appropriate alt text on all images.

### SVG elements and ARIA roles  

- Use `role="img"` on SVG elements to identify them as graphics.  

- Give `title` and `description` elements `id`s and use an `aria-labelledby` attribute to reference the id values to provide accessible name and description.  

- Add `role="presentation"` to elements inside the SVG, such as `circle`, `path`, &c.  

An example is provided below:  

<pre><code class="language-markup">&lt;svg xmlns=http://www.w3.org/2000/svg role="img" aria-labelledby="title desc"&gt;
    &lt;title id="title"&gt;Circle&lt;/title&gt;
    &lt;desc id="desc"&gt;Blue circle with black border&lt;/desc&gt;
    &lt;circle role="presentation" cy="60" r="55" stroke="black" stroke-width="1" fill="blue" /&gt;
&lt;/svg&gt;
</code></pre>
