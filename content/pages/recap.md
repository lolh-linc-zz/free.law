Title: RECAP Project -- Turning PACER Around Since 2009
Slug: recap

<p class="lead">RECAP is an <a href="https://www.courtlistener.com/recap/">online archive</a> and free extension for <a href="https://addons.mozilla.org/en-US/firefox/addon/recap-195534/">Firefox</a> and <a href="https://chrome.google.com/webstore/detail/recap/oiillickanjlaeghobeeknbddaonmjnc">Chrome</a> that improves the experience of using PACER, the electronic public access system for the U.S. Federal District and Bankruptcy Courts.</p>

<div class="text-center">
<a href="https://chrome.google.com/webstore/detail/recap/oiillickanjlaeghobeeknbddaonmjnc" 
   class="btn btn-primary btn-lg"
   id="chrome-button">Add to Chrome&nbsp;<img src="{static}/images/icons/chrome.svg" height="35" width="35"></a>&nbsp;
<a href="https://addons.mozilla.org/en-US/firefox/addon/recap-195534/" 
   class="btn btn-primary btn-lg"
   id="firefox-button">Add to Firefox&nbsp;<img src="{static}/images/icons/firefox.svg" height="35" width="35"></a>
</div>
<br>


If you use PACER, install RECAP. Once installed, every docket or PDF you purchase on PACER will be added to the [RECAP Archive][archive]. Anything somebody else has added to the archive will be available to you for free — right in PACER itself.

<!-- PELICAN_END_SUMMARY -->

Tens of thousands of people have used RECAP. To join them, simply install it using the button above, and then use PACER as you normally would. It's that simple. If you don't like it, you can uninstall at any time. 

Have questions? [We're here to help][c].

<div class="text-center">
  <a href="/recap/screenshots/" class="btn btn-primary btn-lg">See Screenshots</a>
</div>


### The Archives and APIs

Thanks to our users and our [data consulting projects][data], the [RECAP Archive][archive] contains tens of millions of PACER documents, including [every free opinion in PACER][free]. Everything in the archive is fully searchable, including millions of pages that were originally scanned PDFs.

Everything that is in the RECAP Archive is also regularly uploaded to [the Internet Archive][ia-itself], where it has [a lasting home][ia]. This amounts to thousands of liberated documents daily.

Finally, we make the RECAP Archive available via an API or as bulk data for journalists, researchers, startups, and developers.

<div class="text-center">
<a href="https://www.courtlistener.com/recap/" class="btn btn-primary btn-lg">Visit the RECAP Archive</a>&nbsp;
<a href="https://www.courtlistener.com/api/" class="btn btn-primary btn-lg">Read about the RECAP APIs</a>
</div>
<br>


### What People are Saying

<blockquote>
  <p>Recap is an invaluable resource for journalists, activists - and really anyone who cares about law and justice in the United States. The work of the Free Law Project puts our courts within reach for everyone, and reinforces a pillar of democracy that is often overlooked. Everyone should support — and contribute — to this effort.</p>
  <footer>Charles Duhigg, <cite>Pulitzer Prize winning journalist for New York Times</cite></footer>
</blockquote>

<blockquote>
  <p>If you are a PACER user, I strongly encourage you to download RECAP.</p>
  <footer>Todd Ito of the <cite><a href="http://www.guardian.co.uk/technology/2009/nov/11/recap-us-courtrooms">Chicago Association of Law Libraries</a></cite></footer>
</blockquote>

<blockquote>
  <p>Citizens deserve open and easy access to all public court documents. Until public access becomes a matter of policy rather than blocked by PACER's artificial pay wall, independent efforts like RECAP continue to fill a critical gap in our ability to foster a more participatory and engaged democracy.</p>
  <footer>Ari Schwartz, <cite><a href="https://cdt.org">Center for Democracy and Technology</a></cite></footer>
</blockquote>

<p class="text-center"><a href="/recap/quotes/" class="btn btn-primary btn-lg">Read More Testimonials</a></p>
<br>




## History

<div class="right-image">
    <img src="{static}/images/recap/citp-logo-initials.png"
         alt="CITP Logo"
         class="img-responsive">
</div>

RECAP is a joint project of the [Center for Information Technology Policy][citp] at Princeton University and Free Law Project. It is one of several projects that harness the power of the web to increase government transparency.

RECAP is led by Free Law Project co-founders [Brian Carver][bcarver] and [Michael Lissner][ml]. RECAP was created by Harlan Yu, Steve Schultze, Timothy B. Lee, and [Ka-Ping Yee][yee] based on the principles described in [Government Data and the Invisible Hand][hand].

### For More Information, See&hellip;

 - [The Frequently Asked Questions][faq]
 - [Facts about PACER][pacer-faq]
 - [Why It Matters][wim]
 - [Details about RECAP's features][f]
 - [What People are Saying About RECAP][say]
 - [The RECAP Privacy Policy][privacy]

We also have an API and bulk data available for developers. For details, [get in touch][c].

<script type="text/javascript">
document.addEventListener("DOMContentLoaded", function(event) { 
  let isOpera = (!!window.opr && !!opr.addons) || !!window.opera || navigator.userAgent.indexOf(' OPR/') >= 0;
  let isFirefox = typeof InstallTrigger !== 'undefined';
  let isSafari = /constructor/i.test(window.HTMLElement) || (function (p) { return p.toString() === "[object SafariRemoteNotification]"; })(!window['safari'] || (typeof safari !== 'undefined' && safari.pushNotification));
  let isIE = /*@cc_on!@*/false || !!document.documentMode;
  let isEdge = !isIE && !!window.StyleMedia;
  let isChrome = !!window.chrome && (!!window.chrome.webstore || !!window.chrome.runtime);
  
  // Will need updating if we add more buttons
  if (isChrome) {
    $("#firefox-button").hide();
  } else if (isFirefox) {
    $("#chrome-button").hide();
  }
});
</script>

[faq]: {filename}/pages/recap/faq.md
[pacer-faq]: {filename}/pages/pacer-facts.md
[wim]: {filename}/why-it-matters.md
[f]: {filename}/pages/recap/features.md
[say]: {filename}/pages/recap/what-people-are-saying.md
[privacy]: {filename}/pages/recap/privacy.md
[c]: {filename}/pages/contact.md
[free]: {filename}/we-have-all-free-pacer.md
[bulk]: {filename}/pages/data-services.md
[archive]: https://www.courtlistener.com/recap/
[ia]: https://archive.org/details/usfederalcourts&tab=about
[ia-itself]: https://archive.org
[citp]: https://citp.princeton.edu/
[yee]: http://zesty.ca/
[bcarver]: http://www.ischool.berkeley.edu/people/faculty/briancarver
[ml]: http://michaeljaylissner.com/
[hand]: http://papers.ssrn.com/sol3/papers.cfm?abstract_id=1138083
[data]: {filename}/pages/data-services.md
