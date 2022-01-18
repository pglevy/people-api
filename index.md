---
layout: index
title: Home
---
# No-Code API with GitHub Pages

A template for creating a read-only API from a CSV file and hosting it on GitHub Pages
{: .f2}

## How it works

1. Create a copy of this repo template.
2. Replace `mydata.csv` with your data.
3. Publish to GitHub Pages.

Your data is published as a JSON file that you can use to pull content into your apps and design tools.

**To use this template and get more details on how to set it up, see the [README](https://github.com/githubfornocoders/nocode-api-github-pages#readme).**

<div class="d-flex mt-6">
<button id="copy" data-clipboard-text="{{ site.url }}{{ site.baseurl }}/api.json" class="btn-mktg btn-large-mktg mr-3">Copy link to clipboard</button>
<a href="{{ site.url }}{{ site.baseurl }}/api.json" class="btn-mktg btn-muted-mktg btn-large-mktg" target="_blank">Open link</a>
</div>

<div role="alert" id="feedback-success" class="p-1" style="display:none;">
  <div class="Toast Toast--success">
    <span class="Toast-icon">
      <!-- <%= octicon "check" %> -->
      <svg width="12" height="16" viewBox="0 0 12 16" class="octicon octicon-check" aria-hidden="true">
        <path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z" />
      </svg>
    </span>
    <span class="Toast-content">Link copied!</span>
  </div>
</div>

<div role="alert" id="feedback-error" class="p-1" style="display:none;">
  <div class="Toast Toast--error">
    <span class="Toast-icon">
      <!-- <%= octicon "stop" %> -->
      <svg width="14" height="16" viewBox="0 0 14 16" class="octicon octicon-stop" aria-hidden="true">
        <path
          fill-rule="evenodd"
          d="M10 1H4L0 5v6l4 4h6l4-4V5l-4-4zm3 9.5L9.5 14h-5L1 10.5v-5L4.5 2h5L13 5.5v5zM6 4h2v5H6V4zm0 6h2v2H6v-2z"
        />
      </svg>
    </span>
    <span class="Toast-content">Something went wrong. ☹️ Please refresh the page and try again.</span>
  </div>
</div>
