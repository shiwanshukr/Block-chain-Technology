# Block-chain-Technology
Data Structures: LinkedList that uses a hashtable (dictionary) to look up the block for a given hash.
Efficiencies: O(1) time complexity

The design uses two data structures:

Data Structure						Time Complexity			
Hashtable [dictionary]					O(1)
LinkedList								O(n)


TIME COMPLEXITY

Inseting a block 	: 		O(1)
Looking up a block 	: 		O(1)
Traversing a bloac 	: 		O(N)	


A hashtable is required to lookup or insert blocks in the blockchain. Why? A block is linked to its previous block via the previous block's hash. The hashtable lets us lookup the previous block via its hash.
A block has a link to its previous block. Therefore, traversal is from the tail (last block added) to the head (first block added).
