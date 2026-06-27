# Information Theory & Compression Algorithms in Java

This repository contains my implementations of classical **Information Theory** and **Data Compression** algorithms developed as part of the *Introduction to Information Theory* course. The repository covers both **lossless text compression** and **lossy image compression**, including dictionary-based coding, entropy coding, arithmetic coding, predictive coding, and vector quantization.

---

## Algorithms Implemented

### 1. LZ77 Compression

Implemented the complete LZ77 compression algorithm, including:

* Sliding window search
* LZ77 tag generation
* Text compression
* Text decompression
* File-based input/output
* Compression ratio evaluation

---

### 2. LZ78 Compression

Implemented the complete LZ78 algorithm, including:

* Dictionary construction
* Binary tag generation
* Binary file storage
* Binary tag decoding
* Dictionary reconstruction
* Compression ratio analysis

---

### 3. Standard Huffman Coding

Implemented Huffman coding from scratch, including:

* Character frequency analysis
* Entropy calculation
* Huffman tree construction
* Huffman code generation
* Binary encoding
* Binary decoding
* Code table generation

---

### Mini Project Adaptive Huffman Coding

Implemented adaptive Huffman coding with dynamic tree updates, including:

* NYT (Not Yet Transmitted) node handling
* Dynamic Huffman tree construction
* Online encoding
* Online decoding
* Frequency updates
* Node swapping and tree rebalancing

**Bonus**

* Huffman tree visualization using Java Swing

---

### 4. Binary Arithmetic Coding

Implemented binary arithmetic coding for lossless text compression, including:

* Symbol frequency and probability computation
* Alphabetically sorted probability table generation
* Binary arithmetic encoding
* E1 and E2 scaling rules for precision handling
* Binary compressed file generation
* Probability table export
* Binary arithmetic decoding
* Reconstruction of the original text from the compressed bitstream

The implementation stores the compressed data as binary bytes while maintaining the symbol probability table required for decoding.

---

## Term Project

### Vector Quantization for Image Compression (LBG Algorithm)

Developed a complete vector quantization image compression system using the **Linde–Buzo–Gray (LBG)** algorithm and K-Means refinement, including:

* RGB image preprocessing and grayscale conversion
* Image partitioning into fixed-size blocks (vectors)
* Codebook generation using iterative LBG splitting
* K-Means refinement for codebook optimization
* Euclidean distance-based vector matching
* Image reconstruction from compressed representations
* Mean Squared Error (MSE) calculation
* Compression ratio evaluation
* Experimental analysis using different block sizes and codebook sizes

---

### Assignment (5) 2-D Predictive Coding

Implemented predictive image compression using multiple prediction models, including:

* First-order predictor
* Second-order predictor
* Adaptive 2-D predictor
* Prediction residual computation
* Uniform scalar quantization
* Image reconstruction
* Mean Squared Error (MSE) calculation
* Compression ratio evaluation

---

## Repository Structure

```text
information-theory-compression-algorithms-java
│
├── LZ77/
├── LZ78/
├── Standard-Huffman/
├── Binary-Arithmetic-Coding/
├── Adaptive-Huffman/
├── Vector-Quantization-Term-Project/
├── Predictive-Coding-2D/
└── README.md
```

---

## Technologies

* Java
* Object-Oriented Programming (OOP)
* File I/O
* Binary File Processing
* Data Structures
* Priority Queue
* HashMap
* Bit Manipulation
* Swing (Visualization)

---

## Topics Covered

* Information Theory
* Lossless Compression
* Lossy Compression
* Dictionary-Based Compression
* Huffman Coding
* Adaptive Huffman Coding
* Binary Arithmetic Coding
* Predictive Coding
* Vector Quantization
* LBG Algorithm
* Image Compression
* Entropy
* Compression Ratio
* Mean Squared Error (MSE)

---

## Learning Outcomes

Through these implementations, I gained hands-on experience with:

* Dictionary-based compression algorithms
* Entropy-based compression techniques
* Binary arithmetic coding with scaling
* Dynamic Huffman tree maintenance
* Binary encoding and decoding
* Vector quantization using the LBG algorithm
* Predictive image compression
* Performance evaluation using compression ratio and MSE
* Designing complete compression and decompression pipelines

---

## Author

**Habiba Ayman Amin**
