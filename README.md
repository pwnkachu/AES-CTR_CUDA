## AES-CTR CUDA

This repository provides a CUDA-accelerated implementation of the Advanced Encryption Standard (AES) operating in Counter (CTR) mode. It is designed to leverage the parallel processing capabilities of NVIDIA GPUs, demonstrating how hardware acceleration can significantly increase encryption and decryption throughput. You can easily build the project using the standard NVIDIA CUDA compiler by running nvcc -o aes_ctr_cuda main.cu.

Please note that this project is intended strictly as a demonstration of CUDA performance and parallel computing techniques. The provided AES implementation has not been audited or hardened, meaning it may be insecure and vulnerable to various side-channel or cryptographic attacks. It is for educational and demonstrational purposes only and should never be used to secure data in real-world or production environments.
