### Vulnerabilities (flags) found: 4

### Flag0 ###

1. Attempt to edit page 4 by navigating to url http://34.74.105.127/<session-hash\>/page/edit/4
2. A flag should appear inside the editable body of the page.

### Flag1 ###

1. Attempt to edit some page with a malformed name by navigating to url http://34.74.105.127/<session-hash\>/page/edit/'
2. A flag should appear in plaintext on the page

### Flag2 ###

1. Create a page with the title of '\<script\>alert(1)\</script\>' and body of any text
2. After submitting the page, click 'Go Home'
3. A flag should appear in plaintext in a popup on the page. This flag can be copied from the popup or by viewing it in the source of the page.

### Flag3 ###

1. Create a page with any text as the title
2. Enter the body of the page as '<body onload=alert(1)></body>'
3. Upon submitting the page, the flag should appear

