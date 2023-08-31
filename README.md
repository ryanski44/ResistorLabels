# ResistorLabels

This script generates labels for resistor and inductor zip bags.

It is meant for AVERY 5260 or AVERY L7157 labels and 7x10cm (3"x4") zip bags.

The generated labels for resistors include:

-   Resistor value
-   4- and 5-band color codes
-   3- and 4-digit smd codes
-   EIA-96 smd code

<img src="Example.svg">

The generated labels for inductors include:

-   Inductor value
-   4-band color codes
-   3-digit smd codes

# Usage

-   Install python3
-   Install the python3 library `reportlab`. This library is used to do the actual PDF generation.
-   Add your own required resistor values in `main()` of `LabelGenerator.py`.
-   If using Avery L7157, change the `layout` value in `main()` to `AVERY_L7157`.
-   Run the script `LabelGenerator.py`!

It will now generate a `ResistorLabels.pdf` that can be used to print onto AVERY 5260/L7157.

-   Add your own required inductor values in `main()` of `InductorGenerator.py`.
-   If using Avery L7157, change the `layout` value in `main()` to `AVERY_L7157`.
-   Run the script `InductorGenerator.py`!

It will now generate a `InductorLabels.pdf` that can be used to print onto AVERY 5260/L7157.

# More Details

This is forked from https://github.com/Finomnis/ResistorLabels and has been modified to generate inductor labels as well as resistor labels

This is based on an idea from Zach Poff.

For more details on how to use these labels, visit his website:

https://www.zachpoff.com/resources/quick-easy-and-cheap-resistor-storage/
