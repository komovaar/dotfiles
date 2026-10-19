# Firefox fonts

`userChrome.css` uses the system sans-serif font for Firefox tabs, toolbars,
and menus, independent of the GTK desktop font. Web pages keep their own fonts.

Copy the stylesheet to `chrome/userChrome.css` inside your Firefox profile.
Set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true` in
`about:config`, then fully quit and reopen Firefox.
