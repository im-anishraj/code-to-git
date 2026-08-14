<h1 align="center">
  <img src="assets/octocode.png" alt="Leet to Git - Automatically sync your code to GitHub." width="400">
  <br>
  Leet to Git - Automatically sync your code to GitHub.
  <br>
  <br>
</h1>

<p align="center">
  <a href="https://github.com/im-anishraj/leet-to-git/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="license"/>
  </a>
</p>

## What is Leet to Git?
<p>A browser extension that automatically pushes your code to GitHub when you pass all tests on a <a href="https://leetcode.com/">Leetcode</a> problem. It's forked from LeetHub to be faster, cleaner and compatible with the new dynamic LeetCode UI.</p>

## Why Leet to Git?
<p> <strong>1.</strong> Recruiters <em>want</em> to see your contributions to the Open Source community, be it through side projects, solving algorithms/data-structures, or contributing to existing OS projects.<br>
As of now, GitHub is developers' #1 portfolio. Leet to Git makes it autonomous to keep track of progress and contributions on the largest network of engineering community, GitHub.</p>

<p> <strong>2.</strong> There's no easy way of accessing your leetcode problems in one place! <br>
Moreover, pushing code manually to GitHub from Leetcode is very time consuming. So, why not just automate it entirely without spending a SINGLE additional second on it? </p>

## How does Leet to Git work?     

<p>It's as simple as:</p>
<ol>
  <li>After installation, launch Leet to Git.</li>
  <li>Click on "authorize with GitHub" button to automatically set up your account.</li>
  <li>Setup an existing/new repository (private by default) by clicking "Get Started" button.</li>
  <li>Begin Leetcoding! To view your progress, simply click on the extension!</li>
</ol>


#### BONUS: Star [this repository](https://github.com/im-anishraj/leet-to-git) for further development of features. If you want a particular feature, simply [request](https://github.com/im-anishraj/leet-to-git/labels/feature) for it!

# Let's see you ACE that coding interview!

![leetcode view](assets/extension/leetcode.png)


# How to set up Leet to Git for local development?


  1. Fork this repo and clone to your local machine
  2. Run `npm run setup` to install the developer dependencies
  3. Run `npm run build` to build the final extension files into the `./dist/` directory
  4. Go to <a href="chrome://extensions">chrome://extensions </a> or <a href="about:debugging">about:debugging</a> in firefox
    a. In Chrome, enable [Developer mode](https://support.google.com/chrome/a/answer/2714278) by toggling the switch on top right corner
  6. Click `Load unpacked` or `Load Temporary Add-on...`
  7. Select the `./dist/chrome` or `./dist/firefox` folder
  8. That's it! Be sure to `npm run build` and reload the extension after making changes


Other npm commands available:

```
npm run               Show list of commands available
npm run format        Auto-format JavaScript, HTML/CSS
npm run format-test   Test all code is formatted properly
npm run lint          Lint JavaScript
npm run lint-test     Test all code is linted properly
```
