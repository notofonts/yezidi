## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[8] NotoSerifYezidi[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 579:
minus</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSerifYezidi/googlefonts/variable-ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, math, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: math, tai-le, malayalam, duployan, tifinagh, syriac, hebrew, canadian-aboriginal, coptic, todhri, old-permic</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: ahom, warang-citi, thai, oriya, music, lepcha, mahajani, old-permic, balinese, saurashtra, elbasan, grantha, kannada, khudawadi, newa, duployan, yi, brahmi, tifinagh, phags-pa, tai-tham, adlam, sharada, mongolian, bassa-vah, nko, chakma, manichaean, masaram-gondi, kaithi, hanifi-rohingya, wancho, armenian, meetei-mayek, new-tai-lue, javanese, caucasian-albanian, mende-kikakui, sundanese, bhaiksuki, kharoshthi, modi, myanmar, soyombo, khojki, zanabazar-square, syloti-nagri, mandaic, gurmukhi, tai-le, syriac, devanagari, thaana, psalter-pahlavi, cham, marchen, tamil, siddham, gunjala-gondi, tagbanwa, rejang, batak, lao, osage, miao, pahawh-hmong, buhid, tirhuta, telugu, tagalog, bengali, coptic, dogra, sogdian, symbols, hebrew, sinhala, limbu, gujarati, math, buginese, kayah-li, canadian-aboriginal, khmer, hanunoo, takri, malayalam, tibetan, tai-viet</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code>, <code>yezidi</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Heiltsuk (Latn, 300 speakers), Ngbaka (Latn, 1,020,000 speakers), Dan (Latn, 1,099,244 speakers), Avokaya (Latn, 100,000 speakers), South Central Banda (Latn, 244,000 speakers), Nzakara (Latn, 50,000 speakers), Ekpeye (Latn, 226,000 speakers), Yala (Latn, 200,000 speakers), Nateni (Latn, 100,000 speakers), Koonzime (Latn, 40,000 speakers), Lugbara (Latn, 2,200,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Aghem (Latn, 38,843 speakers), Mundani (Latn, 34,000 speakers), Kaska (Latn, 125 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Cicipu (Latn, 44,000 speakers), Gulay (Latn, 250,478 speakers), Ma’di (Latn, 584,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Bete-Bendi (Latn, 100,000 speakers), Sar (Latn, 500,000 speakers), Dii (Latn, 71,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Igbo (Latn, 27,823,640 speakers), Han (Latn, 6 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Bafut (Latn, 158,146 speakers), Southern Kisi (Latn, 360,000 speakers), Mfumte (Latn, 79,000 speakers), Makaa (Latn, 221,000 speakers), Navajo (Latn, 166,319 speakers), Fur (Latn, 1,230,163 speakers), Zapotec (Latn, 490,000 speakers), Ejagham (Latn, 120,000 speakers), Ebira (Latn, 2,200,000 speakers), Basaa (Latn, 332,940 speakers), Mango (Latn, 77,000 speakers), Kom (Latn, 360,685 speakers), Vute (Latn, 21,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* peyezi (U+10E82): X=90.0,Y=-293.0 (should be at descender -292?)

* peyezi (U+10E82): X=268.0,Y=2.0 (should be at baseline 0?)

* peyezi (U+10E82): X=398.0,Y=1.0 (should be at baseline 0?)

* pheyezi (U+10E83): X=254.5,Y=1.0 (should be at baseline 0?)

* zalyezi (U+10E8C): X=92.0,Y=-293.0 (should be at descender -292?)

* zalyezi (U+10E8C): X=97.0,Y=-293.0 (should be at descender -292?)

* sinyezi (U+10E91): X=67.0,Y=1.0 (should be at baseline 0?)

* sinyezi (U+10E91): X=320.0,Y=1.0 (should be at baseline 0?)

* tayezi (U+10E95): X=284.0,Y=-293.0 (should be at descender -292?)

* tayezi (U+10E95): X=289.0,Y=-293.0 (should be at descender -292?)

* qafyezi (U+10E9C): X=231.0,Y=-293.0 (should be at descender -292?)

* qafyezi (U+10E9C): X=263.0,Y=-293.0 (should be at descender -292?)

* kafyezi (U+10E9D): X=372.0,Y=-293.0 (should be at descender -292?)

* kafyezi (U+10E9D): X=378.0,Y=-293.0 (should be at descender -292?)

* khafyezi (U+10E9E): X=372.0,Y=-293.0 (should be at descender -292?)

* khafyezi (U+10E9E): X=378.0,Y=-293.0 (should be at descender -292?)

* yotyezi (U+10EA8): X=411.0,Y=-293.0 (should be at descender -292?)

* yotyezi (U+10EA8): X=416.0,Y=-293.0 (should be at descender -292?)

* etyezi (U+10EA9): X=411.0,Y=-293.0 (should be at descender -292?)

* etyezi (U+10EA9): X=416.0,Y=-293.0 (should be at descender -292?)

* yotCircumyezi (U+10EB1): X=411.0,Y=-293.0 (should be at descender -292?)

* yotCircumyezi (U+10EB1): X=416.0,Y=-293.0 (should be at descender -292?)

* hamzayezi (U+10EAB): X=-44.0,Y=712.0 (should be at cap-height 714?)

* hamzayezi (U+10EAB): X=42.0,Y=716.0 (should be at cap-height 714?)

* uni061F (U+061F): X=149.5,Y=1.5 (should be at baseline 0?)

* G (U+0047): X=519.0,Y=1.5 (should be at baseline 0?)

* Gbreve (U+011E): X=519.0,Y=1.5 (should be at baseline 0?)

* uni0122 (U+0122): X=519.0,Y=1.5 (should be at baseline 0?)

* Gdotaccent (U+0120): X=519.0,Y=1.5 (should be at baseline 0?)

* Oslash (U+00D8): X=454.5,Y=715.5 (should be at cap-height 714?)

* a (U+0061): X=182.0,Y=536.5 (should be at x-height 536?)

* c (U+0063): X=360.0,Y=535.0 (should be at x-height 536?)

* comma (U+002C): X=114.0,Y=1.0 (should be at baseline 0?)

* g (U+0067): X=161.0,Y=-0.5 (should be at baseline 0?)

* gbreve (U+011F): X=161.0,Y=-0.5 (should be at baseline 0?)

* uni0123 (U+0123): X=161.0,Y=-0.5 (should be at baseline 0?)

* gdotaccent (U+0121): X=161.0,Y=-0.5 (should be at baseline 0?)

* nine (U+0039): X=139.0,Y=2.0 (should be at baseline 0?)

* parenleft (U+0028): X=314.0,Y=715.0 (should be at cap-height 714?)

* parenright (U+0029): X=32.0,Y=715.0 (should be at cap-height 714?)

* q (U+0071): X=412.5,Y=0.5 (should be at baseline 0?)

* quotedblbase (U+201E): X=314.0,Y=1.0 (should be at baseline 0?)

* quotedblbase (U+201E): X=114.0,Y=1.0 (should be at baseline 0?)

* quotedblleft (U+201C): X=420.0,Y=715.0 (should be at cap-height 714?)

* quotedblleft (U+201C): X=220.0,Y=715.0 (should be at cap-height 714?)

* quoteleft (U+2018): X=220.0,Y=715.0 (should be at cap-height 714?)

* quotesinglbase (U+201A): X=114.0,Y=1.0 (should be at baseline 0?)

* section (U+00A7): X=101.0,Y=2.0 (should be at baseline 0?)

* semicolon (U+003B): X=132.0,Y=1.0 (should be at baseline 0?)

* sterling (U+00A3): X=77.0,Y=1.0 (should be at baseline 0?)

* three (U+0033): X=334.5,Y=1.0 (should be at baseline 0?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have a counter-clockwise outer contour:</p>
<pre><code>* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour
</code></pre>
 [code: ccw-outer-contour]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 1 | 7 | 97 | 7 | 139 | 0 | 
| 0% | 0% | 0% | 3% | 39% | 3% | 55% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
