---
comments: false
published: true
title: Logo contest
---
Please leave your vote for the logo you like the most.

<style>
.loggos {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-flex-flow: row wrap;
    -ms-flex-flow: row wrap;
    flex-flow: row wrap;
    counter-reset: loggo;
}
.loggo {
	z-index: 1;
	position: relative;
	-webkit-box-flex: 1;
	-webkit-flex: 1 0 16rem;
	    -ms-flex: 1 0 16rem;
	        flex: 1 0 16rem;
	line-height: 16rem;
    text-align: center;
	height: 16rem;
	text-decoration: none;
	color: black;
}
.loggo:after {
    counter-increment: loggo;
    content: counter(loggo);
    font-size: 1rem;
    position: absolute;
    bottom: 0;
    right: 0;
    line-height: 1;
    font-family: "PT Sans", sans-serif;
}
.loggo img {
	max-height: 7rem;
    max-width: 13rem;
}
.loggo p {
    margin: 0;
}
</style>

<section class="loggos">
<div id="loggo-1" class="loggo">![1.png]({{site.baseurl}}/img/1.png)
</div>
<div id="loggo-2" class="loggo">![2.png]({{site.baseurl}}/img/2.png)
</div>
<div id="loggo-3" class="loggo">![spee.png]({{site.baseurl}}/img/spee.png)
</div>
<div id="loggo-4" class="loggo">![spee2.png]({{site.baseurl}}/img/spee2.png)
</div>
<div id="loggo-5" class="loggo">![spee3.png]({{site.baseurl}}/img/spee3.png)
</div>
<div id="loggo-6" class="loggo">![spee4.png]({{site.baseurl}}/img/spee4.png)
</div>
<div id="loggo-7" class="loggo">![v6.png]({{site.baseurl}}/img/v6.png)
</div>
<div id="loggo-8" class="loggo"></div>
<div id="loggo-8" class="loggo"></div>
<div id="loggo-8" class="loggo"></div>
</section>
