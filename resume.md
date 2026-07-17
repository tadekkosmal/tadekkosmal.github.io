---
title: "cv"
permalink: /resume/
layout: single
---

<div class="cv-actions">
  <a class="button" href="{{ site.resume_pdf | relative_url }}" target="_blank" rel="noopener">Open PDF</a>
  <a class="text-link" href="{{ site.resume_pdf | relative_url }}" download>Download CV ↓</a>
</div>

<div class="pdf-frame">
  <iframe src="{{ site.resume_pdf | relative_url }}#view=FitH" title="Tadek Kosmal CV"></iframe>
</div>

<p class="small-note">If the preview is empty, update <code>resume_pdf</code> in <code>_config.yml</code> to match the PDF path in your repository.</p>
