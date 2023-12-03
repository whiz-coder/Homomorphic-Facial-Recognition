# Homomorphic-Facial-Recognition

**Objective:**
Secure and privacy-preserving facial recognition system leveraging homomorphic encryption for confidential computations on sensitive facial data.

**Key Features:**
- Extracts facial embeddings from images using the Facenet model.
- Implements homomorphic encryption (CKKS scheme) for secure operations on facial embeddings.
- Demonstrates privacy-preserving calculations, such as squared Euclidean distance, without exposing raw facial features.
- Enables secure storage and retrieval of homomorphically encrypted results in the cloud.

**Dependencies:**
- Tenseal: Python library for homomorphic encryption.
- DeepFace: Deep learning library for facial analysis.

**Usage Instructions:**
1. Install required dependencies using `pip install tenseal deepface`.
2. Execute the provided Python script for privacy-preserving facial recognition.

**Contributing Guidelines:**
- Contributions are welcome! Fork the repository, make your changes, and submit a pull request.

**License:**
This project is licensed under the [MIT License](LICENSE).
