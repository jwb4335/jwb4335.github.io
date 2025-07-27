---
layout: archive
title:  "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

{% capture pdf_url %}{{ site.baseurl }}/files/vitae/CV John Barry.pdf{% endcapture %}

<!-- ---------- fallback link (always visible) ---------------------------- -->
<p>
  <a href="{{ pdf_url }}" target="_blank" rel="noopener noreferrer">
    ► Open CV as PDF
  </a>
</p>

<!-- ---------- responsive inline viewer (hidden on very small screens) --- -->
<div class="pdf-wrapper">
  <object data="{{ pdf_url }}" type="application/pdf" width="100%" height="100%">
    <p>
      Couldn’t display the PDF.  
      <a href="{{ pdf_url }}">Download instead.</a>
    </p>
  </object>
</div>
