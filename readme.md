<h1>Accessibility Toolbar Plugin</h1>
<p><img src="https://raw.githubusercontent.com/mickidum/acc_toolbar/master/poster.jpg" alt="Accessibility Toolbar Plugin Poster"></p>

<p>Accessibility Toolbar Plugin is a simple accessibility component without dependencies (clean javascript), including a variety of tools. This component allows users with disabilities easy and convenient way to browse most websites.</p>

<h2>Website Accessibility Plugin</h2>
<p>We help you to make your website more accessible for people with disabilities - while also complying with legal requirements.<br>
25Space offers this plugin as a hosting solution including setup on your website.<br>
<a href="https://25space.com/business/accessibility/">Learn more about >><a></p>


<h2>About accessibility</h2>
<p>Accessible websites are websites that can be used by all users without restrictions (barrier-free), regardless of their limitations or technical capabilities.
The accessibility of websites is still not a matter of course: according to a <a href="https://www.aktion-mensch.de/inklusion/barrierefreiheit/barrierefreie-website/test-barrierefreie-webshops" target="_blank">study by Google and "Aktion Mensch" (DE)</a>, for example, two thirds of large German online shops 
are not accessible. Barriers on the internet prevent a website from being accessible to everyone. Only through digital accessibility can all people use a website without restrictions.<br>
An accessible website is worthwhile for all companies, because: According to the Federal Statistical Office, 7.8 million people in Germany live with a recognised severe disability (as of the end of 2021). If you make your website accessible, you will also reach more potential customers. 
What's more, accessibility doesn't just benefit people with disabilities, as accessibility makes websites easier to use and therefore more satisfying for all users.<br></p>


<h2>About the legal regulations</h2>
<p>From 28 June 2025, most B2C websites, services and products must be accessible as part of the Accessibility Reinforcement Act, Barrierefreiheitsstärkungsgesetz (BFSG).
<a target="_blank" href="https://www.barrierefreiheit-dienstekonsolidierung.bund.de/Webs/PB/DE/gesetze-und-richtlinien/barrierefreiheitsstaerkungsgesetz/barrierefreiheitsstaerkungsgesetz-node.html">More on bund.de (DE)</a><br></p>

<h2>How to use Accessibility Toolbar</h2>

	<h4>Option 1 - By 25Space.com</h4>
	<a href="https://25space.com/business/accessibility/">Learn more about >><a></p>

	<h4>Option 2 - Modified by 25Space.com</h4>
	<a href="https://25space.com/business/accessibility/">Learn more about >><a></p>




<p>Add this script to your website</p>








<pre class="highlight">
<code>
&lt;script src=&quot;https://cdn.jsdelivr.net/gh/mickidum/acc_toolbar/acctoolbar/acctoolbar.min.js&quot;&gt;&lt;/script&gt;
&lt;script&gt;
// optional init
  window.onload = function() {
    window.micAccessTool = new MicAccessTool({
      link: 'http://your-awesome-website.com/your-accessibility-declaration.pdf',
      contact: 'mailto:your-mail@your-awesome-website.com',
      buttonPosition: 'right', // default is 'left'
      forceLang: 'ru-RU' // default is 'en' may be 'he-IL', 'ru-RU', or 'fr_FR'
    });
  }
&lt;/script&gt;
</code>
</pre>

<h4>Download</h4>

<ol>
	<li><a href="https://raw.githubusercontent.com/mickidum/acc_toolbar/master/acctoolbar/acctoolbar.min.js">Download(Right click and save)</a> <strong>Accessibility Toolbar Plugin</strong></li>
	<li>Store this file in your website directory (i.e. /public_html)</li>
	<li>
		<p>Add script to website</p>
<pre class="highlight">
<code>
&lt;script src=&quot;path/to/script/where/stored/acctoolbar.min.js&quot;&gt;&lt;/script&gt;
// optional init
&lt;script&gt;
  window.onload = function() {
    window.micAccessTool = new MicAccessTool({
      link: 'http://your-awesome-website.com/your-accessibility-declaration.pdf',
      contact: 'mailto:your-mail@your-awesome-website.com',
      buttonPosition: 'right', // default is 'left'
      forceLang: 'ru-RU' // default is 'en' may be 'he-IL', 'ru-RU', or 'fr_FR'
    });
  }
&lt;/script&gt;
</code>
</pre>
	</li>
	<li>That's all</li>
</ol>

<h2>For Developers</h2>

<ol>
	<li>Clone or download this <a href="{{ site.github.repository_url }}">repo</a></li>
	<li>Install <strong>gulp.js</strong> - write in terminal <em>"npm install gulp -g"</em></li>
	<li><em>cd [installed repo folder]</em></li>
	<li>Write in terminal - <em>"npm install"</em></li>
	<li>Write in terminal - <em>"gulp"</em> to run app</li>
	<li>Now you can change it.</li>
</ol>
