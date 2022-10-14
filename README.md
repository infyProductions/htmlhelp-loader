# Welcome to HHLoader! (HtmlHelp Loader)
## Description:
*HHLoader* allows html help to browse the internet using this html file.

> DISCLAIMER: HTML help uses an older version of Internet Explorer. *DO NOT* use this to enter sensitive information like e-mails and password and you might likely get a lot of javascript errors while using it on other sites. (Please don't load untrusted javascript that might compromise your machine)

## Features include:
1. Common hyperlinks (including Google, DuckDuckGo, Command Prompt [cmd.exe], and Windows PowerShell Legacy [powershell.exe])
2. A custom URL redirector (to browse other websites directly)
3. Shows browser info (like browser name and user agent header

## How to use:
- RUN Box - Press Win + R keys and type the following:
`hh \path\to\hhloader.html`
- Command Prompt (CMD) or Powershell (powershell [legacy] or pwsh [core]) - Enter the following on the prompt:
`hh \path\to\hhloader.html`
> TIP: Use the Tab key to autofill a query quicker.

## Common Issues:
- Can't browse more modern html5 based websites (like Youtube, Facebook):
1. HTML Help uses IE7 compatible webview is the reason why some sites say "Your browser is unsupported".
2. You might receive multiple javascript warnings if you try to load a webpage.
- The Stylesheet is broken (layman term: the look and feel of the site feels incorrect):
1. IE7 compatible webview might be unsupported for newer CSS standards. Some sites do have an older CSS implementation or uses just the basic CSS on HTML (like Google).
