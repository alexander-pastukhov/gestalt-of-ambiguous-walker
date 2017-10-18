A data set and the analysis code for the __"First, you need a Gestalt: an interaction of bottom-up and top-down streams during perception of an ambiguously rotating human walker"__ manuscript. 

## Analysis
The complete analysis, including all figures and statistical comparisons, can be found in Jupyter notebooks `Complete analysis.ipynb` and `Within group analysis using linear mixed models.ipynb`.

## Data folders
* Main experiment: _Naïve_ and _Informed_ folders.
* Learning experiment: _Learning_ folder.

## CSV-file format
* Index
* Observer: observer ID, apart from learning experiment, matches the file name
* SessionID: timestamp for the session start
* Condition: condition label (_scrambled static_, _inverted walker_, _upright walker_, _scrambled walker_).
* Block: block index, block 0 was a training block and was excluded from the analysis
* Block duration: block duration in seconds
* Percept:
  * __-1__ illusory rotation, with front surface moving to the __left__ 
  * __1__ illusory rotation, with front surface moving to the __right__
* Onset: percept onset time relative to the block start, in seconds
* Duration: percept duration, in seconds.

## License
All data (and associated content) is licensed under the [CC-By Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/). All code is licensed
under the [MIT License](http://www.opensource.org/licenses/mit-license.php).