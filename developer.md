


---


Developer Guide
===================

---

- <a target="_blank" href="https://api.iinbrand.com/scan/">**Scan**</a>

<div class="devices">
    <div class="device device-ios">
        <iframe src="https://api.iinbrand.com/scan/" scrolling="no" frameborder="0"></iframe>
    </div>
</div>

---



- <a target="_blank" href="https://api.iinbrand.com/genkeys">**Gen keys**</a>


- <a target="_blank" href="https://iinbrand.com/mockup">**Mockup**</a>

- <a target="_blank" href="https://iinb.ga/dbox">**Design**</a>
    - <a target="_blank" href="https://github.com/iinbrand/artwork">**Other Artwork**</a>

- <a target="_blank" href="http://ios.iinbrand.com">**Info & Help page**</a>

---

**Request POST URL**


- <a target="_blank"> *https://api.iinbrand.com/service/* </a>  (both slash and non-trailing-slash)
 
```json
{
	"keys" : "XXXX-XXXX-XXXX-XXXX",
	"location" : "00.000000,00.000000",
	"secret" : "101946110ac0176b229582f27c98e23f"
}
```


**Respond JSON**

```json
{
	"product" : "Name Product",
	"detail" : "Detail of product",
	"pic" : "url link to picture",
	"keys" : "XXXX-XXXX-XXXX-XXXX",
	"valid" : "Y",
	"chknum" : "3",
	"chklast" : "01 Jan 2015 00:00",
	"product_url" : "https://api.iinbrand.com/product/{product}"
}
```



---


<div id="disqus_thread"></div>
<script>
/**
* RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
* LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables
*/
/*
var disqus_config = function () {
this.page.url = PAGE_URL; // Replace PAGE_URL with your page's canonical URL variable
this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
};
*/
(function() { // DON'T EDIT BELOW THIS LINE
var d = document, s = d.createElement('script');
s.src = '//iinbrand.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>
Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript" rel="nofollow">
comments powered by Disqus.</a>
</noscript><script id="dsq-count-scr" src="//iinbrand.disqus.com/count.js" async></script>
