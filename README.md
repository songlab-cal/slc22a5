# slc22a5
Variant effect prediction for SLC22A5 transporter gene using Potts models.

# Colabs

## Predicted single mutant variant effects with trained potts models
`slc22a5_single_mutants.ipynb` 

## Training a potts model from an alignment
`slc22a5_train_potts.ipynb`

# Data

## Wildtype

```
wget http://s3.amazonaws.com/songlabdata/slc22a5/O76082.fasta
```

## Alignments
```
wget http://s3.amazonaws.com/songlabdata/slc22a5/alignments/deepsequence.a3m
wget http://s3.amazonaws.com/songlabdata/slc22a5/alignments/eve.a3m
wget http://s3.amazonaws.com/songlabdata/slc22a5/alignments/hhblits.a3m
wget http://s3.amazonaws.com/songlabdata/slc22a5/alignments/mammals_30.a3m
wget http://s3.amazonaws.com/songlabdata/slc22a5/alignments/vertebrates_100.a3m
```

## Trained Potts models

```
wget http://s3.amazonaws.com/songlabdata/slc22a5/potts/deepsequence.npz
wget http://s3.amazonaws.com/songlabdata/slc22a5/potts/eve.npz
wget http://s3.amazonaws.com/songlabdata/slc22a5/potts/hhblits.npz
wget http://s3.amazonaws.com/songlabdata/slc22a5/potts/mammals_30.npz
wget http://s3.amazonaws.com/songlabdata/slc22a5/potts/vertebrates_100.npz
```
