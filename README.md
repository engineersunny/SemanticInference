# Getting Started

Original project: https://sherlock.media.mit.edu/
Git: https://github.com/mitmedialab/sherlock-project

1.  python3.7 required & install requirements.txt
2.  Start from here: 01-data-preprocessing.ipynb
3.  OR Start from 02-1-3 Training with preprocessed data - /data


# Model history

Replace TF with jax-flax (https://flax.readthedocs.io/en/latest/notebooks/flax_basics.html)

1.  Replace NN model: 02-1-2-train-with-Flax [09 2022]
        Four sub-models: Character | Word | Paragraph | Rest
    
        [f1 score, accuracy] with Character model only: [0.001,0.022]
         *TF got 0.65-0.70 f1 score with Character + Word + Paragraph model..
        
2.  02-1-3: Jax - code restructuring & drawing model graph [10 2022]

# 02-1-2-train-with-TF: using TF
# 02-1-3-train-with-Flax-Graph-Functional-Working: using Jax
# 05-0213-train-save-model: using Jax & trainstate  


3.  05-0213-train-save-model: 
        train and save trained model [03 2023]
4.  05-1-use-pretrained-model: 
        prerequisite - Run 05-0-data-preprocessing first
        prediction with pretained params (flax_model_MAR.msgpack)







 #  [todo] Replace featurisation


# required files

sherlock/features
        /glove.6B.50d
        /par_vec_trained_400.pkl (I uploaded to my cd google account drive)
        /par_vec_trained_400.pkl.docvecs.vectors_docs.npy
        /par_vec_trained_400.pkl.trainables.syn1neg.npy
        /par_vec_trained_400.pkl.wv.vectors.npy







https://dev.azure.com/clrdyn/DataScience/_git/PyORM?path=/README.md