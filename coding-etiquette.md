### Coding Etiquette ###
general guidelines for writing code for the lab

* Lab scripts general follow this format:
  1. Load indices (e.g., get animals, dates, and recording files that you want to analyze)
  2. Analyze data (e.g., loop through each recording session and perform some analysis)
  3. Compile data (e.g., concatenate analysis output across all recording sessions)
  4. Plot data
* make script, file, and function names concise and meaningful
  * generally variables are nouns and functions are verbs (e.g., getstimulustimes = function, stimtimes = variable)
* writing code in chunks can make it easier to read/for others to use
  * conventionally code is limited to 80 characters per line
  * if a set of analysis is longer than 50 lines it may be best as a function

### References ###
these  guidelines were drawn from [Our Coding Club GitHub for Labs](https://ourcodingclub.github.io/2017/05/15/git-for-labs.html)

for more best practices, see [Wilson et al., 2017 Good enough practices in scientific computing]
(https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005510)
