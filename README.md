# Paramount Petroleum - Default Theme

[![Netlify Status](https://api.netlify.com/api/v1/badges/17758869-2b98-4ae6-87f3-6206ac5d8578/deploy-status)](https://app.netlify.com/sites/goldcoders/deploys)

## Requirements

-   Paramount Petroleum Manager v1.0.0

## Using Checkout with Paymongo

-   You  need to be logged inside netlify account, go to https://app.netlify.com/sites/${SITE_NAME}/settings/deploys#environment , replace the SITE_NAME with your own

Add the Following, Create NEW VARIABLE
```
PAYMONGO_EMAIL
PAYMONGO_PASS
PAYMONGO_LIVEMODE
```
set `livemode` to `true`

## Using Custom Domain Name

-  Go to https://app.netlify.com/sites/${SITE_NAME}/settings/domain , replace the SITE_NAME with your own

Click Add Domain Alias , and set your A record, and other DNS settings

- Go to your Domain provider and point your domain to

```
dns1.p05.nsone.net
dns2.p05.nsone.net
dns3.p05.nsone.net
dns4.p05.nsone.net
```



## Using FB Messenger Chat Plugin

-   get Page ID , on Facebook Fanpage Message Settings and update in on your CMS

## Using Disqus Comment

-   Get Disqus Shortcode and update it on your CMS

## Using Contact Form

### Recaptcha V2

-   [Create Recaptcha For Your Domain](https://www.google.com/recaptcha/admin/create) and copy Site Key

### Creating New Google Form

-   Create New Form
-   Add New Fields
    -   Name
    -   Phone
    -   Message
-   Allow Collecting Emails

### Getting Form URL

-   Click Send Form Click and click via link
-   copy link open it in browser
-   inspect element
-   search for form action
-   copy the url in action

### Adding Field Name

-   Click on the right corner triple dot
-   It will show Get Prefilled Link , Click it
-   Inspect The Form Field
-   Copy the name , it always start with entry.{ANY_NUMBER}
-   paste in on the form field name on contact page
