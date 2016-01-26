# CMI responsive email template

The CMI email templates are built using the 1.X version of the ZURB Ink framework.  The documentation for the framework is included in the repo in `./inc-docs`.  

## Relevant template files
```
.
---+ templates
     +--- articles.html (template for Articles of Interest)
     +--- prices.html (template for Daily Prices)
     +--- specials-v2.html (template for Specials)
```

All other template files are either old or one off emails.  All images should be hosted on MailChimp.

## Importing into MailChimp
Before the edited template can be copy and pasted into MailChimp, all css needs to be inlined using a css inliner.  The [ZURB inliner](http://foundation.zurb.com/emails/inliner.html) is a good choice.

1. Open email template localy so you can view source and copy html
2. Paste html into inliner
3. Copy inlined html and paste it into MailChimp template editor
4. Do not save the inlined html locally, that can be discarded after it's imported into MailChimp

## Ink

Ink is a responsive email framework, used to make HTML emails look great on any client or device.  It includes a 12-column grid, as well as some simple UI elements for rapid prototyping.

Homepage:      http://zurb.com/ink<br />
Documentation: http://zurb.com/ink/docs.php<br />
Download:      http://zurb.com/ink/download.php

Ink is MIT-licensed and absolutely free to use. Ink wouldn't be possible without the support of the entire ZURB team, our friends and colleagues who gave feedback, and some luminaries who did some heavy lifting that we took advantage of (thanks guys).
