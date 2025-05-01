# Learning-Computational-Protein-Design

I am using this repository to learn about computational methods of protein structure design. I normally work on image processing but for a while I really wanted to get into protein design with the emergence of AlphaFold and other models I think it is a great opportunity to learn about this field. I will post projects related to specific topics surrounding this field. I am not aiming here to build something SOTA, but definitely I do my best to optimize the models and get the best possible results.  

# Projects:

### 1. Secondary Structure Prediction
**Objective:**  Predict whether each amino acid in a protein sequence is part of an Alpha-Helix (H), Beta-Sheet (E), or Coil/Loop (C).

**Concepts practiced:**  Sequence handling, Sequence encoding, Pad tokens, Sequence labeling task. 

**Steps:**

1. Gather sequences and their corresponding secondary structure labels (H/E/C strings).
2. Represent sequences numerically.
3. Pad sequences to a uniform length or use techniques to handle variable lengths. 
4. Build a model to predict secondary structure labels:
    - Input Layer -> Embedding Layer-> 1D CNN layers -> Output Layer (predicts H/E/C probability for each position).
    - Train the model 
    - Evaluate accuracy per residue.


