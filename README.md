<p><strong>jQuery</strong>&nbsp;is a&nbsp;<a title="JavaScript library" href="https://en.wikipedia.org/wiki/JavaScript_library">JavaScript library</a>&nbsp;designed to simplify&nbsp;<a title="HTML" href="https://en.wikipedia.org/wiki/HTML">HTML</a>&nbsp;<a title="Document Object Model" href="https://en.wikipedia.org/wiki/Document_Object_Model">DOM</a>&nbsp;tree traversal and manipulation, as well as&nbsp;<a class="mw-redirect" title="Event handling" href="https://en.wikipedia.org/wiki/Event_handling">event handling</a>,&nbsp;<a class="mw-redirect" title="CSS animation" href="https://en.wikipedia.org/wiki/CSS_animation">CSS animation</a>, and&nbsp;<a title="Ajax (programming)" href="https://en.wikipedia.org/wiki/Ajax_(programming)">Ajax</a>.&nbsp;It is&nbsp;<a class="mw-redirect" title="Free and open source software" href="https://en.wikipedia.org/wiki/Free_and_open_source_software">free, open-source software</a>&nbsp;using the permissive&nbsp;<a title="MIT License" href="https://en.wikipedia.org/wiki/MIT_License">MIT License</a>.&nbsp;As of May 2019, jQuery is used by 73% of the 10 million most popular websites.&nbsp;<a title="World Wide Web" href="https://en.wikipedia.org/wiki/World_Wide_Web">Web</a>&nbsp;analysis indicates that it is the most widely deployed JavaScript library by a large margin, having 3 to 4 times more usage than any other JavaScript library.</p>
<p>jQuery's syntax is designed to make it easier to navigate a document, select&nbsp;<a title="Document Object Model" href="https://en.wikipedia.org/wiki/Document_Object_Model">DOM</a>&nbsp;elements, create&nbsp;<a title="Animation" href="https://en.wikipedia.org/wiki/Animation">animations</a>, handle&nbsp;<a title="Event (computing)" href="https://en.wikipedia.org/wiki/Event_(computing)">events</a>, and develop&nbsp;<a title="Ajax (programming)" href="https://en.wikipedia.org/wiki/Ajax_(programming)">Ajax</a>&nbsp;applications. jQuery also provides capabilities for developers to create&nbsp;<a title="Plug-in (computing)" href="https://en.wikipedia.org/wiki/Plug-in_(computing)">plug-ins</a>&nbsp;on top of the JavaScript library. This enables developers to create&nbsp;<a title="Abstraction (computer science)" href="https://en.wikipedia.org/wiki/Abstraction_(computer_science)">abstractions</a>&nbsp;for low-level interaction and animation, advanced effects and high-level, themeable widgets. The modular approach to the jQuery library allows the creation of powerful&nbsp;<a title="Dynamic web page" href="https://en.wikipedia.org/wiki/Dynamic_web_page">dynamic web pages</a>&nbsp;and Web applications.</p>
<p>The set of&nbsp;<a href="https://en.wikipedia.org/wiki/JQuery#Features">jQuery core features</a>&mdash;DOM element selections, traversal and manipulation&mdash;enabled by its&nbsp;<em>selector engine</em>&nbsp;(named "Sizzle" from v1.3), created a new "programming style", fusing algorithms and DOM data structures. This style influenced the architecture of other&nbsp;<a title="Comparison of JavaScript frameworks" href="https://en.wikipedia.org/wiki/Comparison_of_JavaScript_frameworks">JavaScript frameworks</a>&nbsp;like&nbsp;<a title="YUI Library" href="https://en.wikipedia.org/wiki/YUI_Library">YUI v3</a>&nbsp;and&nbsp;<a title="Dojo Toolkit" href="https://en.wikipedia.org/wiki/Dojo_Toolkit">Dojo</a>, later stimulating the creation of the standard&nbsp;<em>Selectors API</em>.&nbsp;Later, this style has been enhanced with a deeper algorithm-data fusion in an heir of jQuery, the&nbsp;<a title="D3.js" href="https://en.wikipedia.org/wiki/D3.js">D3.js</a>&nbsp;framework.</p>
<p><a title="Microsoft" href="https://en.wikipedia.org/wiki/Microsoft">Microsoft</a>&nbsp;and&nbsp;<a title="Nokia" href="https://en.wikipedia.org/wiki/Nokia">Nokia</a>&nbsp;bundle jQuery on their platforms.&nbsp;Microsoft includes it with&nbsp;<a title="Microsoft Visual Studio" href="https://en.wikipedia.org/wiki/Microsoft_Visual_Studio">Visual Studio</a>&nbsp;for use within Microsoft's&nbsp;<a title="ASP.NET AJAX" href="https://en.wikipedia.org/wiki/ASP.NET_AJAX">ASP.NET AJAX</a>&nbsp;and&nbsp;<a title="ASP.NET MVC" href="https://en.wikipedia.org/wiki/ASP.NET_MVC">ASP.NET MVC</a>&nbsp;frameworks while Nokia has integrated it into the Web Run-Time widget development platform.</p>

</br>

<div class="toctitle" dir="ltr" lang="en">
<h2 id="mw-toc-heading">Contents</h2>
<label class="toctogglelabel" for="toctogglecheckbox"></label></div>
<ul>
<li class="toclevel-1 tocsection-1"><a href="#Overview"><span class="toctext">Overview</span></a></li>
<li class="toclevel-1 tocsection-2"><a href="#History"><span class="toctext">History</span></a>
<ul>
<li class="toclevel-2 tocsection-3"><a href="#Popularity"><span class="toctext">Popularity</span></a></li>
</ul>
</li>
<li class="toclevel-1 tocsection-4"><a href="#Features"><span class="toctext">Features</span></a>
<ul>
<li class="toclevel-2 tocsection-5"><a href="#Browser_support"><span class="toctext">Browser support</span></a></li>
</ul>
</li>
<li class="toclevel-1 tocsection-6"><a href="#Distribution"><span class="toctext">Distribution</span></a></li>
<li class="toclevel-1 tocsection-7"><a href="#Interface"><span class="toctext">Interface</span></a>
<ul>
<li class="toclevel-2 tocsection-8"><a href="#Functions"><span class="toctext">Functions</span></a>
<ul>
<li class="toclevel-3 tocsection-9"><a href="#jQuery_methods"><span class="toctext">jQuery methods</span></a></li>
<li class="toclevel-3 tocsection-10"><a href="#Static_utilities"><span class="toctext">Static utilities</span></a></li>
</ul>
</li>
<li class="toclevel-2 tocsection-11"><a href="#No-conflict_mode"><span class="toctext">No-conflict mode</span></a></li>
<li class="toclevel-2 tocsection-12"><a href="#Typical_start-point"><span class="toctext">Typical start-point</span></a></li>
<li class="toclevel-2 tocsection-13"><a href="#Chaining"><span class="toctext">Chaining</span></a></li>
<li class="toclevel-2 tocsection-14"><a href="#Creating_new_DOM_elements"><span class="toctext">Creating new DOM elements</span></a></li>
<li class="toclevel-2 tocsection-15"><a href="#Ajax"><span class="toctext">Ajax</span></a></li>
</ul>
</li>
<li class="toclevel-1 tocsection-16"><a href="#jQuery_plug-ins"><span class="toctext">jQuery plug-ins</span></a></li>
<li class="toclevel-1 tocsection-17"><a href="#Release_history"><span class="toctext">Release history</span></a></li>
<li class="toclevel-1 tocsection-18"><a href="#Testing_framework"><span class="toctext">Testing framework</span></a></li>
</ul>

</br>





