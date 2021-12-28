### The Goal:
- The goal of this project is to train several classification/clustering models to help the research community in classifying unknown protein based on the AA sequence (primary structure) to better understand its functionality.

<img width="816" alt="Screen Shot 1443-05-24 at 10 11 52 PM" src="https://user-images.githubusercontent.com/32347958/147599851-fc63e79b-c4f1-484a-b01d-4445aec8219e.png">

- Using PCA, helped with reducing the demintionality significantly and capturing 84% of the data variance still when treating every 4 amino acids as a word. I have been working on 3 different approches aiming to arrive at the best solution.
 
<img width="464" alt="Screen Shot 1443-05-24 at 10 20 15 PM" src="https://user-images.githubusercontent.com/32347958/147599832-dbdf1b82-7f6b-490d-9562-a521be4b6c8d.png">

- The above image shows how the clusters are when considering each character as a single word(~112000 * 20), which is not the desired results because there isn't a clear boundries between clusters and also the accuracy is too low.
