# SERA
SERA is a convention for the transcription of Ethiopic script into the seven bit American Standard for Computer Information Interchange (ASCII).
Amharic to SERA converter for  python 2 and 3
I used a mapping data from http://etd.aau.edu.et/bitstream/handle/123456789/1245/Daniel%20Zegeye.pdf?sequence=1&isAllowed=y
Efficiency benchmark carried out with 8612820 characters (python2 -- 3.316404 seconds) (python3 -- 1.550314) on Intel(R) Core(TM) i5-2520M CPU @ 2.50GHz.

Usage 
   *** python sera_mapper_v1.py -f file_name to for file conversion \n
   
   *** python sera_mapper_v1.py -s \'your string here \' for direct string conversion

