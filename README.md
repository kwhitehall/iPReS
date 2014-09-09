iPReS
=====

<img src="http://podaac.jpl.nasa.gov/sites/default/files/image/custom_thumbs/podaac_logo.png" align="centre" width="300" />

#Introduction

The Internationalization (i18n) Product Retrieval Service is a web service and client providing 
i18n-type access to products and product metadata contained within [NASA JPL's](http://www.jpl.nasa.gov/) 
[Physical Oceanography Distributed Active Archive Center](http://podaac.jpl.nasa.gov/) otherwise known as 
PO.DAAC.

The software implements a [RESTful](http://en.wikipedia.org/wiki/Representational_state_transfer) 
[Apache CXF](http://cxf.apache.org) web-service and client to obtain data from the [PO.DAAC 
Web-Services API](http://podaac.jpl.nasa.gov/ws/index.html). It then translates the product metadata into 
a target language provided along with the intial call to the service. 

#Supported Product Translations

Currently products retrieved from PO.DAAC can be translated to the following languages:

 * ar == Arabic
 * bg == Bulgarian
 * ca == Catalan
 * zh-CHS == Chinese Simplified
 * zh-CHT == Chinese Traditional
 * cs == Czech
 * da == Danish
 * nl == Dutch
 * en == English
 * et == Estonian
 * fi == Finnish
 * fr == French
 * de == German
 * el == Greek
 * ht == Haitian Creole
 * he == Hebrew
 * hi == Hindi
 * mww == Hmong Daw
 * hu == Hungarian
 * id == Indonesian
 * it == Italian
 * ja == Japanese
 * tlh == Klingon
 * tlh-Qaak == Klingon (pIqaD)
 * ko == Korean
 * lv == Latvian
 * lt == Lithuanian
 * ms == Malay
 * mt == Maltese
 * no == Norwegian
 * fa == Persian
 * pl == Polish
 * pt == Portuguese
 * ro == Romanian
 * ru == Russian
 * sk == Slovak
 * sl == Slovenian
 * es == Spanish
 * sv == Swedish
 * th == Thai
 * tr == Turkish
 * uk == Ukrainian
 * ur == Urdu
 * vi == Vietnamese
 * cy == Welsh
 
= License =
iPReS is licnesed under the [Apache Software License v2.0](http://www.apache.org/licenses/LICENSE-2.0).
