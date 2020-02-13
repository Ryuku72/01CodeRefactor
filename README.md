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
  <li>Bonus: Make things pretty</li>
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
<p> In the HTML There was a heavy use of Div throughout the code sequence. This was converted to a more semantic structure sequence of Header, figure, section, aside and footer. </p>
<p>In the CSS all changes to the div's were translated to the cascading style sheet (header, figure, section, aside, footer)</p>
<H3>Logical Structure independent of style</h3>
<p>Order changed from Header Aside Content Figure Footer to Header Figure Content Aside Footer.</p>
<H3>ALT element</H3>
<p> Alt elements was added to every img src attribute in the html. Larger pictures were given a discription which icons were simply named after the icons they represent </p>
<H3>Concise Title</H3>
<p>Title was changed in the html from 'webpage' to 'Horiseon | Social Solutions' to reflect the footer '2019 Horiseon Social Solution Services, Inc.'</p> 
<H3>Fix Links</H3>
<P>In the HTML the link for '#search-engine-optimization' within the header did not work as the corresponding ID did not exist. This was inserted on line 40.</p>
<h3>Clean up the Code</h3>
<p>For the HTML I first removed the Div from the header on line 13 and line 25 of the original. This div served the same functon as the associated header class.</p>
<p>For the CSS the obvious changes to the element structure needed to be implemented (header, figure, content, aside, footer) and the corresponding tags needed to be altered. However, some tags, e.g. .header div ul were shortened to header ul, whilst others were deleted completely and merged into new class tags. This is evident in both the content and aside root elements.</p>
<p> For contrast the original Content Root Element (aka benifit) had 10 tags and now has 4, Aside (search-engine etc) had 9 tags and now has 7. </p>
<H3>Bonus</H3>
<P>Whilst HTML and CSS syntax has already been covered, the design tools learnt in week 1 (floats, positioning and box models) can be found heavily experiemented on in my CSS. Examples of floats can be found in the content images and assigning relative and absolutes position properties. I tried implementing the same 'relative' and 'absolute' relationship to the 'hero' image but failed. I did however 'fixed' position the footer. Position of the entire page has been edited to make it more lean and relative via manipulating the box models.
<br>
<H2>Contributor</h2>
<p>Joshua K Bader</p>