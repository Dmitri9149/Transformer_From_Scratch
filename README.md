# Transformer_From_Scratch
The code (from scratch, Python, MXNET) for Transformer

I use d2l.ai project http://d2l.ai/ to implement code for the Transformer (machine translation) from scratch. Original paper for the Transformer architecture: 
"Vaswani, A., Shazeer, N., Parmar, N., Uszkoreit, J., Jones, L., Gomez, A. N., … Polosukhin, I. (2017). Attention is all you need. Advances in neural information processing systems (pp. 5998–6008)".  
It is not easy to understand how the Transformer works. I added a lot of comments at most difficult 
parts of the code and many code examples. With it, I hope, it will be easier to learn the architecture. 

As an example the Transformer is used for English French translation on 
small amount of data (about 100000 pairs of sentences or less). 

The learning experiments with different model parameters are collected in /models folder.
For example this: https://github.com/Dmitri9149/Transformer_From_Scratch/blob/main/models/Transformer_MXNet_102400_128_12_30_10_20.ipynb
There are many files like : Final_Working_Transformer....ipynb : this is the same model but with different parameters. 

Some raw theoretical considerations are in: 
"Diagrams_Transformer....ipynb" file
and in:
"Transformer_Values_Keys_Queries.ipynb" file.

It is the first part of my project in Transformers. The next steps: 

1.Translation on English Finnish pairs dataset.   
2.Translation/Learning on big datasets.  
3.Modifications of the original Transformer (change in architecture).  
4.Development of the theory of the Transformers.  
5.Transformers from scratch in Rust.   


