This is a working example of Lab1 of Natural Language Processing Course
offered on Coursera, which is taught by Professor Andrew NG, Professor Younes
and Professor Lucasz.

I have downloaded the tweets using the NLTK package, which is the open source
package for Natural Language Processing. We have used a 50/50 split, which has 
50% +ve and 50% -ve examples. 

![Pie Chart](<./Screenshot 2025-12-14 180630.png>)

I have developed a pre-processor which would stem the original tweet, which could be
fed to train the model. 

Firstly, we have remove the punctuation and stopwords, then used 
PorterStemmer from NLTK package to reduce the words to their basic 
Stems. 


At last, the print statement shows the original tweet 
                    V/s
The Stems which are stored in a list. 
![Comparison ScrenShot](<./Screenshot 2025-12-14 181847.png>)

I have also freezed the requirements to save space on my workstation
as well you can install the dependencies using requirements.txt
and replicate the tutorial.