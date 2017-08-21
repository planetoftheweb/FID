 <section>
  <h1>Learning HTML</h1>
  <h2>by Ray Villalobos</h2>
  <p><small>Use arrow keys to advance or esc</small></p>
</section>

<!-- ============================== slide -->
 <section>
  <h1>What is HTML?</h1>
  <h2>HyperText Markup Language</h2>

  <div class="fragment">
    <h3>HYPERTEXT</h3>
    <p>Documents that can be linked together</p>
  </div>

  <div class="fragment">
    <h3>MARKUP</h3>
    <p>Special Syntax (markup) for annotating a document</p>
  </div>
</section>

<!-- ============================== slide -->
<section>
  <h1>HTML</h1>
  <h2>Creating semantic HTML</h2>
  <img class="fragment" src="images/webpage.png" alt="html page">
  <ul>
    <li class="fragment">Define structure of the information on page</li>
    <li class="fragment">Should never include layout information</li>
    <li class="fragment">If the HTML is badly written, everything else can fail</li>
  </ul>
</section>

<!-- ============================== slide -->
<section>
  <h1>Tag Structure</h1>
  <pre><code class="html" contenteditable>&lt;ELEMENT [ATTRIBUTE[=&quot;VALUE&quot;]]...&gt;content[&lt;/ELEMENT&gt;]</code></pre>
  <ul>
    <li class="fragment">Markup tags are opened with <code>&lt;&gt;</code> signs</li>
    <li class="fragment">A tag starts with a <code>&lt;</code> sign and the name of the element</li>
    <li class="fragment">The element can then have <strong>no attributes</strong> or <br />an <strong>infinite number</strong> of attributes and values in <strong>no particular order</strong></li>
    <li class="fragment">Some tags <strong>wrap around</strong> content and some don't</code></li>
    <li class="fragment">If they wrapped, content is placed between opening and closing tags</li>
  </ul>
</section>

<!-- ============================== slide -->
<section>
  <h1>Container tags</h1>
  <ul>
    <li class="fragment">Container tags usually start with <code contenteditable="true">&lt;&gt;</code> and end with <code contenteditable="true">&lt;/&gt;</code>.</li>
    <li class="fragment">Attributes are <strong>optional</strong> and not always needed</li>
    <li class="fragment">The <strong>meaning</strong> of the content is changed by the tags</li>
    <li class="fragment">What they look like is not important</li>
  </ul>
</section>

<!-- ============================== slide -->
<section>
  <h1>Standalone tags</h1>
  <ul>
    <li class="fragment">Do something immediately, so <strong>don't need</strong> ending tags</li>
    <li class="fragment"><strong>Example:</strong> <a href="http://www.w3schools.com/tags/tag_img.asp">Place an image</a>, create a <a href="http://www.w3schools.com/tags/tag_br.asp">line break</a> or add a <a href="http://www.w3schools.com/tags/tag_hr.asp">horizontal rule</a></li>
  </ul>
</section>

<!-- ============================== slide -->
<section>
  <h1>Attributes</h1>
  <ul>
    <li class="fragment">Attributes are optional, but can be essential</li>
    <li class="fragment">The browser can't display an <code>&lt;img&gt;</code> tag without a <code>src</code> attribute</li>
    <li class="fragment">An anchor tag without the href attribute doesn't go anywhere.</li>
  </ul>
</section>

<!-- ============================== slide -->
<section>
  <h1>Importance</h1>
  <ul>
    <li class="fragment"><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements">Heading Elements</a> (<code>&lt;h1&gt;</code>, <code>&lt;h2&gt;</code>, <code>&lt;h3&gt;</code>, <code>&lt;h4&gt;</code>, <code>&lt;h5&gt;</code>, <code>&lt;h6&gt;</code>) denote relative importance of the elements</li>
    <li class="fragment">A <code>&lt;h1&gt;</code> headline is more important than an <code>&lt;h2&gt;</code> headline</li>
    <li class="fragment">Use it to structure a document...like a book or outline</li>              
  </ul>
</section>

<!-- ============================== slide -->
<section>
  <h1>Compound Tags</h1>
  <ul>
    <li class="fragment">Most tags live inside other tags, but others <strong>have to</strong> in order to make sense</li>
    <li class="fragment"><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul">Lists</a> are a good example of <strong>compound tags</strong></li>
    <li class="fragment">Can be <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol">ordered</a>, <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul">unordered</a> or <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dl">definition</a> lists</li>
  </ul>
