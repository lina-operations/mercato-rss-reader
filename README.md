# mercato-rss-reader
A HTML news page that outputs news stories on a [Mercato](https://mercatogroup.com.au/) screen reader based on a supplied RSS feed.

## Description

This is designed to work alongside [LINA's Custom RSS WordPress plugin](https://github.com/lina-operations/lina-custom-rss/)

The intention is that you can use this tool to generate a lightweight RSS page for use with Mercato retail screens.

This "News Page" consists of a newsroom masthead, a page heading, three news stories, a subscription call-to-action, and a QR code that can be scanned to take the user to a newsletter signup page, website registration page, etc.

Key assets such as the newsroom masthead and the QR code image can be configured once the ZIP has been loaded as asset into a campaign within Mercato's Digital Signage online manager. Similarly, the Page heading and QR Code Subscribe Call-to-Action can also be modified to suit.

By default, three articles are shown. If there's a need to change this, this can be included in a future release, but the current build is optimised to accommodate three.

The provided RSS feed is checked once an hour and updates on-screen accordingly.

## Installation

1. Download the package by clicking the green "Code" button to reveal the "Download Zip" option.
2. When using Mercato's Digital Signage online manager, once you've created your "News" Campaign, upload this zip file as your 

## Defaults

The **Page Heading** shows the copy "News Headlines" by default.

The **QR Code Subscribe Call-to-Action** shows the copy "Subscribe to our free weekly newsletter" by default.

The **Header background and Article title colour** shows the hexidecimal colour code #0495da by default. 

Please note that the images included in this package are courtesy of [Western Weekender](https://westernweekender.com.au/). These can be changed to suit your masthead once you have created your Mercato Campaign.

## Recommendations

To generate your own QR code, we used [Canva](https://www.canva.com/), which has its own built-in QR code generation tool. There are many other tools available online.

We recommend any images that are uploaded be first optimised by [TinyPNG](https://tinypng.com/).

## Requirements

1. The default Newsroom Image is defined at 600 x 150px (width by height). Feel free to put in an logo with a width that is different to this, but for best results ensure the height is 150px. Transparent PNGs are supported, or if you do have a background colour for your logo, ensure it matches the header background colour.
2. The QR code image is rendered at 200 x 200px (width by height). As long as your image is square and at least this size, you'll be fine.
3. A hexadecimal color code represents a color by defining the intensity of its red, green, and blue components. The easiest way to get one is to use a digital color picker tool, which can be found online or built into design software and web browsers. Design tools such as Photoshop, or online equivalents such as [Canva](https://www.canva.com/) or [Photopea](https://www.photopea.com/) can be used to get this. You can also use browser plugins such ColorZilla.

## Thanks

Thanks to the team at Mercato for answering a number of questions about how the Mercato Digital Signage online manager works, particularly Sam Radwan and Matt Bannon. And also to Troy Dodds of the Western Weekender for allowing me to use his publication as a guinea pig for all of this!

## License

This plugin is licensed under the GPL-3.0. For more information, see the [license file](https://github.com/lina-operations/lina-custom-rss/blob/main/LICENSE). 