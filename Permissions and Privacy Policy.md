# Technical Overview and Privacy Policy

This details the Technical Overview and Privacy Policy for the Multi Forward for Gmail chrome extension.

## Technical Overview

Multi Forward for Gmail uses OAuth for user authentication to Gmail.
It also uses Google Apps script to forward the emails selected by the user.

### Permissions
The extension needs access to the following authentication scopes to function properly:

- https://mail.google.com/ 
  
  This is needed to forward emails on behalf of the user and add the "multi-forward" label to the forwarded thread.

- https://www.googleapis.com/auth/contacts.readonly
  
  This is needed to have read only access to the user's contact list. This is needed for auto-completion of recipient email addresses.

- https://www.googleapis.com/auth/script.storage

  This is needed by the Google App script to read and write data. The following data is stored per user:
    - The total number of emails forwarded using the extension by the user.
    - The total number of emails forwarded using the extension by the user on a given day. 
  
  This is required to surface better information to the user.

- https://www.googleapis.com/auth/userinfo.email 
  
  This is needed to fetch your email address.

## Privacy Policy

Personal information this extension accesses
- Your email address.
- The emails you select to be forwarded using the extension.
- Your contact list.

All this information is required for the extension to function. This information is never stored on any servers or shared with any third party.

For more information, see the Technical Overview section above.
