# Text-mining
The materials and content were used for a session introducing text analysis and mining with tools that do not require programming knowledge or skills. The primary tools we used for pre-processing text, analysis, and visualization include <a href="http://lexos.wheatoncollege.edu/upload" target="_blank">Lexos</a> and <a href="http://voyant-tools.org/" target="_blank">Voyant</a>. 

## Resources:
* TextMiningIntro.pdf - slides with an overview of text mining and analysis, sample projects, and resources 

## Texts for mining and analysis:
For this session we used Anne Brönte’s novel, *Agnes Grey* (1847). This text consists of 25 chapters, approximately 219 pages. This <a href="http://www.gutenberg.org/files/767/767-0.txt " target="_blank">text</a> was downloaded from Project Gutenberg. The main file used for pre-processing is raw_agnesgrey.txt, the scrubbed and modified files are included here as examples of pre-processed files outputted from Lexos. 

* en.txt - text file with English stopwords that can be edited to one's needs (drawn from the <a href="http://mallet.cs.umass.edu/download.php" target="_blank">Mallet 2.0 toolkit</a>)
* raw_agnesgrey.txt - entire raw text of *Agnes Grey*
* scrubbed_agnesgrey.txt - scrubbed text of *Agnes Grey* 
* modified-agnesgrey folder - chunked text of *Agnes Grey* using chapters as milestone

## Pre-Processing your Texts:
1. Download all of the text files 
2. Open the raw_agnesgrey.txt file
    
  * manually or using scripts, remove all of the text that appears above "CHAPTER I" and all of the text that appears after the final sentence
3. Navigate to <a href="http://lexos.wheatoncollege.edu/upload" target="_blank">Lexos</a>
        
  ![lexos1](https://cloud.githubusercontent.com/assets/6841932/16316956/eba11d10-3956-11e6-8f90-22ffb32ac6f8.png)
        
  * Upload the raw_agnesgrey.txt file
  * Under "Manage" - choose "select"
    * select text and choose "select all" 

4. Under "Prepare" - choose "scrub"
    
  * select scrubbing options
  * upload the en.txt stopwords file
  * preview and select "Apply Scrubbing" 
  * download scrubbed files

5. Under "Prepare" - chose "cut"
    
  * select cutting options
  * use "cut by milestone" and input "chapter" as the term
  * preview and select "Apply Cuts"
  * download cut files

6. Review all of the cut files, there will be 31 files, but we want to get down to 25 files to reflect the exact number of chapters
    
  * manually or using scripts, clean up any messy text or characters
  * add leading zeroes to your file names (i.e. agnesgrey_01.txt)
  * review the segmenting (some of the chapters will need to be merged)

## Analyze and Visualize your Texts:
1. Once your files are processed navigate to <a href="http://voyant-tools.org/" target="_blank">Voyant</a> to analyze your text files
2. Upload all 25 text files into Voyant
3. You will see a dashboard with the following windows:
        
    * Cirrus (word frequency)
        * view as word cloud, terms, or links
    * Reader (corpus)
        * frequency information (hover over the word)
        * distribution information (graph)
        * relative size of documents within corpus (bar graph)
        * select terms from dropdown/search menu
    * Trends (relative frequency graph)
        * trends on specific words (click term to add/remove)
        * document terms table
        * select terms from dropdown/search menu
    * Summary/Documents/Phrases
        * document length
        * vocabulary density
        * word frequency
        * distinctive words 
    * Contexts/Bubblelines (concordances)
        * frequent terms within context
        * select terms from dropdown/search menu
    * other visualizations are also available (hover over the top ? in right corner for more options)

![voyant1](https://cloud.githubusercontent.com/assets/6841932/16317019/28bf6a6c-3957-11e6-9170-5febd585d0a6.png)

4. Start to explore and analyze your texts! 
5. You can generate a URL for the view (tools and data) or an HTML embed snippet


