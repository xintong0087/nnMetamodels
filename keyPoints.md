# Project 2 Keypoints

## Main Conclusion

- For simulationists: only the highest level of noise moves one towards choosing the low capacity neural network model.
    - In most cases, a high capacity model is better.
    - Warning: in extreme circumstances when the noise level is too high, a high capacity metamodel will not work.
    - Domain knowledge about the right architecture for the task and knowledge about the noise level are both important.
- For machine learning practitioners: Despite noise in practical data, training is still beneficial.
    - We provide a piece of evidence to show that training cuts through the noise.
- We speculate the convergence rate of $-2/3$

## Flow of Thought

- Table 2: the high capacity metamodel always have better training error, but not necessarily the test/true error
- Metamodeling:
    - We tried everything to make the simiplist model better
    - Mention the tuning process of the RNN 
- Neural network is a data-driven method to find basis function
    - Regression has high and unknown model error
    - The model errors of machine learning metamodels are still unknown, but believed to be much smaller than regression

## Additional Work

- Add RNN* to Table 1
    - $\checkmark$ writing 
    - $\checkmark$ result 
- Fill the test errors for Table 2
    - $\checkmark$ writing
    - $\checkmark$ result
- Training/true QQ plot for good/bad RNN    
    - $\checkmark$ writing
    - $\checkmark$ result
- Similar to Table 3: fill experiments for HiCap LSTM
    - $\checkmark$ writing
    - $\checkmark$ result
    - Fill Figure 9 with results from new experiments
- Add a boxplot for $N = 1$ like Figure 8.    
    - $\checkmark$ writing
    - $\checkmark$ result
    - $\checkmark$ Different boxes with different colors
- In Figure 5, refer to Jessica's result for GMMB/GMAB
    - $\checkmark$ writing
    - $\checkmark$ result
- In Figure 7, add the Pearson correlation onto the graphs
    - $\checkmark$ result
- In Figure 9 and 10, add the confidence band
    - $\checkmark$ writing
    - $\checkmark$ result
- Delete "LoCap" from "Locap LSTM"
    - $\checkmark$ writing

