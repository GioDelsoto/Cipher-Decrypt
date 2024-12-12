# Cipher Decryption Project

This project aims to develop one approach to decrypting letter-shuffling ciphers. By analyzing the probability distribution of letter sequences within a given language, we can make informed guesses about the most likely plaintext. A genetic algorithm will be employed to efficiently search for the optimal key-value pairs that maximize the probability of a given ciphertext.

## Methodology

- Probability Distribution:

  - A comprehensive corpus, such as Moby Dick, will be used to calculate the probability distribution of letter sequences in the - English language.
  - This distribution will serve as a baseline for evaluating the likelihood of generated plaintext.

- Genetic Algorithm:
  - A genetic algorithm will be implemented to explore the vast search space of possible key-value pairs.
  - Initial populations of potential solutions will be generated randomly.
  - Fitness will be evaluated based on the probability of the decrypted ciphertext, as determined by the language model.
  - Through processes of selection, crossover, and mutation, the algorithm will converge towards the optimal solution.
