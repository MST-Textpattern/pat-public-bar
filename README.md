# pat-public-bar

Textpattern plugin

Add a bar on your website to access side to side from public to admin pages.

Support for multi-sites installation (with sub domain), context & privileges sensitiv and give access to 'Section', 'Form', 'CSS' tabs (only for users with 1, 2 or 6 privs level); 'Article' (with 'edit' or 'create new' option), 'Categories', 'Images' tabs. Access to Textpattern interface (with official logo branding), log-out link, i18n capable.

Very discreet appearance to not interfere with the design of websites, appears on mouseover (only for users connected) to the top of the page (figured with a black horizontal line). Customizable colors (background and characters).


## Plugin help

Just add `<txp:pat_public_bar />` in your page templates where to show this bar on your website (public side) only available for login-in users.

Notice: due to the support of multi-site installations the bar only disappear when the client's browser is closed.

## Attributes

> **interface** *String* (optional): only for multi-site installations context, set your Textpattern back-office address (i.e. admin.example.com). Default: /root/textpattern (default TXP back-office address).
>
> **bgcolor** *String* (optional): change the background color of the bar. Default: rgba(0, 0, 0, 0.8)
>
> **color** *String* (optional): change the font color into the bar. Default: #fff.

## Changelog

    2d August 2015: v 0.3.2. Admin privs can access to "Section", "Page" and "Style" tabs.
    1st August 2015: v. 0.3.1. Add "bgcolor" and "color" attributes.
    30th July 2015: v. 0.3.0. Support for multi-site installations.
    29th April 2015: v 0.2. Add image & category page links.
    25th July 2014: first release.


