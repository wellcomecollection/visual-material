---
description: >-
  Language. Location. Cat Date. Date of Creation. Place of Creation. Object
  type. Technique & Materials
---

# Fixed Fields

## Leader Fields

| Populate the following fields: |                                                                                                                       |
| ------------------------------ | --------------------------------------------------------------------------------------------------------------------- |
| **LANG**                       | three letter code for the languge of the item. See [LC Language Codes](https://www.loc.gov/marc/languages/)           |
| SKIP                           | ignore, this will populate automatically                                                                              |
| **LOCATION**                   | **stax** (for closed stores)                                                                                          |
| **CAT DATE**                   | date item was first catalogued. When in the field press T for today's date                                            |
| **BIB LVL**                    | **m** = a single item                                                                                                 |
|                                | **a** = part of an item                                                                                               |
|                                | **c** = collection                                                                                                    |
|                                | **d** = coll. subunit. Use for item part of a larger collection, e.g. Adamson Collection                              |
| **MAT TYPE**                   | **k** = pictures                                                                                                      |
|                                | **r** = 3D objects                                                                                                    |
| **COUNTRY**                    | 3 letter code for the country of publication or creation. See [LC Country Codes](https://www.loc.gov/marc/countries/) |

## MARC Leader Fields

To open the MARC leader press ctrl+r

| Populate the following fields: |                                                                                          |
| ------------------------------ | ---------------------------------------------------------------------------------------- |
| **REC TYP**                    | **k** = pictures (graphic materials)                                                     |
| **BIB LVL**                    | same as preceeding BIB Levl:                                                             |
|                                | **m** = a single whole item                                                              |
|                                | **a** = part of an item, items physically part of a larger resource                      |
|                                | **c** = collection                                                                       |
|                                | **d** = coll. subunit. Use for item part of a larger collection, e.g. Adamson Collection |
| **ENC LEVL**                   |                                                                                          |
| **CAT FORM**                   | i = ISBD punctuation                                                                     |

## 007 Physical Description

Select Ctrl + r to open the field and edit. Double click to open the sub fields to edit.

**Category of Material** (MatCatg) = **k** non-projected graphic\
For 3D objects (MAT Type **r**) fewer options will be offered, code the Spec Mat as **z** unspecified

**Specific Material Designation or Medium** (Spec Mat)\
**c** = Collage\
**d** = Drawing\
**e** = Painting\
**f** = Photomechanical print\
**g** = Photonegative\
**h** = Photoprint\
**i** = Picture\
**j** = Print\
**k** = Poster\
**v** = Photograph

**Colour**\
**a** = One colour monochrome (not photographs)\
**b** = Black & white, used for photographs\
**c** = Multi-coloured\
**h** = Hand-coloured\
**m** = Mixed – the work is a mix of colour characteristics\
**z** = Other – used for stained, tinted and toned items such as sepia photos

**Primary Support Material**\
**a** = canvas\
**o** = paper\
See the full list of options [here](https://www.oclc.org/bibformats/en/0xx/007nonproj.html)

**Secondary Support Material**\
Leave blank (code for ‘no secondary support’), unless the mount is of historical, informational, or archival importance

## 008 Date & Country

Select **Ctrl + r** to open the field and edit. Edit each field as follows:

**Date Ent**           catalogued date (YYMMDD).

**Dat Type**          in most cases the code will be **s**, options include:

**s** = single known or probable date (year)

{% hint style="info" %}
**Dat Type**   s                      for a single known date\
**Date One**   2003\
**264 \_0**       **|c**2003

**Dat Type**   s                      for a single probable date\
**Date One**  1966\
**264 \_0**       **|c**\[1966?]  &#x20;

**Dat Type**   s                      for a single probable date\
**Date One**  19uu\
**264 \_0**       **|c**\[20th century]  &#x20;
{% endhint %}

**t** = a publishing date and a copyright date together (to be entered in this order)

**q** = questionable date, exact date unknown, but range of years can be specified. Put the earliest date in _Date 1_ and the latest in _Date 2_.         &#x20;

{% hint style="info" %}
**Dat Type**   q\
**Date One**  1972\
**Date Two**  1973\
**264 \_0**       **|c**\[1972 or 1973]

**Dat Type**   q\
**Date One**  1921\
**Date Two**  1928\
**264 \_0**       **|c**\[between 1921 and 1973]

**Dat Type**   q                                                                  for a group of objects\
**Date One**  18uu\
**Date Two**  19uu\
**264 \_0**       **|c**\[late 19th and early 20th century]

**Dat Type**   q\
**Date One**  uuuu\
**Date Two**  1960\
**264 \_0**       **|c**\[not after 1960]
{% endhint %}

**n** = dates unknown. Use for _\[date of creation not identified]_ and similar situations, where no other code applies and a reasonable date cannot be determined. Both _Date 1_ and _Date 2_ should be coded _uuuu_

**i =** inclusive dates of a collection. Use for unpublished items that have a range of dates of execution.

For further explanation see [OCLC date types](https://www.oclc.org/bibformats/en/fixedfield/dtst.html)

Dates included in the Fixed field should be led by the [264 field](264-creation-and-copyright.md)\
&#x20;\
**Date One**          the date the artwork was created.\
&#x20;                         for a single probable date (s) enter the probable date, do not use u. \
&#x20;                         for questionable dates (q) represent the unknown numeral(s) with a u  &#x20;

**Date Two**         use for : the copyright date\
&#x20;                                       the final date of a multi-volume set \
&#x20;                                       the original date of publication of a reprint\
&#x20;                                       the later date for a for questionable date.



**Type Mat**          **k** = graphic

**Country**            three letter code for country of publication or creation – see [LC Country Code List](http://www.loc.gov/marc/countries/)\
\
**Language**         three letter code for the language of the item – see [LC Language Code List](http://www.loc.gov/marc/languages/language\_code.html)

**Cat Srce**           **d**
