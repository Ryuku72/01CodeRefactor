# HomeworkW1
<H1>Horiseon Assignment</H1> 
<H2>Aim</H2>
<P> Take the existing Html and CSS project files provided in the WAUS-CRAW-FSF-PT-02-2020-U-C-MW / Week1 / Day1 / Homework repository on GitLab and refractor it to meet a set of goals set by the Week 1 Homework Assignment. For extra flare, show addition understanding of principals discussed in Week 1 through application.</P>
<br>
<H2> Expectations aka Web Accessibility</H2>
  <ul>
  <li>Sematic and Sequential Order of Elements (HTML and CSS)</li>
  <li>Logical structure independent of style </li>
  <li>Utilizing 'Alt' attribute</li>
  <li>Concise title</li>
  <li>Fix links</li>
  <li>Clean up the code</li>
</ul>
<H2>Key concepts and tools from Week 1</H2>
  <ul> 
  <li>Html Syntax </li>
  <li>Css Syntax </li>
  <li> Floats </li>
  <li>Positioning </li>
  <li> Box Models </li>
  </ul>
<br>
<H2>Meeting Expectations </h2>
<H3>Sematic and Sequential Order of Elements (HTML & CSS)</H3>
<p> In the HTML There was a heavy use of Div throughout the code sequence. This was converted to a more semantic structure sequence of Header, figure, section, aside and footer. The 'Hero' img element was moved between line 32 - 34 for clear sequence order of elements. Added addition notes between each root elements for clarity.</p>
<p>In the CSS all changes to the div's were translated to the cascading style sheet (header, figure, section, aside, footer). Notes were applied to clarify each root element. Hero class was moved further up the css to reflect the order of the corresponding html index.</p>
<H3>Logical Structure independent of style</h3>
<p>Only major change to the html structure is the 'Hero' img element. Turning off the stylesheet will flow in the correct order of header, figure, section, aside and footer. Additional note, Image sizes are extremely large without style restrictions. A large clean up to the aside section result in a large number of classes being either merged or deleted. This was the same as the Section element but was not as heavy handed</p>
<H3>ALT element</H3>
<p> Alt elements was added to every img src attribute in the html. Larger pictures were given a discription which icons were simply named after the icons they represent </p>
<H3>Concise Title</H3>
<p>Title was changed in the html to 'Horiseon | Social Solutions' in reflection to the footer '2019 Horiseon Social Solution Services, Inc.'</p> 
<H3>Fix Links</H3>
<P>The link for '#search-engine-optimization' in the html did not work as the corresponding ID did not exist. This was inserted on line 40.</p>
