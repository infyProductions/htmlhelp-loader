# Welcome to HHLoader! (HtmlHelp Loader)

### Github release 1.5 Alpha

![hhloader_sample](https://user-images.githubusercontent.com/31158494/195764553-224ffeaf-06fc-46bf-abda-6218cd0a3266.png)
## Description:
*HHLoader* allows html help to browse the internet with the help this early HTML style-like file.

> DISCLAIMER: HTML help uses an old and minimal version of Internet Explorer. *DO NOT* use this to enter sensitive information like e-mails and password and you might likely get a lot of javascript errors while using it on other sites specially modern ones with lots heavy javascript or even HTML 5 content.

## Features include:
1. Common hyperlinks (including Google, DuckDuckGo, Frogfind, TheOldNet [Full and Lite], Command Prompt [cmd.exe], and Windows PowerShell Legacy [powershell.exe])
2. A custom URL redirector to browse other websites directly (Don't even attempt to load more modern websites involving heavy javascript)
3. Shows browser info in the bottom (like browser name and user agent header)

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
