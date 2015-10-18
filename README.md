# MinimOSD_MK2
MinimOSD made smaller with better pinout and USB.
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

## Configuration

There are four jumpers that are useful for configuration.

Two are sets of three pads labeled `12-5`.  The one closest to the
`IN` pad sets the camera voltage.  Shorting the two pads on the `12`
side sends 12V to the camera, and the two closest to the `5` side
sends 5V to the camera.  The one nearest the `OUT` pad is the same for
the VTX.

On the same side, there's an `GND` jumper which configures a common
ground for the OSD itself and the video.

On the other side, there's one labeled `+V` which jumps the 5V input
pins so you can have a single 5V input that is used for both outputs
and operating the OSD itself.

## BOM

* [D1, D2, D3 - 3x 0603 LED](http://www.digikey.com/product-detail/en/APT1608SGC/754-1121-1-ND/1747838)
* [D5 - 0805 Schottky](http://www.digikey.com/product-detail/en/SD0805S040S0R5/478-7802-1-ND/3749494)
* [IC4 - MAX7456EUI+](http://www.aliexpress.com/item/5pcs-lot-MAX7456EUI-MAX7456-TSSOP-28-100-NEW-Free-Shipping/32379979937.html)
* [U1 - Atmega 328P AU](http://www.digikey.com/product-detail/en/0/ATMEGA328P-AU-ND)
* [U2 - 0603 1k Resistor Array](http://www.mouser.com/Search/ProductDetail.aspx?R=CRA06S0831K00FTAvirtualkey61300000virtualkey71-CRA06S08031001FR) OR [digikey](http://www.digikey.com/product-detail/en/CRA06S0831K00FTA/CRA6S81.00KACT-ND/2665710)
* [U9 - CP2102](http://www.digikey.com/product-detail/en/0/336-1160-1-ND)
* [C1, C2, C3, C4, C5, C6, C17, C19 - 0603 0.1μF](http://www.digikey.com/product-detail/en/0/490-1532-1-ND/587771)
* [R1, R14 - 0603 10kΩ](http://www.digikey.com/product-detail/en/0/RMCF0603FT10K0CT-ND)
* [Y1 - 16MHz resonator](http://www.digikey.com/product-detail/en/PRQC16.00SR5010X000/478-5420-1-ND/1987419)
* [R2, R3 - 0603 75Ω] (http://www.digikey.com/product-detail/en/RMCF0603FT75R0/RMCF0603FT75R0CT-ND/1942961)
* [C18 - 1μF cap](http://www.digikey.com/product-detail/en/0/1276-1946-1-ND)
* [Q1 - 27MHz resonator](http://www.mouser.com/Search/ProductDetail.aspx?R=XRCGB27M000FAN00R0virtualkey64800000virtualkey81-XRCGB27M000FAN0R0) OR [digikey](http://www.digikey.com/product-detail/en/XRCGB27M000FAN00R0/490-12140-1-ND/5403022)
* [C7, C8 - 0603 4.7μF tantalum cap](http://www.digikey.com/product-detail/en/0/478-8644-1-ND/4005804)
* [J1 - USB micro B](http://www.mouser.com/ProductDetail/Molex/47346-0001/?qs=/ha2pyFaduhPJYReNyhO50y8HO7Ogi%252bBiMiNIuS56C8=) or [digikey](http://www.digikey.com/product-detail/en/0473460001/WM17141CT-ND/1782474)

## Board

![Top](http://i.imgur.com/CR3SLzY.png)

![Bottom](http://i.imgur.com/RqJIqJ9.png)