</section>

<!-- ============================== slide -->
<section>
  <h1>Block Level</h1>
  <ul>
    <li class="fragment"><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Block-level_elements">Major containers</a> of content</li>
    <li class="fragment">Are usually formatted in a new line before and after the tags by browsers</li>
    <li class="fragment">Examples: <code><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements">&lt;h1&gt;</a></code>, <code><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/p">&lt;p&gt;</a></code>, <code><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul">&lt;ul&gt;</a></code>, <code><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/div">&lt;div&gt;</a></code></li>
  </ul>
</section>

<!-- ============================== slide -->
<section>
  <h1>Inline tags</h1>
  <ul>
    <li class="fragment"><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Inline_elemente">Less significant</a> sections of text</li>
    <li class="fragment">Don't usually display a newline before and after the tag</li>
    <li class="fragment">Used inside block level tags</li>
  </ul>
</section>

<!-- ============================== slide -->
<section>
  <h1>Structural Tags</h1>
  <ul>
    <li class="fragment">Some tags identify the function of the content</li>
    <li class="fragment"><a href="http://www.w3schools.com/html/html5_semantic_elements.asp">Examples</a>: <code>&lt;header&gt;, &lt;nav&gt;, &lt;section&gt;, &lt;article&gt;, &lt;aside&gt;, &lt;figcaption&gt;, &lt;figure&gt;, &lt;footer&gt;</code></li>
    <li class="fragment">You can use CSS or javascript to target these</li>
  </ul>
</section>

<!-- ============================== slide -->
<section>
  <h1>Generic Tags</h1>
  <ul>
    <li class="fragment">Generic tags let you create your own sections of content</li>
    <li class="fragment">&lt;div&gt; generic block level tag</li>

    <li class="fragment">&lt;span&gt; generic inline tag.</li>
    <li class="fragment">You can add meaning to these tags using the <code>id</code> and <code>class</code> attributes</li>
  </ul>
</section>

<!-- ============================== slide -->
<section>
  <h1>Class vs IDs</h1>
  <ul>
    <li class="fragment">Different ways of adding meaning to content</li>
    <li class="fragment"><strong>Class</strong>es can be used many times on the same page</li>
    <li class="fragment"><strong>ID</strong>s should be used once per page</li>
    <li class="fragment">You can have more than one class on the same tag...separate with spaces</li>
  </ul>
</section>

<!-- ============================== slide -->
<section>
  <h1>Page Structure</h1>
  <ul>
    <li class="fragment">
<pre><code class="html" contenteditable>&lt;!DOCTYPE html&gt;
&lt;html lang=&quot;en&quot;&gt;
&lt;head&gt;
&lt;meta charset=&quot;utf-8&quot; /&gt;
&lt;title&gt;&lt;/title&gt;
&lt;/head&gt;
&lt;body&gt;
&lt;/body&gt;
&lt;/html&gt;</code></pre>
  </li>
    <li class="fragment">The <code>DOCTYPE</code> is the version of HTML page uses</li>
    <li class="fragment"><code>&lt;html&gt;</code> the parent of all tags</li>
    <li class="fragment"><code>&lt;head&gt;</code> Info you don't want to show users</li>
    <li class="fragment"><code>&lt;title&gt;</code> The title of the document</li>
    <li class="fragment"><code>&lt;body&gt;</code> Content you want the users to see</li>
  </ul>
</section>

<!-- ============================== slide -->
<section>
  <h1>Whitespace</h1>
  <ul>
    <li class="fragment">Has no effect on final output</li>
    <li class="fragment">Extra space, tabs, carriage returns do not render on the browser</li>
    <li class="fragment">They can help make your code easier to read</li>
  </ul>
</section>

<!-- ============================== slide -->
<section>
  <h1>Special Elements</h1>
  <ul>
    <li class="fragment">Some characters like &amp; should be encoded as <code>&amp;amp;</code>.</li>
    <li class="fragment">Lots of other <a href="http://www.zytrax.com/tech/web/entities.html">special characters</a></li>
    <li class="fragment">Watch out for curly quotes when pasting</li>
    <li class="fragment">Add comments with <code>&lt;!-- comment --&gt;</code></li>
  </ul>
