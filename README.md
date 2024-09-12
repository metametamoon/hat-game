### Hat game cards generator

A generator of flash cards for a game named Hat / Alias based on the alledged difficulty assessed by the Juilland coefficient, which is a measure of dispersion that builds on the Coefficient of variation and, informally, measures how universal or topic-specific the considered word is. 
The repository has included the Russian frequency dictionary by Lyashevskaya and Sharov, downloaded from the official [site](http://dict.ruslang.ru/freq.php) and reencoded into utf-8 for simplicity. 

The main notebook, written in Kotlin, is located in `hat-game.ipynb` and is highly customizable. For example, by changing the third cell you can include any frequency dictionary you want, granted you can parse it, or by changing the fourth cell you can adjust the way the word's difficulty is assessed. 
The draft notebook, written in Python, is located in `hat-game-draft.ipynb` and contains the raw, unpolished code which does essentialy the same thing.