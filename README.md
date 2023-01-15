# Analysis-and-Prediction-of-Covid-19-Mutation-Rate-using-LSTM-GRU-and-RNN
In this project, we calculated the mutation rate of nucleotide sequence and then implement Long-Short Term Memory (LSTM) model, Simple Recurrent Neural Networks and Gated recurrent units (GRUs) to predict the future mutation rate of SARS-CoV-2 virus. Further, we have also calculated the codon mutation rate of the SARS-CoV-2 virus. Analyzed and compared model performances based on loss rate and true mutation rate.

# CODE EXPLANATION

- Input the SARS Cov-19 strain genomic sequence into a list. (Ref list). Input the various virus strains from diseased individuals in the dataset into a list. (Sequence list). We have taken a dataset comprising strains from continents for analysis. 
 
- A nucleotide list comprising of A, C, G, T is created 
 
- For each sequence, initiate a Mutation_matrix which will contain the number of mutations for every pair of nucleotides in a particular sequence. 
 
- Compute the mutation rate using the formula, 
 
                 MutationRate = (mutation/(1*len(reference))) *100 
 
- Append the matrix into the Mutation_Rates list which comprises mutation rates of every pair of nucleotides in every sequence 
 
- Divide the dataset into training and test and input the respective Mutation_Rates into the model for prediction. The model considers the mutation rate of twelve sequences sorted by date to predict the thirteenth sequence mutation rate. 


# RESULTS


- ![image](https://user-images.githubusercontent.com/30584808/212567868-3840ce7a-171a-4828-bff8-fcc021d7d4b9.png)
