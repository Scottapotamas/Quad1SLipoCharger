# Quad1SLipoCharger
Charges up to 4 1S lipo batteries, independantly. Settable 300, 500 or 800mA charge current per battery.

# Version 2.0
Version 2.0 was the first variant that uses the STC08 IC for charging, as it offers better performance and programmable current limits which the older MAX charging IC didn't on V1.

A few of these V2 boards were made as a test, and performed very well charging 4 batteries in the field for micro brushed quads. 

The biggest issue has been the physical connectors to the batteries, given the multitude of competing battery connectors used on brushed aircraft. V2.0 used JST-PH and then adaptor cables I made up, but this doesn't suit the fully range as easily as hoped.

That said, two of these prototype boards have charged over 100 batteries with no issues, and charging/regulation seems safe, stable and reliable.

# Version 2.1

Having tested V2 in person some changes were made which are represented in V2.1, mainly increased thermal considerations, removal of some status leds, and simplification of the layout. 

Connectors were changed to be compatible with the smaller 1S batteries found on TinyWhoop/RTF planes, and rotated to allow for direct connections to the board.

The board was also shrunk, and the XT60 footprint corrected based on discoveries relating to incorrect datasheets used for V2.0 footprint design.
