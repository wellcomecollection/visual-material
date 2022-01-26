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
| **CAT FORM**                   | lower case i for ISBD punctuation                                                        |

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
**c** = cardboard\
**o** = paper\
See the full list of options [here](https://www.oclc.org/bibformats/en/0xx/007nonproj.html)

**Secondary Support Material**\
Leave blank (code for ‘no secondary support’), unless the mount is of historical, informational, or archival importance

## 008 Date & Country

Select **Ctrl + r** to open the field and edit. Edit each field as follows:

**Date Ent**           catalogued date (YYMMDD).

**Dat Type**          the code for the date can vary, it is generally **s**, but also available:\
&#x20;                         **i =** inclusive dates of a collection\
&#x20;                         **n** = dates unknown\
&#x20;                         **q** = questionable date, exact date unknown, but range of years can be specified.\
&#x20;                         **s** = a single date\
&#x20;                         **t** = a publishing date and a copyright date together (to be entered in this order)\
&#x20;\
**Date One**          the date the artwork was created.\
&#x20;                         if the date is questionable the unknown numeral(s) can be represented by a u

{% hint style="info" %}
For an object known to be created in the 1960s enter the date as **196u**
{% endhint %}

**Date Two**         use for : the copyright date\
&#x20;                                       the final date of a multi-volume set \
&#x20;                                       the original date of publication of a reprint\
&#x20;                                       the later date for a for questionable date.

**Type Mat**          **k** = graphic

**Country**            three letter code for country of publication or creation – see [LC Country Code List](http://www.loc.gov/marc/countries/)\
\
**Language**         three letter code for the language of the item – see [LC Language Code List](http://www.loc.gov/marc/languages/language\_code.html)

**Cat Srce**           **d**
