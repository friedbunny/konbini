# konbini

## use

The CSV file contains the barest essentials — chain, location name, latitude & longitude — while the SQLite database includes the raw information (which can and does differ between different chains, based on availability).

Example CSV field: `7-11,"富山城址公園前",36.6915631,137.2129004`

A recommended SQLite database client for Mac is [Base](http://menial.co.uk/base/).

##coverage

47477 locations are included in the CSV file. This includes every major chain and minor or regional ones where available:

- Lawson
  - Natural Lawson
  - Lawson 100 (defunct)
- Seven-Eleven
- FamilyMart
  - Tomony
  - Famima!!
- Circle K & Sunkus
- Daily Yamazaki
- Ministop
- Poplar
  - Kurashi House
  - Gran Merci (グランメルシー)
  - Three Eight (スリーエイト)
  - ハイウェイ彩家
- Seicomart
- Everyone
  - RIC Mart
  - Coco

The database includes locations that failed geocoding or otherwise aren't entirely certain.

If you have chain you'd like to suggest, feel free to open an issue with a link to their website's store listing.

## accuracy

These locations were taken from chain websites and generally represents where they say their stores are. Frankly, this isn't always entirely accurate or ideally placed, but I have made no effort to manually correct them. Seven-Eleven locations may be shifted slightly due to the conversion between datums (see below).

## future

I intend to post logo assets for the konbini included herein, especially as I've been lucky enough to find or create vectors for most. Once updated, I would also like to pursue some way of putting these points on [Open Street Map](https://www.openstreetmap.org), perhaps using a tool such as [To-Fix](https://github.com/osmlab/to-fix), provided scaped data fits [the OSM license](https://www.openstreetmap.org/copyright).

## backstory

Living in the snowy wasteland of Toyama, my annual hibernation project for the winter of 2012-13 was to scrape and format as many convenience store locations as I could. Did you know that there is a [Japanese Geodetic Datum](http://www.gsi.go.jp/ENGLISH/page_e30030.html) ([日本測地系](http://ja.wikipedia.org/wiki/測地系#.E6.97.A5.E6.9C.AC.E3.81.AE.E6.B8.AC.E5.9C.B0.E7.B3.BB.EF.BC.9A.E4.B8.96.E7.95.8C.E6.B8.AC.E5.9C.B0.E7.B3.BB.E3.81.A8.E6.97.A5.E6.9C.AC.E6.B8.AC.E5.9C.B0.E7.B3.BB)) that some companies use for web maps? Several datums, in fact! Were to you aware that, despite a façade of techno-prowess, Japan is perpetually 5–10 years behind in most design and web trends? Oh, the hotdog stand color schemes and stock typefaces! And so on and so forth — innumerable were the curiosities and mysteries that filled the stunted, biting days of that winter.
