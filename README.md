# Wikipedia dumps parsing and basic cleaning

 The codes in this repository allow to parse Wikipedia dump files (in XML format) and perform the basic cleaning of the text.

<p>&nbsp;</p>

### Downloading and parsing Wiki dumps
 __parse_wiki_dumps.ipynb__ downloads Wikipedia dump files (in XML format), parse them, extract titles and the textual content of the articles and save them in the pandas framework.
This code is a shorten and modified version of the project _"Wikipedia Data Science: Working with the World’s Largest Encyclopedia"_ by Will Koehrsen. Full code for his project with a very clear description can be retrieved from [here](https://github.com/WillKoehrsen/wikipedia-data-science/blob/master/notebooks/Downloading%20and%20Parsing%20Wikipedia%20Articles.ipynb).

<p>&nbsp;</p>

### Basic cleaning of the content
 __basic_cleaning.ipynb__ suggests the most basic cleaning of Wikipedia articles text after __parse_wiki_dumps.ipynb__

<p>&nbsp;</p>

#### Libraries needed:
* requests
* sys
* keras.utils
* xml.sax
* BeautifulSoup
* bz2
* subprocess
* gc
* mwparsefromhell
* pandas
