# Flesch-Kincaid-Grade-Level
Function to calculate the grade Level of a Text

The Flesch-Kincaid grade level of a text is defined in Wikipedia as: https://en.wikipedia.org/wiki/Flesch%E2%80%93Kincaid_readability_tests 

To approximate the number of syllables in a word, we will count the number of vowel phones in a word, counting consecutive vowel
phones as one vowel. The decomposition of words into phones (vowel phone and consonant phones) is
available from the CMU Pronouncing Dictionary (http://www.speech.cs.cmu.edu/cgi-bin/cmudict) . 

Decomposition of words into phones:- http://svn.code.sf.net/p/cmusphinx/code/trunk/cmudict/cmudict-0.7b

Vowel and consonant phones in the dictionary:- http://svn.code.sf.net/p/cmusphinx/code/trunk/cmudict/cmudict-0.7b.phones 


