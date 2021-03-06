# Data Analysis

[BARs][Home] related to analysis of non-image numerical data.

###[Clipboard to Results](./Clipboard_to_Results.py)
   Imports numeric values (delimiter-separated values), copied to the clipboard into the
   _Results_ table. Useful, since BARs that analyze tabular data can only read values from
   the main IJ _Results_ table.
   ([Download .py](./Clipboard_to_Results.py?raw=true))

   See also [Plot Results](#plot-results)


###[Distribution Plotter](./Distribution_Plotter.ijm)
   Plots relative and cumulative frequencies on a double Y-axis graph of a measured parameter.

  1. Retrives relative and cumulative frequencies
  2. Fits a Normal distribution to histogram of relative frequencies
  3. Offers several methods to determine the optimal number of histogram bins: Square root
   (used by e.g., M. Excel), Sturges', Scott's (used by _Analyze>Distribution..._) and
   Freedman–Diaconis'

   ([Download .ijm](./Distribution_Plotter.ijm?raw=true))
   ([Documentation page][DP page])

   [![][DP image]][DP page]


###[Find Peaks](./Find_Peaks.bsh)
   Retrieves local maxima and minima from an ImageJ plot, allowing several filtering
   options such as: 1) Peak amplitude; 2) Peak height and 3) Peak width.

   ([Download .bsh](./Find_Peaks.bsh?raw=true))
   ([Documentation page][FP page])

   [![][FP image]][FP page]


###[Fit Polynomial](./Fit_Polynomial.bsh)
   Fits a polynomial function (of arbitrary degree) to sampled data from an ImageJ plot.
   Features an heuristic algorithm for guessing a polynomial 'best fit'.

   Requires the apache commons math library, distributed with Fiji. Non-Fiji users that do
   not have it installed are provided with a direct download link that will install all
   required dependencies.
   ([Download .bsh](./Fit_Polynomial.bsh?raw=true))

   [![][Poly image]](http://fiji.sc/Sholl_Analysis#Complementary_Tools)


###[Plot Results](./Plot_Results.bsh)
   Routine that creates an XY plot from data in the Results table. Useful for plotting
   data from imported spreadsheets.
   ([Download .bsh](./Plot_Results.bsh?raw=true))

   See also [Clipboard to Results](#clipboard-to-results)


##See Also

* [Analysis], BARs that complement built-in commands in the ImageJ `Analyze>` menu.

[DP page]: http://imagejdocu.tudor.lu/doku.php?id=macro:distribution_plotter
[DP image]: http://imagejdocu.tudor.lu/lib/exe/fetch.php?cache=&media=macro:distributionplotterdemo.png
[FP page]: http://fiji.sc/Find_Peaks
[FP image]: http://fiji.sc/images/a/a1/FindPeaksSnapshot.png
[Poly image]: http://fiji.sc/images/f/f0/AnimatedPolyFit.gif



| [Home] | [Analysis] | [Data Analysis] | [Annotation] | [Segmentation] | [Tools] | [Plugins] | [lib] | [Snippets] | [Fiji] |
|:------:|:----------:|:---------------:|:------------:|:--------------:|:-------:|:---------:|:-----:|:----------:|:------:|

[Home]: https://github.com/tferr/Scripts#ij-bar
[Analysis]: https://github.com/tferr/Scripts/tree/master/Analysis#analysis
[Data Analysis]: https://github.com/tferr/Scripts/tree/master/Data_Analysis#data-analysis
[Annotation]: https://github.com/tferr/Scripts/tree/master/Annotation#annotation
[Segmentation]: https://github.com/tferr/Scripts/tree/master/Segmentation#segmentation
[Morphometry]: https://github.com/tferr/Scripts/tree/master/Morphometry#morphometry
[Tools]: https://github.com/tferr/Scripts/tree/master/Tools#tools-and-toolsets
[Plugins]: https://github.com/tferr/Scripts/tree/master/BAR#bar-plugins
[lib]: https://github.com/tferr/Scripts/tree/master/lib#lib
[Snippets]: https://github.com/tferr/Scripts/tree/master/Snippets#snippets
[Fiji]: http://fiji.sc/BAR
