# Bringhurst CSS Styles

/* Testing Push Mirror */

Cascading Style Sheets (CSS) make it easy to apply a set of styles across all of the pages that comprise a websites. In the 4th edition of Robert Bringhurst's *The Elements of Typographic Style,*<sup>*</sup> the author applies simple design principles to headings on a page. This is my application of those styles to <abbr>HTML<abbr>.

## Google Webfonts and Bringhurst Style

Google provides a wide range of webfonts, two of which provide a full spectrum of styles. Playfair and Alegreya, along with their Small Capitals variants, provide a total of 12 styles apiece in the Latin extended set.

Using one of these two webfonts provides ample resources for designers to apply the principles outlined by Bringhurst.<sup>* See footnote</sup> The included examples include the complete set of webfonts; however, a designer should bridle their implementation to accommodate actual use.

See what they look like:

- [Playfair 66][14]
- [Playfair 67][15]
- [Alegreya 66][16]
- [Alegreya 67][17]

For displaying code or other cases where preformatted text is required I recommend Adobe Source Code Pro, which provides seven styles in the Latin extended set. It is included in both examples below. Though unused here, Adobe Source Sans Pro is another excellent typeface to serve your sans serif needs.

### Playfair & Playfair SC

[**Claus Eggers Sørensen**][0]   
[**SIL Open Font License, 1.1**][1]   

Playfair is a transitional design. From the time of enlightenment in the late 18th century, the broad nib quills were replaced by pointed steel pens. This influenced typographical letterforms to become increasingly detached from the written ones. Developments in printing technology, ink, and paper making, made it possible to print letterforms of high contrast and delicate hairlines.

This design lends itself to this period, and while it is not a revival of any particular design, it takes influence from the designs of printer and typeface designer John Baskerville, the punchcutter William Martin's typeface for the 'Boydell Shakspeare' (sic) edition, and from the 'Scotch Roman' designs that followed thereafter.

As the name indicates, Playfair Display is well suited for titling and headlines. It has an extra large x-height and short descenders. It can be set with no leading if space is tight, for instance in news headlines, or for stylistic effect in titles. Capitals are extra short, and only very slightly heavier than the lowercase characters. This helps achieve a more even typographical colour when typesetting proper nouns and initialisms. Languages, like German, where nouns are capitalized, particularly benefit from this lower contrast between lower and upper case glyphs. In German, with its many capitalised words, and in other European languages that use many diacritical characters, it is advised to use more leading.

Being a transitional design, stylistically Playfair can accompany Georgia, where Georgia is used for body text.

Playfair's downloaded font files include a full set of [small caps][2], common ligatures, and discretionary ligatures. For Polish, a set of alternate diacritical characters designed with 'kreska's are included. All European languages using the latin script are supported. A set of eight arrow devices are also included.

To contribute to the project contact Claus Eggers Sørensen [here][3].

<cite>---[Google Webfonts -- Playfair][8]</cite>

[0]: https://plus.google.com/102070068022044858239/about
[1]: http://scripts.sil.org/OFL
[2]: http://www.google.com/webfonts/specimen/Playfair+Display+SC
[3]: mailto:es@forthehearts.net

#### Playfair (Standard)

`<link href='http://fonts.googleapis.com/css?family=Playfair+Display:400,700,900,400italic,700italic,900italic|Source+Code+Pro:200,300,400,500,600,700,900|Playfair+Display+SC:400,400italic,700,700italic,900,900italic&subset=latin,latin-ext' rel='stylesheet' type='text/css'>`

#### Playfair @import

`@import url(http://fonts.googleapis.com/css?family=Playfair+Display:400,700,900,400italic,700italic,900italic|Source+Code+Pro:200,300,400,500,600,700,900|Playfair+Display+SC:400,400italic,700,700italic,900,900italic&subset=latin,latin-ext);`

#### Playfair (Javascript)

`<script type="text/javascript">
    WebFontConfig = {
      google: { families: [ 'Playfair+Display:400,700,900,400italic,700italic,900italic:latin,latin-ext', 'Source+Code+Pro:200,300,400,500,600,700,900:latin,latin-ext', 'Playfair+Display+SC:400,400italic,700,700italic,900,900italic:latin,latin-ext' ] }
    };
    (function() {
      var wf = document.createElement('script');
      wf.src = ('https:' == document.location.protocol ? 'https' : 'http') +
        '://ajax.googleapis.com/ajax/libs/webfont/1/webfont.js';
      wf.type = 'text/javascript';
      wf.async = 'true';
      var s = document.getElementsByTagName('script')[0];
      s.parentNode.insertBefore(wf, s);
    })(); </script>`

#### Playfair CSS

`font-family: 'Playfair Display', serif;`   
`font-family: 'Source Code Pro', sans-serif;`   
`font-family: 'Playfair Display SC', serif;`

