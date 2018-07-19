# Translation files for R-Instat

## How to contribute to translations

1. Download the .xlf from this repository for the language you want to translate.
2. Download and install the Multilingual App Toolkit from here https://developer.microsoft.com/en-us/windows/develop/multilingual-app-toolkit
3. Open the xlf file with the Multilingual App Toolkit
4. In the bottom left corner click "Strings" to see all the translation items.
5. The file contains many items that should not be translated e.g. locations so you will need to filter to only show items that should be translated. To do this click the "Filter" tab on the menu bar. Enter ".Text" and uncheck "Source" and "Translation" and click "Apply". You will now see only resources where the ID column contains ".Text" i.e. items that should be translated. **It is important that you only change items which have a ".Text" ID value.**
6. Select the item you want to modify and type into the large Translation textbox above to make your changes.
7. When you've finished making changes, send the file back to us at r-instat(at)africanmathsinitiative.net. (Do not make a pull request to this repository as translations are incorporated into R-Instat directly and not through this file.) 
8. Once reviewed, your changes will appear in the next release of R-Instat!

You can also use the filter in other ways to search for specific items e.g. "mnu" will show the main menu items.

For questions or discussions on this translation process or to make a suggestion without editing the xlf file, feel free to open an issue on this repository.

Check the repository regularly for the most up to date versions of the xlf files.
