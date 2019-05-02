# Quire.io MathJax
MathJax for Quire.io.

Displaying LaTeX equations in Quire.io.

1. Copy this code into your clipboard:
```javascript
javascript:(function(){if(window.MathJax===undefined){var script=document.createElement("script");script.type="text/javascript";script.src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/MathJax.js?config=TeX-AMS_HTML";var config='MathJax.Ajax.config.path["mhchem"]="https://cdnjs.cloudflare.com/ajax/libs/mathjax-mhchem/3.2.0";MathJax.Hub.Config({extensions: ["tex2jax.js"],tex2jax:{inlineMath:[["$","$"],["\\\\\\\\\\\\(","\\\\\\\\\\\\)"]],displayMath:[["$$","$$"],["\\\\[","\\\\]"]],processEscapes:true},TeX:{extensions:["[mhchem]/mhchem.js","cancel.js"]},jax:["input/TeX","output/HTML-CSS"]});MathJax.Hub.Startup.onload();';if(window.opera){script.innerHTML=config}else{script.text=config}document.getElementsByTagName("head")[0].appendChild(script);window.setInterval(function(){MathJax.Hub.Queue(["Typeset",MathJax.Hub]);},1000);}else{MathJax.Hub.Queue(["Typeset",MathJax.Hub]);}})();
```

2. Create a **bookmark** (Chrome: Menu > Bookmarks > Bookmark manager > Add new bookmarks) and name it as you want.

3. Open Quire.io and click on the **bookmark**.

4. Enjoy your Quire.io with Latex.