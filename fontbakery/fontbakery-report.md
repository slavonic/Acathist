## FontBakery report

fontbakery version: 0.13.2





## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] Acathist-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check base characters have non-zero advance width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#base-has-width">base_has_width</a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs had zero advance width:
- uniE005 (U+E005)</p>
 [code: zero-width-bases]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[23] Acathist-Regular.ttf</summary>
<div>
<details>
    <summary>💥 <b>ERROR</b> Familyname must be unique according to namecheck.fontdata.com <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#fontdata-namecheck">fontdata_namecheck</a></summary>
    <div>







* 💥 **ERROR** <p>Failed to access: <a href="https://namecheck.fontdata.com/api/?q=Acathist">https://namecheck.fontdata.com/api/?q=Acathist</a>.
This check relies on the external service <a href="http://namecheck.fontdata.com">http://namecheck.fontdata.com</a> via the internet. While the service cannot be reached or does not respond this check is broken.</p>
<pre><code>	You can exclude this check with the command line option:
	-x fontdata_namecheck

	Or you can wait until the service is available again.
	If the problem persists please report this issue at: https://github.com/fonttools/fontbakery/issues

	Original error message:
	&lt;class 'requests.exceptions.ConnectionError'&gt;
</code></pre>
 [code: namecheck-service]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#family-win-ascent-and-descent">family/win_ascent_and_descent</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinAscent value should be equal or greater than 1051, but got 939 instead</p>
 [code: ascent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking Vertical Metric Linegaps. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#linegaps">linegaps</a></summary>
    <div>







* 🔥 **FAIL** <p>hhea lineGap is not equal to 0.</p>
<p><em>Overridden</em>: This check was originally a WARN but was
overridden by the universal profile:
For Google Fonts, all messages from this check are considered FAILs.</p>
 [code: hhea]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 Metrics match hhea Metrics. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#os2-metrics-match-hhea">os2_metrics_match_hhea</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoLineGap (33) and hhea lineGap (17) must be equal.</p>
 [code: lineGap]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* 🔥 **FAIL** <p>GF_TransLatin_Arabic glyphset:</p>
<table>
<thead>
<tr>
<th align="left">FAIL messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ѫ, ѩ, ѥ, Ѩ, Џ, Ѫ, Ѥ, ѭ, Ѭ, џ</td>
<td align="left">cu_Cyrl (Church Slavic)</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check copyright namerecords match license file. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-name-license">googlefonts/name/license</a></summary>
    <div>







* 🔥 **FAIL** <p>Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set.</p>
 [code: missing]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyph-coverage">googlefonts/glyph_coverage</a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x0100 (LATIN CAPITAL LETTER A WITH MACRON)


- 0x0101 (LATIN SMALL LETTER A WITH MACRON)


- 0x0102 (LATIN CAPITAL LETTER A WITH BREVE)


- 0x0103 (LATIN SMALL LETTER A WITH BREVE)


- 0x0104 (LATIN CAPITAL LETTER A WITH OGONEK)


- 0x0105 (LATIN SMALL LETTER A WITH OGONEK)


- 0x0106 (LATIN CAPITAL LETTER C WITH ACUTE)


- 0x0107 (LATIN SMALL LETTER C WITH ACUTE)


- 0x010A (LATIN CAPITAL LETTER C WITH DOT ABOVE)


- 0x010B (LATIN SMALL LETTER C WITH DOT ABOVE)


- 0x010C (LATIN CAPITAL LETTER C WITH CARON)


- 0x010D (LATIN SMALL LETTER C WITH CARON)


- 0x010E (LATIN CAPITAL LETTER D WITH CARON)


- 0x010F (LATIN SMALL LETTER D WITH CARON)


- 0x0110 (LATIN CAPITAL LETTER D WITH STROKE)


- 0x0111 (LATIN SMALL LETTER D WITH STROKE)


- 0x0112 (LATIN CAPITAL LETTER E WITH MACRON)


- 0x0113 (LATIN SMALL LETTER E WITH MACRON)


- 0x0116 (LATIN CAPITAL LETTER E WITH DOT ABOVE)


- 0x0117 (LATIN SMALL LETTER E WITH DOT ABOVE)


- 0x0118 (LATIN CAPITAL LETTER E WITH OGONEK)


- 0x0119 (LATIN SMALL LETTER E WITH OGONEK)


- 0x011A (LATIN CAPITAL LETTER E WITH CARON)


- 0x011B (LATIN SMALL LETTER E WITH CARON)


- 0x011E (LATIN CAPITAL LETTER G WITH BREVE)


- 0x011F (LATIN SMALL LETTER G WITH BREVE)


- 0x0120 (LATIN CAPITAL LETTER G WITH DOT ABOVE)


- 0x0121 (LATIN SMALL LETTER G WITH DOT ABOVE)


- 0x0122 (LATIN CAPITAL LETTER G WITH CEDILLA)


- 0x0123 (LATIN SMALL LETTER G WITH CEDILLA)


- 0x0126 (LATIN CAPITAL LETTER H WITH STROKE)


- 0x0127 (LATIN SMALL LETTER H WITH STROKE)


- 0x012A (LATIN CAPITAL LETTER I WITH MACRON)


- 0x012B (LATIN SMALL LETTER I WITH MACRON)


- 0x012E (LATIN CAPITAL LETTER I WITH OGONEK)


- 0x012F (LATIN SMALL LETTER I WITH OGONEK)


- 0x0130 (LATIN CAPITAL LETTER I WITH DOT ABOVE)


- 0x0136 (LATIN CAPITAL LETTER K WITH CEDILLA)


- 0x0137 (LATIN SMALL LETTER K WITH CEDILLA)


- 0x0139 (LATIN CAPITAL LETTER L WITH ACUTE)


- 0x013A (LATIN SMALL LETTER L WITH ACUTE)


- 0x013B (LATIN CAPITAL LETTER L WITH CEDILLA)


- 0x013C (LATIN SMALL LETTER L WITH CEDILLA)


- 0x013D (LATIN CAPITAL LETTER L WITH CARON)


- 0x013E (LATIN SMALL LETTER L WITH CARON)


- 0x0141 (LATIN CAPITAL LETTER L WITH STROKE)


- 0x0142 (LATIN SMALL LETTER L WITH STROKE)


- 0x0143 (LATIN CAPITAL LETTER N WITH ACUTE)


- 0x0144 (LATIN SMALL LETTER N WITH ACUTE)


- 0x0145 (LATIN CAPITAL LETTER N WITH CEDILLA)


- 0x0146 (LATIN SMALL LETTER N WITH CEDILLA)


- 0x0147 (LATIN CAPITAL LETTER N WITH CARON)


- 0x0148 (LATIN SMALL LETTER N WITH CARON)


- 0x0150 (LATIN CAPITAL LETTER O WITH DOUBLE ACUTE)


- 0x0151 (LATIN SMALL LETTER O WITH DOUBLE ACUTE)


- 0x0154 (LATIN CAPITAL LETTER R WITH ACUTE)


- 0x0155 (LATIN SMALL LETTER R WITH ACUTE)


- 0x0158 (LATIN CAPITAL LETTER R WITH CARON)


- 0x0159 (LATIN SMALL LETTER R WITH CARON)


- 0x015A (LATIN CAPITAL LETTER S WITH ACUTE)


- 0x015B (LATIN SMALL LETTER S WITH ACUTE)


- 0x015E (LATIN CAPITAL LETTER S WITH CEDILLA)


- 0x015F (LATIN SMALL LETTER S WITH CEDILLA)


- 0x0160 (LATIN CAPITAL LETTER S WITH CARON)


- 0x0161 (LATIN SMALL LETTER S WITH CARON)


- 0x0164 (LATIN CAPITAL LETTER T WITH CARON)


- 0x0165 (LATIN SMALL LETTER T WITH CARON)


- 0x016A (LATIN CAPITAL LETTER U WITH MACRON)


- 0x016B (LATIN SMALL LETTER U WITH MACRON)


- 0x016E (LATIN CAPITAL LETTER U WITH RING ABOVE)


- 0x016F (LATIN SMALL LETTER U WITH RING ABOVE)


- 0x0170 (LATIN CAPITAL LETTER U WITH DOUBLE ACUTE)


- 0x0171 (LATIN SMALL LETTER U WITH DOUBLE ACUTE)


- 0x0172 (LATIN CAPITAL LETTER U WITH OGONEK)


- 0x0173 (LATIN SMALL LETTER U WITH OGONEK)


- 0x0174 (LATIN CAPITAL LETTER W WITH CIRCUMFLEX)


- 0x0175 (LATIN SMALL LETTER W WITH CIRCUMFLEX)


- 0x0176 (LATIN CAPITAL LETTER Y WITH CIRCUMFLEX)


- 0x0177 (LATIN SMALL LETTER Y WITH CIRCUMFLEX)


- 0x0178 (LATIN CAPITAL LETTER Y WITH DIAERESIS)


- 0x0179 (LATIN CAPITAL LETTER Z WITH ACUTE)


- 0x017A (LATIN SMALL LETTER Z WITH ACUTE)


- 0x017B (LATIN CAPITAL LETTER Z WITH DOT ABOVE)


- 0x017C (LATIN SMALL LETTER Z WITH DOT ABOVE)


- 0x017D (LATIN CAPITAL LETTER Z WITH CARON)


- 0x017E (LATIN SMALL LETTER Z WITH CARON)


- 0x0218 (LATIN CAPITAL LETTER S WITH COMMA BELOW)


- 0x0219 (LATIN SMALL LETTER S WITH COMMA BELOW)


- 0x021A (LATIN CAPITAL LETTER T WITH COMMA BELOW)


- 0x021B (LATIN SMALL LETTER T WITH COMMA BELOW)


- 0x0237 (LATIN SMALL LETTER DOTLESS J)


- 0x02C7 (CARON)


- 0x02D8 (BREVE)


- 0x02D9 (DOT ABOVE)


- 0x02DB (OGONEK)


- 0x02DD (DOUBLE ACUTE ACCENT)


- 0x0302 (COMBINING CIRCUMFLEX ACCENT)


- 0x0303 (COMBINING TILDE)


- 0x0304 (COMBINING MACRON)


- 0x030A (COMBINING RING ABOVE)


- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


- 0x030C (COMBINING CARON)


- 0x0326 (COMBINING COMMA BELOW)


- 0x0327 (COMBINING CEDILLA)


- 0x0328 (COMBINING OGONEK)


- 0x1E80 (LATIN CAPITAL LETTER W WITH GRAVE)


- 0x1E81 (LATIN SMALL LETTER W WITH GRAVE)


- 0x1E82 (LATIN CAPITAL LETTER W WITH ACUTE)


- 0x1E83 (LATIN SMALL LETTER W WITH ACUTE)


- 0x1E84 (LATIN CAPITAL LETTER W WITH DIAERESIS)


- 0x1E85 (LATIN SMALL LETTER W WITH DIAERESIS)


- 0x1E9E (LATIN CAPITAL LETTER SHARP S)


- 0x1EF2 (LATIN CAPITAL LETTER Y WITH GRAVE)


- 0x1EF3 (LATIN SMALL LETTER Y WITH GRAVE)


- 0x2122 (TRADE MARK SIGN)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vertical-metrics">googlefonts/vertical_metrics</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoLineGap is &quot;33&quot; it should be 0</p>
 [code: bad-OS/2.sTypoLineGap]



* 🔥 **FAIL** <p>hhea.lineGap is &quot;17&quot; it should be 0</p>
 [code: bad-hhea.lineGap]



* ⚠️ **WARN** <p>We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.538x (1538)</p>
 [code: bad-hhea-range]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check mark characters are in GDEF mark glyph class. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-gdef-mark-chars">opentype/gdef_mark_chars</a></summary>
    <div>







* ⚠️ **WARN** <p>The following mark characters could be in the GDEF mark glyph class:
uni034F (U+034F) and uni20DD (U+20DD)</p>
 [code: mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check glyphs in mark glyph class are non-spacing. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-gdef-spacing-marks">opentype/gdef_spacing_marks</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs seem to be spacing (because they have width &gt; 0 on the hmtx table) so they may be in the GDEF mark glyph class by mistake, or they should have zero width instead:
acutecomb (U+0301), gravecomb (U+0300), uni0311 (U+0311), uni033E (U+033E), uni0483 (U+0483), uni0486 (U+0486), uni0487 (U+0487), uni2DE1 (U+2DE1), uni2DE10487 (U+F4E1), uni2DE2 (U+2DE2), uni2DE20487 (U+F4E2), uni2DE3 (U+2DE3), uni2DE4 (U+2DE4), uni2DE5 (U+2DE5), uni2DE9 (U+2DE9), uni2DE90487 (U+F4E9), uni2DEA (U+2DEA), uni2DEA0487 (U+F4EA), uni2DEC (U+2DEC), uni2DEC0487 (U+F4EC), uni2DED (U+2DED), uni2DED0487 (U+F4ED), uni2DEF (U+2DEF), uni2DF1 (U+2DF1), uni2DF10487 (U+F4F1), uniE000 (U+E000), uniE001 (U+E001), uniE002 (U+E002), uniE003 (U+E003) and uniE004 (U+E004)</p>
 [code: spacing-mark-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if uppercase glyphs are vertically centered. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#caps-vertically-centered">caps_vertically_centered</a></summary>
    <div>







* ⚠️ **WARN** <p>Uppercase glyphs are not vertically centered in the em box.</p>
 [code: vertical-metrics-not-centered]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: uni0000	Contours detected: 5	Expected: 0

- Glyph name: asterisk	Contours detected: 2	Expected: 1 or 4

- Glyph name: ydieresis	Contours detected: 2	Expected: 3

- Glyph name: afii10025	Contours detected: 2	Expected: 1

- Glyph name: afii10070	Contours detected: 1	Expected: 2

- Glyph name: afii10076	Contours detected: 2	Expected: 1

- Glyph name: uni0450	Contours detected: 2	Expected: 3

- Glyph name: uni0451	Contours detected: 3	Expected: 4

- Glyph name: uni0456	Contours detected: 1	Expected: 2

- Glyph name: uni045C	Contours detected: 3	Expected: 2

- Glyph name: uni046E	Contours detected: 1	Expected: 2

- Glyph name: uni046F	Contours detected: 1	Expected: 2

- Glyph name: uni0473	Contours detected: 2	Expected: 3

- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

- Glyph name: asterisk	Contours detected: 2	Expected: 1 or 4

- Glyph name: uni0450	Contours detected: 2	Expected: 3

- Glyph name: uni0451	Contours detected: 3	Expected: 4

- Glyph name: uni0456	Contours detected: 1	Expected: 2

- Glyph name: uni045C	Contours detected: 3	Expected: 2

- Glyph name: uni046E	Contours detected: 1	Expected: 2

- Glyph name: uni046F	Contours detected: 1	Expected: 2

- Glyph name: uni0473	Contours detected: 2	Expected: 3

- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

- Glyph name: ydieresis	Contours detected: 2	Expected: 3
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#math-signs-width">math_signs_width</a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 579 among a set of 3 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 453:
plus</p>
<p>Width = 611:
less</p>
<p>Width = 376:
equal</p>
<p>Width = 600:
greater</p>
<p>Width = 399:
logicalnot</p>
<p>Width = 330:
minus</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-hyphen">soft_hyphen</a></summary>
    <div>







* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure Stylistic Sets have description. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#stylisticset-description">stylisticset_description</a></summary>
    <div>







* ⚠️ **WARN** <p>The stylistic set ss01 lacks a description string on the 'name' table.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+007F : try adding symbols</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, canadian-aboriginal, todhri, duployan, hebrew, tai-le, tifinagh, math, syriac, coptic, old-permic</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding one of: todhri, coptic</li>
<li>U+033E COMBINING VERTICAL TILDE: not included in any glyphset definition</li>
<li>U+034F COMBINING GRAPHEME JOINER: not included in any glyphset definition</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: malayalam, tirhuta, new-tai-lue, warang-citi, tai-tham, syloti-nagri, tai-le, lao, lepcha, hatran, sundanese, chakma, tamil, khojki, khmer, myanmar, siddham, mandaic, oriya, hanifi-rohingya, khudawadi, grantha, cham, gunjala-gondi, pahawh-hmong, saurashtra, kayah-li, mongolian, buhid, zanabazar-square, javanese, psalter-pahlavi, hanunoo, sinhala, tagbanwa, rejang, manichaean, kharoshthi, arabic, duployan, kaithi, limbu, devanagari, tibetan, tifinagh, bengali, meetei-mayek, bhaiksuki, nko, syriac, tagalog, phags-pa, tai-viet, buginese, telugu, sogdian, yi, mahajani, kannada, takri, hebrew, newa, thaana, gurmukhi, brahmi, gujarati, dogra, modi, batak, thai, avestan, balinese, sharada, masaram-gondi</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: malayalam, tirhuta, new-tai-lue, warang-citi, tai-tham, syloti-nagri, tai-le, lao, lepcha, sundanese, tamil, chakma, khojki, khmer, myanmar, old-hungarian, mandaic, siddham, oriya, hanifi-rohingya, khudawadi, grantha, cham, gunjala-gondi, pahawh-hmong, saurashtra, kayah-li, mongolian, buhid, zanabazar-square, javanese, psalter-pahlavi, hanunoo, sinhala, tagbanwa, rejang, manichaean, kharoshthi, arabic, duployan, kaithi, limbu, devanagari, tibetan, tifinagh, bengali, meetei-mayek, bhaiksuki, nko, syriac, tagalog, phags-pa, tai-viet, buginese, telugu, sogdian, yi, mahajani, kannada, takri, hebrew, newa, thaana, gurmukhi, brahmi, gujarati, dogra, modi, batak, thai, avestan, balinese, sharada, masaram-gondi</li>
<li>U+2010 HYPHEN: try adding one of: kharoshthi, sora-sompeng, cham, arabic, hebrew, kaithi, syloti-nagri, sundanese, kayah-li, armenian, lisu, coptic, yi</li>
<li>U+2011 NON-BREAKING HYPHEN: try adding one of: syloti-nagri, yi, arabic</li>
<li>U+2012 FIGURE DASH: not included in any glyphset definition</li>
<li>U+2024 ONE DOT LEADER: try adding armenian</li>
<li>U+2025 TWO DOT LEADER: try adding phags-pa</li>
<li>U+2027 HYPHENATION POINT: not included in any glyphset definition</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, phags-pa, mongolian</li>
<li>U+203B REFERENCE MARK: not included in any glyphset definition</li>
<li>U+2056 THREE DOT PUNCTUATION: try adding coptic</li>
<li>U+2058 FOUR DOT PUNCTUATION: try adding coptic</li>
<li>U+2059 FIVE DOT PUNCTUATION: try adding coptic</li>
<li>U+205C DOTTED CROSS: not included in any glyphset definition</li>
<li>U+205D TRICOLON: try adding one of: meroitic, old-hungarian, carian, meroitic-hieroglyphs</li>
<li>U+205E VERTICAL FOUR DOTS: try adding old-hungarian</li>
<li>U+2060 WORD JOINER: not included in any glyphset definition</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+20DD COMBINING ENCLOSING CIRCLE: try adding symbols</li>
<li>U+2219 BULLET OPERATOR: try adding one of: tai-tham, math, symbols, yi</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: wancho, new-tai-lue, ahom, lepcha, chakma, khojki, elbasan, myanmar, old-permic, khudawadi, zanabazar-square, hanunoo, kaithi, devanagari, tifinagh, nko, telugu, yi, adlam, hebrew, music, newa, thaana, thai, tagbanwa, sharada, malayalam, tirhuta, canadian-aboriginal, lao, sundanese, marchen, mandaic, siddham, cham, kayah-li, mongolian, rejang, bengali, tagalog, sogdian, takri, gurmukhi, batak, balinese, bassa-vah, tai-tham, tamil, khmer, mende-kikakui, hanifi-rohingya, oriya, miao, pahawh-hmong, osage, javanese, sinhala, kharoshthi, duployan, tibetan, armenian, syriac, tai-viet, buginese, mahajani, kannada, symbols, gujarati, warang-citi, syloti-nagri, tai-le, caucasian-albanian, soyombo, grantha, gunjala-gondi, saurashtra, math, buhid, coptic, psalter-pahlavi, manichaean, limbu, meetei-mayek, bhaiksuki, phags-pa, brahmi, modi, dogra, masaram-gondi</li>
<li>U+2626 ORTHODOX CROSS: try adding symbols</li>
<li>U+2720 MALTESE CROSS: try adding symbols</li>
<li>U+2E2F VERTICAL TILDE: not included in any glyphset definition</li>
<li>U+E000 : not included in any glyphset definition</li>
<li>U+E001 : not included in any glyphset definition</li>
<li>U+E002 : not included in any glyphset definition</li>
<li>U+E003 : not included in any glyphset definition</li>
<li>U+E004 : not included in any glyphset definition</li>
<li>U+E005 : not included in any glyphset definition</li>
<li>U+E0E2 : not included in any glyphset definition</li>
<li>U+E0E4 : not included in any glyphset definition</li>
<li>U+E2EA : not included in any glyphset definition</li>
<li>U+E8E2 : not included in any glyphset definition</li>
<li>U+E8E4 : not included in any glyphset definition</li>
<li>U+E8E5 : not included in any glyphset definition</li>
<li>U+E904 : not included in any glyphset definition</li>
<li>U+E90A : not included in any glyphset definition</li>
<li>U+E90B : not included in any glyphset definition</li>
<li>U+F4E1 : not included in any glyphset definition</li>
<li>U+F4E2 : not included in any glyphset definition</li>
<li>U+F4E9 : not included in any glyphset definition</li>
<li>U+F4EA : not included in any glyphset definition</li>
<li>U+F4EC : not included in any glyphset definition</li>
<li>U+F4ED : not included in any glyphset definition</li>
<li>U+F4F1 : not included in any glyphset definition</li>
<li>U+1F540 CIRCLED CROSS POMMEE: try adding symbols</li>
<li>U+1F541 CROSS POMMEE WITH HALF-CIRCLE BELOW: try adding symbols</li>
<li>U+1F542 CROSS POMMEE: try adding symbols</li>
<li>U+1F543 NOTCHED LEFT SEMICIRCLE WITH THREE DOTS: try adding symbols</li>
<li>U+1F544 NOTCHED RIGHT SEMICIRCLE WITH THREE DOTS: try adding symbols</li>
<li>U+1F545 SYMBOL FOR MARKS CHAPTER: try adding symbols</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic</code>, <code>cyrillic-ext</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: j̀ j́ j̈ j̑ і́</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ĭ i̇ ȉ ȋ i̾ i҃ i҆ i҇ iⷡ iⷢ iⷣ iⷤ iⷥ iⷩ iⷪ iⷬ iⷭ iⷮ iⷯ iⷱ</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-colinear-vectors">outline_colinear_vectors</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* Z (U+005A): L&lt;&lt;187.0,38.0&gt;--&lt;189.0,38.0&gt;&gt; -&gt; L&lt;&lt;189.0,38.0&gt;--&lt;382.0,42.0&gt;&gt;

* u1F545 (U+1F545): L&lt;&lt;508.0,838.0&gt;--&lt;514.0,863.0&gt;&gt; -&gt; L&lt;&lt;514.0,863.0&gt;--&lt;519.0,898.0&gt;&gt;

* uni040E (U+040E): L&lt;&lt;262.0,293.0&gt;--&lt;257.0,169.0&gt;&gt; -&gt; L&lt;&lt;257.0,169.0&gt;--&lt;253.0,82.0&gt;&gt;

* uni0423 (U+0423): L&lt;&lt;262.0,293.0&gt;--&lt;257.0,169.0&gt;&gt; -&gt; L&lt;&lt;257.0,169.0&gt;--&lt;253.0,82.0&gt;&gt;

* uni1C85 (U+1C85): L&lt;&lt;347.0,0.0&gt;--&lt;344.0,353.0&gt;&gt; -&gt; L&lt;&lt;344.0,353.0&gt;--&lt;344.0,371.0&gt;&gt;

* uni203B (U+203B): L&lt;&lt;295.0,340.0&gt;--&lt;339.0,383.0&gt;&gt; -&gt; L&lt;&lt;339.0,383.0&gt;--&lt;382.0,425.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* afii10021 (U+0414): L&lt;&lt;260.0,18.0&gt;--&lt;260.0,327.0&gt;&gt;/B&lt;&lt;260.0,327.0&gt;-&lt;255.0,306.0&gt;-&lt;245.0,285.5&gt;&gt; = 13.392497753751098
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-semi-vertical">outline_semi_vertical</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* N (U+004E): L&lt;&lt;556.0,185.0&gt;--&lt;554.0,514.0&gt;&gt;

* Ntilde (U+00D1): L&lt;&lt;556.0,185.0&gt;--&lt;554.0,514.0&gt;&gt;

* T (U+0054): L&lt;&lt;350.0,504.0&gt;--&lt;352.0,124.0&gt;&gt;

* afii10086 (U+0444): L&lt;&lt;326.0,509.0&gt;--&lt;327.0,745.0&gt;&gt;

* afii10086 (U+0444): L&lt;&lt;330.0,9.0&gt;--&lt;328.0,466.0&gt;&gt;

* afii10086 (U+0444): L&lt;&lt;438.0,753.0&gt;--&lt;436.0,500.0&gt;&gt;

* e (U+0065): L&lt;&lt;385.0,256.0&gt;--&lt;119.0,258.0&gt;&gt;

* eacute (U+00E9): L&lt;&lt;385.0,256.0&gt;--&lt;119.0,258.0&gt;&gt;

* ecircumflex (U+00EA): L&lt;&lt;385.0,256.0&gt;--&lt;119.0,258.0&gt;&gt;

* edieresis (U+00EB): L&lt;&lt;385.0,256.0&gt;--&lt;119.0,258.0&gt;&gt;

* egrave (U+00E8): L&lt;&lt;385.0,256.0&gt;--&lt;119.0,258.0&gt;&gt;

* onequarter (U+00BC): L&lt;&lt;216.0,635.0&gt;--&lt;215.0,361.0&gt;&gt;

* uni1C85 (U+1C85): L&lt;&lt;347.0,0.0&gt;--&lt;344.0,353.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vendor-id">googlefonts/vendor_id</a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value '    ' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 1 | 0 | 8 | 15 | 108 | 6 | 98 | 0 | 
| 0% | 0% | 3% | 6% | 46% | 3% | 42% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
