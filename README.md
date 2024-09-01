# Munsell Re-renotation: Revised
A revised version of the psychophysical color difference Munsell Re-renotation dataset.

The dataset originates from a conference paper:
*Nikolaev, D., Basova, O., Usaev, G., Tchobanou, M., & Bozhkova, V. (2023, June). Detection and Correction of Errors in Psychophysical Color Difference Munsell Re-renotation Dataset. In London Imaging Meeting (Vol. 4, pp. 40-44). Society for Imaging Science and Technology. https://doi.org/10.2352/lim.2023.4.1.10*

Munsell Re-renotation is a psychophysical dataset describing large color differences, featuring 2986 colors characterized by standard colorimetric coordinates (x, y, Y) and coordinates within the Munsell system (H, V, C). 
The Munsell Re-renotation iteration enhances the uniformity of the system compared to its predecessor, the Munsell Renotation dataset.

The original Munsell Re-renotation data exists as a scanned report, accessible at this  http://www.rit-mcsl.org/MunsellRenotation/MunsellRe-renotations.pdf 

Within this repository, you will find the Munsell Re-renotation data converted into a machine-readable format (.csv), accompanied by three revised versions:
(1) Corrected Misprints (35 items): This version rectifies 35 misprints identified during the initial round of corrections from the scanned report.
(2) Excluded Ambiguous and Duplicate Colors (5 Items): Ambiguous and duplicate colors, totaling 5 items, have been excluded from this version.
(3) Additional Misprints Corrections (39 Items): Incorporating 39 additional misprints corrections identified during a subsequent review, along with 8 revised corrections from the initial iteration.

Additionally, the repository includes Munsell Renotation data sourced from [https://www.rit.edu/science/munsell-color-science-lab-educational-resources](https://www.rit.edu/science/munsell-color-science-lab-educational-resources) (file real.dat), converted to .csv format for ease of use.

Repository Contents:
- `/README.md`: this file
- `/munsell_2-0.csv`: Munsell Renotation data containing real colors only, i.e., within the Macadam limits, sourced from the [RIT website](https://www.rit.edu/science/munsell-color-science-lab-educational-resources) (file real.dat converted to .csv format).
- `/munsell_3-0.csv`: Original Munsell Re-renotation data from [the report](http://web.archive.org/web/20210901124224/http://www.rit-mcsl.org/MunsellRenotation/MunsellRe-renotations.pdf), featuring 2986 colors.
- `/munsell_3-1-0.csv`: Munsell Re-renotation data with 35 corrected erroneous colors (2965 colors).
- `/munsell_3-1-1.csv`: Munsell Re-renotation data with 35 corrected erroneous colors, excluding 4 ambiguous colors and 1 duplicate color (2960 colors).
- `/munsell_3-2.csv`: Munsell Re-renotation data incorporating a total of 74 corrected erroneous colors from munsell_3-0.csv (2964 colors). Note that corrections applied resulted in the removal of one color from the dataset.

All data within this repository are available under the Creative Commons Attribution-NonCommercial-ShareAlike (CC BY-NC-SA 4.0) license. For more information, refer to the license at https://creativecommons.org/licenses/by-nc-sa/4.0.
