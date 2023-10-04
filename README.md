<!DOCTYPE html>
<!-- saved from url=(0033)http://127.0.0.1:5500/haroon.html -->
<html lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
  
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
 <title>Simple Website Design</title>
 <link rel="stylesheet" href="./Simple Website Design_files/haroon.css">
  <!---Custom Css File!--->

</head>
<body cz-shortcut-listen="true">
    <div class="container">
      <nav>
        <div class="logo">
          <a href="http://127.0.0.1:5500/haroon.html#">Graphic designer<span>Haroon</span></a>
        </div>
        <ul>
          <li><a href="http://127.0.0.1:5500/haroon.html#">Home</a></li>
          <li><a href="http://127.0.0.1:5500/haroon.html#">About</a></li>
          <li><a href="http://127.0.0.1:5500/haroon.html#">Services</a></li>
          <li><a href="http://127.0.0.1:5500/haroon.html#">Contact</a></li>
        </ul>
        <div class="buttons">
          <a href="http://127.0.0.1:5500/haroon.html#" class="login">Log in</a>
          <a href="http://127.0.0.1:5500/haroon.html#" class="btn">Register</a>
        </div>
      </nav>
      <h1>the main content</h1>
      <div class="content">
        <h2>Hello,<br>I am a professional graphic designer</h2>
        
        <p>Mydesign Service Includes:
  
          Flyer
            Bi-Fold Brochure <br>
           Tri-Fold Brochure <br>
            A4, A5 Brochure <br>
            Multi-page Brochure/Magazine <br>
            Company Profile <br>
            Business Proposal <br>
            Annual Report navbar-brand <br>
            Flyer <br>
            Booklet <br>
            Magazine <br>
            Proposal <br>
            Handbook, coursebook, guidebook, policy, and notebook (Custom Price) </p>
        
        
      </div>
      <div class="link">
        <a href="http://127.0.0.1:5500/haroon.html#" class="hire">Hire Me</a>
      </div>
    </div>
  <!-- Code injected by live-server -->
<script>
	// <![CDATA[  <-- For SVG support
	if ('WebSocket' in window) {
		(function () {
			function refreshCSS() {
				var sheets = [].slice.call(document.getElementsByTagName("link"));
				var head = document.getElementsByTagName("head")[0];
				for (var i = 0; i < sheets.length; ++i) {
					var elem = sheets[i];
					var parent = elem.parentElement || head;
					parent.removeChild(elem);
					var rel = elem.rel;
					if (elem.href && typeof rel != "string" || rel.length == 0 || rel.toLowerCase() == "stylesheet") {
						var url = elem.href.replace(/(&|\?)_cacheOverride=\d+/, '');
						elem.href = url + (url.indexOf('?') >= 0 ? '&' : '?') + '_cacheOverride=' + (new Date().valueOf());
					}
					parent.appendChild(elem);
				}
			}
			var protocol = window.location.protocol === 'http:' ? 'ws://' : 'wss://';
			var address = protocol + window.location.host + window.location.pathname + '/ws';
			var socket = new WebSocket(address);
			socket.onmessage = function (msg) {
				if (msg.data == 'reload') window.location.reload();
				else if (msg.data == 'refreshcss') refreshCSS();
			};
			if (sessionStorage && !sessionStorage.getItem('IsThisFirstTime_Log_From_LiveServer')) {
				console.log('Live reload enabled.');
				sessionStorage.setItem('IsThisFirstTime_Log_From_LiveServer', true);
			}
		})();
	}
	else {
		console.error('Upgrade your browser. This Browser is NOT supported WebSocket for Live-Reloading.');
	}
	// ]]>
</script>
<basefont> 
<script>
</script>
  </body></html>
