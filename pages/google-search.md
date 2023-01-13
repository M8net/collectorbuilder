---
title: Google CSE
layout: page
permalink: /search/google.html
# optional Google search page, see docs/google.md
# set google-cse-id in _config.yml
---

## Ricerca Google nel Sito

<div class="alert alert-primary" role="alert">
  Avvertenza: CSE è un servizio gratuito messo a disposizione da. I risultati dipendono dall'indicizzazione del fornitore e possono contenere pubblicità.
</div>

<script>
  (function() {
    var cx = '{{ site.google-cse-id }}';
    var gcse = document.createElement('script');
    gcse.type = 'text/javascript';
    gcse.async = true;
    gcse.src = 'https://cse.google.com/cse.js?cx=' + cx;
    var s = document.getElementsByTagName('script')[0];
    s.parentNode.insertBefore(gcse, s);
  })();
</script>
<gcse:search></gcse:search>
