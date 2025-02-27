# Open Dyslexic

![Facebook example](https://github.com/antijingoist/open-dyslexic/raw/master/screenshots/facebook-dyslexic.png)

![ZDNet example](https://github.com/antijingoist/open-dyslexic/raw/master/screenshots/zdnetarticle.PNG)

_This is a minor modification of the original [open-dyslexic](https://github.com/antijingoist/open-dyslexic) repo to make it possible to easily include this in Node projects. All credit goes to the original authors there._

## Example Usage


```bash
$ npm i open-dyslexic require-style
$ npm i yo-yo
```

```js
var requireStyle = require('require-style')
var html = require('yo-yo')

var style = html`
  <style>
    ${requireStyle('open-dyslexic')} 

    body {
      font-family: OpenDyslexicRegular;
    }
  </style>
`
document.head.appendChild(style)


var hello = html`
  <h1>Hello Open Dyslexic!</h1>
`
document.body.appendChild(hello)
```

Notes : this "just works" in electron apps, but for bundled apps read `require-style` documentation about bundling transforms.

## Original README

Download the [latest bleeding edge version](https://github.com/antijingoist/open-dyslexic/archive/master.zip).

Places I've officially uploaded the latest stable versions to are [dafont.com](http://dafont.com/open-dyslexic.font) and [opendyslexic.org](http://opendyslexic.org)

The latest version may not always be the best version. If you want a stable version, check [github](https://github.com/antijingoist/open-dyslexic/tags) for the latest stable or working beta including otf's and ttf's, or [DaFont](http://dafont.com/open-dyslexic.font) for a stable otf.

For ease of use there is a CDN provided by [ClarkHacks](https://clarkhacks.com/)

__V1__

`https://cdn.clarkhacks.com/OpenDyslexic/v1/OpenDyslexic.css`

__V2__

`https://cdn.clarkhacks.com/OpenDyslexic/v2/OpenDyslexic.css`

__V3__

`https://cdn.clarkhacks.com/OpenDyslexic/v3/OpenDyslexic.css`

The CDN is powered by CloudFlare for ultra-fast and reliable connections.

If you are upgrading your copy of this font, you may want to remove previous version first. 

Typeface/font to help readability, and help readability for some of the symptoms of dyslexia.

Your brain can sometimes do funny things to letters. OpenDyslexic tries to help prevent some of these things from happening. Letters have heavy weighted bottoms to provide an indication of orientation to make it more difficult to confuse with other similar letters. Consistently weighted bottoms can also help reenforce the line of text. The unique shapes of each letter can help prevent flipping and swapping.

The italic style for OpenDyslexic has been crafted still be able to be used for emphasis while still being readable. 

Thanks to everyone that donated during the Glyphs.app fundraising:

- Cheryl Marshall
- Anonymous (MG). <-- look at that, anonymous supports this. :D 
- Eric Bailey
- Steven V James
- @nguarracino
- Plow Software, LLC

You guys are super cool! Thanks!

Also, thanks to:
- @glyphsapp for helping me learn Glyphs. 
- Rob Carpenter of Oak Grove College in England for the Alta style
- The awesome folk @ TEDxGateway that still have yet to release the OpenDyslexic TEDx talk.

It is based on Bitstream Vera Sans because of the nice license it has. 

OpenDyslexic is not packaged by me as an .exe file. It is packaged as a zip file, with no installer,  so you know what you are getting.

If you were compelled to pay for this font, ask for a refund. This font is provided at no charge. Donations are cool though. :)

License
-------
The license for this font is: 

♡ Copying is an act of love. Please copy.

Bitstream License: 

Copyright (c) 2003 by Bitstream, Inc. All Rights Reserved. Bitstream Vera is a trademark of Bitstream, Inc. 

Permission is hereby granted, free of charge, to any person obtaining a copy of the fonts accompanying this license (“Fonts”) and associated documentation files (the “Font Software”), to reproduce and distribute the Font Software, including without limitation the rights to use, copy, merge, publish, distribute, and/or sell copies of the Font Software, and to permit persons to whom the Font Software is furnished to do so, subject to the following conditions: 

The above copyright and trademark notices and this permission notice shall be included in all copies of one or more of the Font Software typefaces.

The Font Software may be modified, altered, or added to, and in particular the designs of glyphs or characters in the Fonts may be modified and additional glyphs or characters may be added to the Fonts, only if the fonts are renamed to names not containing either the words “Bitstream” or the word “Vera”.

This License becomes null and void to the extent applicable to Fonts or Font Software that has been modified and is distributed under the “Bitstream Vera” names. 

The Font Software may be sold as part of a larger software package but no copy of one or more of the Font Software typefaces may be sold by itself. 

THE FONT SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO ANY WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT OF COPYRIGHT, PATENT, TRADEMARK, OR OTHER RIGHT. IN NO EVENT SHALL BITSTREAM OR THE GNOME FOUNDATION BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, INCLUDING ANY GENERAL, SPECIAL, INDIRECT, INCIDENTAL, OR CONSEQUENTIAL DAMAGES, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF THE USE OR INABILITY TO USE THE FONT SOFTWARE OR FROM OTHER DEALINGS IN THE FONT SOFTWARE. 

Except as contained in this notice, the names of Gnome, the Gnome Foundation, and Bitstream Inc., shall not be used in advertising or otherwise to promote the sale, use or other dealings in this Font Software without prior written authorization from the Gnome Foundation or Bitstream Inc., respectively. For further information, contact: fonts at gnome dot org. 

Remember in 2013 where Chrome messed up the font rendering on Windows XP? At least I'll be able to know ahead of time with this now. :)
[![BrowserStack Status](https://apathyonline.net/browserstack-logo-600x315.png)](https://browserstack.com/)
