
Random Sampling: This method involves selecting a random subset of the existing sparse matrices and adding them to the dataset. This is a simple yet effective augmentation technique that can help increase the size of the training set without introducing significant distortions or noise.


Proc: Select a random subset of the existing sparse matrices based on a certain probability distribution.
Cons: The selected matrices may not be representative of the underlying physical problem, leading to suboptimal results in the augmented dataset.
Costs: Low computational requirements as the selection process is straightforward.
Risks: The selected matrices could potentially introduce new correlations or dependencies that were not present in the original dataset, leading to overfitting.
Augmented Graph Verification Method: Compare the eigenvalues and eigenvectors of the augmented sparse matrix with those of the original dataset.
