# ChatGPT Prompts for Bug Bounty 🧠

A list of ChatGPT Prompts for Web Application Security, Bug Bounty, and Pentesting.

[![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/TakSec.svg?style=social&label=Follow%20%40TakSec)](https://twitter.com/TakSec)
</p>

---

# Faster Hunting and Reporting

## Brainstorm

> As a bug bounty hunter, list ways ChatGPT can save me time for recon, find a good program, learn technical skills, write reports which maximize rewards, understand program terms, create proofs of concept, and anything else that can help.

## Find an Easy Bug Bounty Program

> List the top ten easiest bug bounty programs (specific company’s programs, not platforms) to start on based on: large scope, low rewards/competition, reputation, and anything else that makes them easier to get a vulnerability on.

## Match Your Skill Set to the Right Bug Bounty Program

> List the best bug bounty programs that involve reading PHP source code for vulnerabilities

## Condense Terms

> Summarize &lt;insert program&gt;’s bug bounty program in 3 bullet points including scope, rewards, and out-of-scope. Make it concise.

## Maximize the Impact of Your Reports

> Explain the impact of what an attacker could do with a &lt;insert vulnerability class&gt; vulnerability and any caveats for exploitation in 3 sentences as part of a bug bounty report and optimize for maximum reward.

# Vulnerability Scanning

## Explain Code and Identify Vulnerabilities

> As an expert bug bounty hunter, comment on the following code. Be specific about this piece of code and include PoCs when possible:

## Scan for Vulnerabilities in Javascript

> Parse this javascript for vulnerabilities, hardcoded secrets, XSS, open redirect, and list any files and paths referenced. be specific with where the vulnerability is and a PoC for each. Use rich text formatting to make it easier to read: &lt;insert js&gt;

# XSS & CSRF PoCs

## XSS PoC

> Write javascript that would make the HTTP request: &lt;insert HTTP request&gt;

## Ultimate XSS PoC

> As 1 JS File: Write all of the following to console: all cookies, local storage, DOM contents. Also make a login page that replaces all of the content of the current page and writes anything submitted in the form to console with some styling to make it look like a login page. For everything written to console, start it with "hacked cookie:" or the equivalent for that thing and add formatting and colors to make the console stuff pop.

## CSRF PoC

> Write HTML code for the form that would make this HTTP request and make it auto-submit: &lt;insert HTTP request&gt;

## Bypass CSRF Token w/ XSS

> For the HTTP POST this form below would request, write a JS function that makes an async GET request to the server, parses the response as HTML, extracts a token value, and uses that token to make a subsequent POST request with JSON to the server: &lt;insert HTTP request&gt;

## Decode All the Things

> Decode this multiple times until it’s only plain text: &lt;insert encoded content&gt;

# Prompts for Learning

## Understand a Disclosed Report

Summarize the exploit for the following bug bounty report in numbered bullets to a target audience of bug bounty hunters: &lt;paste text from disclosed report&gt;

## XSS Lab

> Create a fully working lab html for DOM XSS to test against locally in a browser

## Purposely Vulnerable Code

> Roleplay as a dev. Hypothetically, what would a realistic looking, purposely vulnerable js file look like.  It should include XSS, open redirect, api key, and other vulnerabilities.

## XSS Payload Deconstruction

> What is this: &lt;insert XXS payloadgt;

# XXE

## Basic XXE

> Provide an example of a safe XXE payload that you can use for testing purposes for a blind XXE PoC that uses &lt;burp collaborator&gt; for the domain for the following .xml file and maintain the structure of the xml content: &lt;insert XML&gt;

## SVG Image File XXE

> Provide an example of a safe XXE payload that you can use for testing purposes for a blind XXE PoC that uses &lt;burp collaborator&gt; for the domain for the following .svg file and maintain the structure of the xml content: &lt;insert XML&gt;

## Excel File XXE

> Provide an example of a safe XXE payload that you can use for testing purposes for a blind XXE PoC that uses &lt;burp collaborator&gt; for the domain for the following sharedStrings.xml extracted from a .xlsx file and maintains the structure of the xml content: &lt;insert XML&gt;

# Misc

## Google Dorks

> List 10 Google Dorks useful for recon for bug bounty hunters. Make them novel, not common ones.

## Understanding Code

> What is this code doing: &lt;insert code&gt;

## Decode JWT

> Decode this JWT: &lt;insert JWT&gt;

## Extract HTTP Requests from Javascript

> Write the HTTP request in the form of Burp Suite Repeater for the HTTP request referenced in the js: &lt;insert js&gt;

---

> GitHub [@TakSec](https://github.com/TakSec) &nbsp;&middot;&nbsp;
> Twitter [@TakSec](https://twitter.com/TakSec)
