# Text-mining
This session introduced text analysis and mining with tools that do not require programming knowledge or skills. The primary tools used for pre-processing text, analysis, and visualization include <a href="http://lexos.wheatoncollege.edu/upload" target="_blank">Lexos</a> and <a href="http://voyant-tools.org/" target="_blank">Voyant</a>. 

## Resources:
* TextMiningIntro.pdf - slides with an overview of text mining and analysis, sample projects, and resources 

## Texts for mining and analysis:
For this session we used Anne Brönte’s novel, *Agnes Grey* (1847). This text consists of 25 chapters, approximately 219 pages. This <a href="http://www.gutenberg.org/files/767/767-0.txt " target="_blank">text</a> was downloaded from Project Gutenberg.

* en.txt - text file with English stopwords that can be edited to one's needs (drawn from the <a href="http://mallet.cs.umass.edu/download.php" target="_blank">Mallet 2.0 toolkit</a>)
* raw_agnesgrey.txt - entire raw text of *Agnes Grey*
* scrubbed_agnesgrey.txt - scrubbed text of *Agnes Grey*
* modified-agnesgrey folder - chunked text of *Agnes Grey* using chapters as milestone

## Getting Started:
1. Download all of the text files 
2. Open the raw_agnesgrey.txt file
    
  * manually or using scripts, remove all of the text that appears above "CHAPTER I" and all of the text that appears after the final sentence
3. Navigate to <a href="http://lexos.wheatoncollege.edu/upload" target="_blank">Lexos</a>
    
  * Upload the raw_agnesgrey.txt file
  * Under "Manage" - highlight text and click "select all"

4. Under "Prepare" - select "scrub"
    
  * select scrubbing options
  * upload the en.txt stopwords file
  * preview and select "Apply Scrubbing" 
  * download scrubbed files

5. Under "Prepare" - select "cut"
    
  * select cutting options
  * use "cut by milestone" and input "chapter" as the term
  * preview and select "Apply Cuts"
  * download cut files

6. Review all of the cut files, there will be 31 files, but we want to get down to 25 files to reflect the exact number of chapters
    
  * manually or using scripts, clean up any messy text or characters
  * add leading zeroes to your file names (i.e. agnesgrey_01.txt)
  * review the segmenting (some of the chapters will need to be merged)

Once your files are processed navigate to <a href="http://voyant-tools.org/" target="_blank">Voyant</a> to analyze your text files.