### Alegreya & Alegreya SC

[**Huerta Tipográfica**][4]   
[**SIL Open Font License, 1.1**][5]   

Alegreya was chosen as one of 53 "Fonts of the Decade" at the ATypI Letter2 competition in September 2011, and one of the top 14 text type systems. It was also selected in the 2nd Bienal Iberoamericana de Diseño, competition held in Madrid in 2010\. 

Alegreya is a typeface originally intended for literature. Among its crowning characteristics, it conveys a dynamic and varied rhythm which facilitates the reading of long texts. Also, it provides freshness to the page while referring to the calligraphic letter, not as a literal interpretation, but rather in a contemporary typographic language. 

The italic has just as much care and attention to detail in the design as the roman. The bold weights are strong, and the Black weights are really experimental for the genre. There is also a [Small Caps][6] sister family. 

Not only does Alegreya provide great performance, but also achieves a strong and harmonious text by means of elements designed in an atmosphere of diversity. 

Designed by Juan Pablo del Peral for [Huerta Tipográfica][7].

<cite>---[Google Webfonts -- Alegreya][9]</cite>

#### Alegreya (Standard)

`<link href='http://fonts.googleapis.com/css?family=Source+Code+Pro:200,300,400,500,600,700,900|Alegreya:400italic,700italic,900italic,400,700,900|Alegreya+SC:400,400italic,700,700italic,900,900italic&subset=latin,latin-ext' rel='stylesheet' type='text/css'>`

#### Alegreya (@import)
`@import url(http://fonts.googleapis.com/css?family=Source+Code+Pro:200,300,400,500,600,700,900|Alegreya:400italic,700italic,900italic,400,700,900|Alegreya+SC:400,400italic,700,700italic,900,900italic&subset=latin,latin-ext);`

#### Alegreya (Javascript)

`<script type="text/javascript">
  WebFontConfig = {
    google: { families: [ 'Source+Code+Pro:200,300,400,500,600,700,900:latin,latin-ext', 'Alegreya:400italic,700italic,900italic,400,700,900:latin,latin-ext', 'Alegreya+SC:400,400italic,700,700italic,900,900italic:latin,latin-ext' ] }
  };
  (function() {
    var wf = document.createElement('script');
    wf.src = ('https:' == document.location.protocol ? 'https' : 'http') +
      '://ajax.googleapis.com/ajax/libs/webfont/1/webfont.js';
    wf.type = 'text/javascript';
    wf.async = 'true';
    var s = document.getElementsByTagName('script')[0];
    s.parentNode.insertBefore(wf, s);
  })(); </script>`

### Adobe Source Code Pro

[**Paul D. Hunt**][10]   
[**SIL Open Font License, 1.1**][11]   

Source Code was designed by Paul D. Hunt as a companion to Source Sans. This complementary family was adapted from the Source design due to a request to create a monospaced version for coding applications. Source Code preserves the design features and vertical proportions of Source Sans, but alters the glyph widths so that they are uniform across all glyphs and weights.

Although this family was designed specifically for coding environments, for which a regular weight will typically suffice, Source Code has been made available in the same weight range as the corresponding Source Sans design. Source Code Pro currently supports a wide range of languages using the Latin script, and includes all the characters in the Adobe Latin 4 glyph set.

As an open source project, it is expected that incremental updates will be made over time to extend glyph set coverage and functionality. Future releases are expected to add support for Greek and Cyrillic scripts, italics, and other features documented on the project page at [Open@Adobe][12], which is hosted by SourceForge.

If you are interested in contributing to this open source project, please visit this project page for information on how to become involved. Source Code Pro can be adapted and redistributed according to the terms of the Open Font License (OFL) agreement.

<cite>---[Google Webfonts -- Source Sans Pro][13]</cite>

[4]: https://plus.google.com/u/0/112473143573572123748/about
[5]: http://scripts.sil.org/OFL
[6]: http://www.google.com/webfonts/specimen/Alegreya+SC
[7]: http://www.huertatipografica.com.ar/
[8]: https://www.google.com/fonts/specimen/Playfair+Display
[9]: https://www.google.com/fonts/specimen/Alegreya
[10]: https://plus.google.com/108888178732927400671/about
[11]: http://scripts.sil.org/OFL
[12]: http://sourceforge.net/adobe
[13]: https://www.google.com/fonts/specimen/Source+Code+Pro
[14]: http://carryingstones.com/bringhurst/playfair-66.html
[15]: http://carryingstones.com/bringhurst/playfair-67.html
[16]: http://carryingstones.com/bringhurst/alegreya-66.html
[17]: http://carryingstones.com/bringhurst/playfair-67.html

\* --- Bringhurst, R. (2012). Elements of Typographic Style (4th ed.). Vancouver: Hartley & Marks. pp 66--67.
