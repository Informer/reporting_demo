# Errors

<aside class="notice">
This error section is stored in a separate file in <code>includes/_errors.md</code>. Slate allows you to optionally separate out your docs into many files...just save them to the <code>includes</code> folder and add them to the top of your <code>index.md</code>'s frontmatter. Files are included in the order listed.
</aside>

The Kittn API uses the following error codes:


Error Code | Meaning
---------- | -------
400 | Bad Request -- Your request is invalid.
401 | Unauthorized -- Your API key is wrong.
403 | Forbidden -- The requested filter is hidden for administrators only.
404 | Not Found -- The specified filter could not be found.
405 | Method Not Allowed -- You tried to access a filter with an invalid method.
406 | Not Acceptable -- You requested a format that isn't json.
418 | I'm a stormtrooper.
429 | Too Many Requests -- Whoa partner! Slow down! Come back in 10mins
500 | Internal Server Error -- We had a problem with our server. Try again later.
503 | Service Unavailable -- We're temporarily offline for maintenance. Please try again later.
