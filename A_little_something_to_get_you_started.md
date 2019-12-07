### Vulnerabilities (flags) found: 1

### Flag0 ###

#### Method 1 ####
1. From the site's homepage (35.190.155.168.\<session-hash\>), inside the source of the page there is an image whose url is 'background.png'. Append this url to the homepage url.
2. On this new page, the flag should appear in the \<body\> of the source and should be displayed in plaintext on the page.

####Method 2 ####
1. From the site's homepage (35.190.155.168\<session-hash\>), use the developer tools (typically F12) to view the network activity for this page. Hit refresh, and there should be a GET request for a file titled 'background.png'. 
2. Right-click on this file and open it in a new tab, the flag should appear in the \<body\> of the source and should be displayed in plaintext on the page.
