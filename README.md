# Sentiment Analysis of Azerbaijani Turkish Texts <br>
## First install pip package installer: <br>
        sudo apt-get install python-pip

## Required Libraries: <br>

### Pandas: <br>
        pip install pandas

### Numpy: <br>
        pip install numpy

### Matplotlib: <br>
        pip install matplotlib

### Polyglot: <br>
        pip install polyglot   

### If you are still have some problems download this necessary dependancy as well: <br>
        pip install pycld2 morfessor

### NLTK: <br>
        pip install nltk
        
### Spacy: <br>
        pip install spacy

### Load English language model using spaCy library: <br>    
        python3 -m spacy download en_core_web_sm 

### Tensorflow: <br>
        pip install tensorflow
        
### For Glove Pre-trained word embeddings write the commands, unzip the file and move the file named glove.6B.100d.txt on your code location: <br>
        wget https://downloads.cs.stanford.edu/nlp/data/glove.6B.zip
        
        unzip -q glove.6B.zip
### Download pre-trained Azerbaijani FastText file<br>
        wget https://dl.fbaipublicfiles.com/fasttext/vectors-crawl/cc.az.300.vec.gz

### Install Gensim<br>
#### This software depends on NumPy and Scipy, two Python packages for scientific computing.<br>
        pip install --upgrade gensim
        pip install scipy