</section>

<!-- ============================== slide -->
<section>
  <h1>Validating your code</h1>
  <ul>
    <li class="fragment"><a href="http://validator.w3.org/">Validating your code</a> checks for errors</li>
    <li class="fragment">Tools like <a href="http://jsbin.com/">JSBin</a> or <a href="http://codepen.io/">CodePen</a> can help</li>
    <li class="fragment">Use a <a href="https://chrome.google.com/webstore/detail/html-validator/cgndfbhngibokieehnjhbjkkhbfmhojo">validating extension</a> for your browser</li>
    <li class="fragment">Learn &amp; install <a href="http://emmet.io/">Emmet</a></li>
    <li class="fragment">Lots of <a href="http://iviewsource.com/presentations/errorfreetooling/#/">other tools</a> (advanced users only)</li>
  </ul>
</section>

<!-- ============================== slide -->
<section>
  <h1>In-Class Exercises</h1>
  <h2>Part 1 of 4</h2>
  <ul>
    <li class="fragment"><a class="jsbin-embed" href="http://jsbin.com/uSAJuraM/1/embed?html,output">Try It</a> Try adding a <code>&lt;strong&gt;</code> tag to make the word 'jumps' look bold</li>
    <li class="fragment"><a class="jsbin-embed" href="http://jsbin.com/igECUTO/3/embed?html,output">Try it</a> Add your own second paragraph with <code>&lt;strong&gt;</code> and <code>&lt;em&gt;</code> tags</li>
    <li class="fragment"><a class="jsbin-embed" href="http://jsbin.com/ExumosIZ/2/embed?html,output">Try it</a> Add a <code>&lt;hr&gt;</code> tag and another image.</li>
  </ul>
</section>

<section>
  <h1>In-Class Exercises</h1>
  <h2>Part 2 of 4</h2>
  <ul>
    <li class="fragment"><a class="jsbin-embed" href="http://jsbin.com/oxIWowu/2/embed?html,output">Try it</a> Add a link to google.com, then make the image clickable to iviewsource.com</li>
    <li class="fragment"><a class="jsbin-embed" href="http://jsbin.com/olOmAHUM/1/embed?html,output">Try it</a> Add a new panagram in the same format.</li>    
    <li class="fragment"><a class="jsbin-embed" href="http://jsbin.com/uyuqequ/1/embed?html,output">Try It</a> Add a list of american countries that is ordered from north to south</li>
  </ul>
</section>

<section>
  <h1>In-Class Exercises</h1>
  <h2>Part 3 of 4</h2>
  <ul>
    <li class="fragment"><a class="jsbin-embed" href="http://jsbin.com/uyuqequ/4/embed?html,output">Try It</a> Change the first <code>&lt;h1&gt;</code> and <code>&lt;p&gt;</code> tags to <code>&lt;strong&gt;</code> tags. Note what happens to the spacing.</li>
    <li class="fragment"><a class="jsbin-embed" href="http://jsbin.com/iNUSOqI/3/embed?html,output">Try it</a> Add strong tags to the contant info titles (email, twitter and flickr. Do it before the colon ':') on Contact me section</li>
    <li class="fragment"><a class="jsbin-embed" href="http://jsbin.com/IFuLUTi/2/embed?html,output">Try it</a> Add a footer tag to the section with my contac</li>
  </ul>
</section>

<section>
  <h1>In-Class Exercises</h1>
  <h2>Part 4 of 4</h2>
  <ul>
    <li class="fragment"><a class="jsbin-embed" href="http://jsbin.com/iKAhOdUR/2/embed?html,output">Try It</a> Wrap the experience section with a div that uses id of experience. Wrap each of the contact me  titles (email, twitter, flickr) with a span that has a class of social.</li>
    <li class="fragment"><a class="jsbin-embed" href="http://jsbin.com/ibesIXi/1/embed?html,output">Try it</a> Add the userinfo class to the experience section</li>
    <li class="fragment"><a class="jsbin-embed" href="http://jsbin.com/ONAyUgOh/2/embed?html,output">Try it</a> Add another paragraph with some tabs and spaces after the last paragraph</li>
  </ul>
