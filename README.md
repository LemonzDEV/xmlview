XV is a browser-based XML viewer, available as a Google Chrome and
Safari extensions.

![][1]

[Online demo][] (works in Chrome, Safari, Firefox)

## Current features

-   **Collapsable elements**: Alt+click to expand/collapse all
    descendant elements
-   **Outline** for better document overview
-   **Search by name or XPath**. By default uses simple search mode
    which looks for a partial match in element‘s or attribute’s name;
    use special symbols like ‘/’ or ‘\[’ to search by XPath
-   **Quick XPath mode**: hold down Command (Mac) or Ctrl (PC) key while
    moving mouse cursor over element‘s or attribute’s name to enter
    Quick XPath mode. Use Shift key to cycle through available XPath
    variants and then drag’n’drop element under cursor into text
    editor.  
    *Google Chrome users: click on element will copy XPath to clipboard*

### Download

-   [Google Chrome extension][]
-   [Safari extension][]

You can also download an [XSL stylesheet][] and use it for styling XML
files with `<?xml-stylesheet type="text/xsl" href="xv-browser.xsl"?>`

### Dev Install and Testing

-   Install [NodeJS v9.1.0][]
-   Run these commands:

### Installation

#### Chrome

-   Got to chrome://extensions/ and Enable XV - XML Viewer. If you want
    the viewer to automatically process XML feeds, Click on Options and
    tick the box <strong>Intercept requests for XML, RSS and ATOM
    documents</strong>

### Note for Safari on Mac plugin

Due to plugin’s nature, the styled XML is very unresponsive on mouse
hover events (like Quick XPath mode) so you have to click on area of
interest to get focus. I’m looking for a solutions of this problem.

------------------------------------------------------------------------

XV design is inspired by MacRabbit’s [Espresso editor][]

  [1]: http://files.chikuyonok.ru/xv/screenshot.png?v=2
  [Online demo]: http://files.chikuyonok.ru/xv/
  [Google Chrome extension]: https://chrome.google.com/webstore/detail/eeocglpgjdpaefaedpblffpeebgmgddk
  [Safari extension]: http://files.chikuyonok.ru/xv/xv.safariextz
  [XSL stylesheet]: https://github.com/sergeche/xmlview/downloads
  [NodeJS v9.1.0]: https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-20-04#option-3-%E2%80%94-installing-node-using-the-node-version-manager
  [Espresso editor]: http://macrabbit.com/espresso/