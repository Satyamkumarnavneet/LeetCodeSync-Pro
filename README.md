
# LLeetCodeSync Pro - Sync your LeetCode Solutions with GitHub

<p align="center">
  <a href="https://github.com/raphaelheinz/LeetHub-3.0/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="license"/>
  </a>
  <a href="https://chromewebstore.google.com/u/1/detail/leethub-v3/kdkgpjpenaeoodajljkflmlnkoihkmda">
    <img src="https://img.shields.io/chrome-web-store/v/kdkgpjpenaeoodajljkflmlnkoihkmda.svg" alt="chrome-webstore"/>
  </a>
  <a href="https://chromewebstore.google.com/u/1/detail/leethub-v3/kdkgpjpenaeoodajljkflmlnkoihkmda">
    <img src="https://img.shields.io/chrome-web-store/d/kdkgpjpenaeoodajljkflmlnkoihkmda.svg" alt="users">
  </a>
  <a href="https://github.com/raphaelheinz/LeetHub-3.0/graphs/contributors" alt="Contributors">
    <img src="https://img.shields.io/github/contributors/raphaelheinz/LeetHub-3.0" />
  </a>
</p>
<h1 align="center">
    <img src="assets/octocode.png" alt="LeetHub v3" width="400">
</h1>


## What is LeetHub-3.0?

LeetCodeSync Pro is a powerful tool that automates the synchronization of your LeetCode coding solutions with GitHub repositories. Say goodbye to manual syncing and hello to more time for coding and innovation. Forked from a renowned predecessor, LeetCodeSync Pro is designed to streamline your coding workflow.


## Why LeetCodeSync Pro?

Tired of juggling between LeetCode and GitHub to manage your coding solutions? LeetCodeSync Pro provides a seamless solution by automatically pushing your code to GitHub when you pass all tests on a LeetCode problem. Spend more time solving problems and less time on manual tasks.

## Screenshot

<h1 align="center">
    <img src="assets/extension/4.png" alt="leetcode view" width="800">
</h1>

## Supported UI

LeetCodeSync Pro is compatible with two different LeetCode UIs. For the best experience, we recommend using the following:

1. **old layout** or
2. new **"dynamic layout"**

## Installation

<div align="center">
    <a href="https://chromewebstore.google.com/u/1/detail/leethub-v3/kdkgpjpenaeoodajljkflmlnkoihkmda" rel="Download leetcode plugin">
        <img src="https://embedsignage.com/wp-content/uploads/2016/04/embed-signage-chromeos-web-store-button.png" alt="Download leetcode plugin" width="300" />
    </a>
</div>

1. **Chrome Web Store**

    Install this plugin using Chrome Web Store. Please find the link above. This is the preferred way of installation. Updates are installed automatically.


2. **(Optional) Manual installation**

    You can also install the plugin manually. Please follow the steps below.

    * Create your own OAuth app in GitHub (https://github.com/settings/applications/new) and store CLIENT_ID and CLIENT_SECRET confidentially
        * Application name: [CUSTOM]
        * Homepage URL: https://github.com/Satyamkumarnavneet/LeetCodeSync-Pro
        * Authorization callback URL: https://github.com/
    * Download the project ZIP (<a href="https://github.com/raphaelheinz/LeetHub-3.0/releases">Releases</a>) or clone this repository
    * Run ```npm run setup``` to install the developer dependencies
    * Update CLIENT_ID and CLIENT_SECRET in ```scripts/authorize.js``` and ```scripts/oauth2.js``` with your ids
    * Go to <a href="chrome://extensions">chrome://extensions</a>
    * Enable <a href="https://www.mstoic.com/enable-developer-mode-in-chrome/">Developer mode</a> by toggling the switch on top right corner
    * Click **"Load unpacked"**
    * Select the entire LeetHub folder


## Setup

1. After installing the LeetHub, launch the plugin
2. Click on **"Authorize with GitHub"** to set up your account with LeetHub
3. Setup an existing/new repository with LeetHub (private by default) by clicking **"Get Started"**
4. Begin Leetcoding! To view your progress, simply click on the extension!


## Supported npm commands

```bash
npm run               # Show available commands
npm run setup         # Install dependencies
npm run format        # Auto-format JavaScript, HTML/CSS
npm run format-test   # Test if code is formatted properly
npm run lint          # Lint JavaScript
npm run lint-test     # Test if code is linted properly
```

## Contribution

Please help to further improve this awesome plugin! We would appreciate your support. Your pull requests are welcome!

Don't forget to star this repository for further development of new features. If you want a particular feature, simply [request](https://github.com/raphaelheinz/LeetHub-3.0/labels/feature) for it!

