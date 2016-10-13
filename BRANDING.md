## Branding

In order to use this extension with your own brand (naming, icons, URL), follow these steps.
Note: this document is intentionally
sparse, as most of the important information is in the links provided, and
is subject to change at Google Chrome's discretion.

1. Fork the repo - You may fork the repo with source control, or simply download
the source files for the `extension` directory.
2. Use your own icons - Replace the `images/icon-` files with an icon of your
own (use png format, in the three sizes specified). See [Supplying Images][1]
for more details.
3. Use your own translations - This repo has internationalization already
configured, for rendering the extension in multiple languages. You may use
these translations, replacing `PureCloud` with your own Brand Name, or hard code
the strings of your choice.
4. Publish your extension to the Chrome WebStore - [Publishing][3] (additional
info on [the tutorial][5])
5. For inline installation (recommended - for one click install)
    1. [Prove Site OwnerShip][4] on [Webmaster Tools][6]
    2. Ensure the Extension is associated with your URL, and that `Inline
    Installation` is checked in the developer dashboard.


[1]: https://developer.chrome.com/webstore/images
[2]: https://developer.chrome.com/webstore/inline_installation
[3]: https://developer.chrome.com/webstore/publish
[4]: https://support.google.com/webmasters/answer/34592?hl=en
[5]: https://developer.chrome.com/webstore/get_started_simple#step5
[6]: http://www.google.com/webmasters/
