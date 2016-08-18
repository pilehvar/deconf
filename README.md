# DeConf
## De-conflated Semantic Representations

Sense representations generated using the algorithm introduced in:
* M. T. Pilehvar and N. Collier, [De-Conflated Semantic Representations](http://www.pilevar.com/taher/pubs/Pilehvar_Collier_EMNLP2016.pdf). EMNLP 2016, Austin, TX.


## Download
Semantic representations for around 130K word senses in WordNet 3.0:

* [Download bin](http://mws-02485.mws3.csx.cam.ac.uk/DeConf/wn3.0_sense_vectors.bin): in bin format (150 MB), or
* [Download txt](http://mws-02485.mws3.csx.cam.ac.uk/DeConf/wn3.0_sense_vectors.txt.bz2): as a compressed (bzip2) text file (228 MB).

The sense representations live in the same 300-dimensional semantic space of words and phrases trained by [Word2vec](https://code.google.com/archive/p/word2vec/) on the Google News Corpus ([direct link](https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit?usp=sharing)).


## Data format
```
sense_ID    <300-d real valued vector>
```
where sense_IDs are in the form *word#1*, *word#2*, ..., *word#n* (where *n* is the polysemy of the *word*).

## Mapping files

* A [mapping](http://mws-02485.mws3.csx.cam.ac.uk/DeConf/sense_key_map.txt.bz2) between sense_IDs and WordNet 3.0 sense keys.

* The [word list](http://mws-02485.mws3.csx.cam.ac.uk/DeConf/sense_list.txt.bz2) of the pre-trained Word2vec representations (3 million words and phrases), along with the sense_IDs for those that overlap with the vocabulary of WordNet 3.0.




