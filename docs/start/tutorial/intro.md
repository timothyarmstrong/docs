---
layout: default
type: start
navgroup: docs
shortname: Start
title: Getting Started
subtitle: Your first Polymer application 
---

<style>
#download-button {
  background: #4285f4;
  color: #fff;
  font-size: 18px;
  fill: #fff;
}
#download-button:hover {
  background: #2a56c6;
}
#download-button::shadow #ripple {
  color: #fff;
}
.unquote-link {
  max-width: 400px;
}
.unquote-image {
  background-image: url(/images/unquote.png);
  background-size: cover;
  background-position: top;
  width: 400px;
  height: 320px;
  border: 1px solid black;
}
</style>


In this tutorial, you'll build a small {{site.project_title}} application -- a very basic client for a social networking service. The end result will look like this:

<div layout horizontal center-justified>
  <a href="/samples/tutorial/finished/index.html" layout horizontal flex class="unquote-link">
    <div class="unquote-image" flex></div>
  </a>
</div>

This project will introduce you to most of the key concepts in working with {{site.project_title}}. Don't worry if you don't understand everything. Each of the concepts presented here is described in detail in the {{site.project_title}} documentation.

## Before you start: getting the sample project

To get started, download the starter project. This starter project includes all of the {{site.project_title}} libraries and dependencies you'll need to get started.

<p layout horizontal center-justified>
  <a href="https://github.com/Polymer/polymer-tutorial/archive/master.zip">
    <paper-button icon="file-download" id="download-button" raisedButton label="Download Starter Project" onclick="downloadStarter()"></paper-button>
  </a>
</p>

Unzip the starter project somewhere on your local drive. 

The starter includes an initial version of the project you'll be working with. If you run into trouble, it also includes incremental versions of the project so you can check your work along the way. 

While you're working, you'll need a basic HTTP server to serve your pages. If you have Python installed, you can run the following command in the top level of the starter project:

    python -m SimpleHTTPServer 

Or with python 3 :

    python -m http.server

Open a browser and navigate to the local server. For `SimpleHTTPServer`, this is typically:

-  [http://localhost:8000/](http://localhost:8000/)

### Next

<a href="/docs/start/tutorial/step-1.html">
  <paper-button icon="arrow-forward" label="Step 1: Creating the app structure" raisedButton></paper-button>
</a>

