# Medisheild
Medsheild: Secure medical Image Steganography 

## Introduction  

**MediShield** is an innovative full-stack web application designed to enhance the security of medical records by embedding them within diagnostic images using advanced steganography and machine learning techniques. This approach ensures the confidentiality, integrity, and availability of sensitive patient data, offering a layer of protection beyond traditional encryption methods.  
## Problem Statement  

Current practices of storing and transmitting medical records separately from diagnostic images expose data to potential breaches, tampering, and loss. These vulnerabilities compromise patient privacy and the quality of care. **MediShield** addresses this challenge by securely embedding medical records directly within diagnostic images.  

---

## Objectives  

1. Develop a secure and efficient method to embed medical records within diagnostic images.  
2. Utilize steganography and machine learning techniques to safeguard data confidentiality and integrity.  
3. Build a user-friendly web application for seamless upload, embedding, and extraction of medical records.  

---

## Techniques  

1. **Image Classification:**  
   - Implemented using Support Vector Machines (SVM) to identify Regions of Interest (ROIs) and non-ROIs in diagnostic images.  

2. **Data Encryption:**  
   - Utilized Advanced Encryption Standard (AES) to encrypt sensitive medical records before embedding.  

3. **Steganographic Embedding:**  
   - Applied Integer Wavelet Transform (IWT) for secure embedding of encrypted data into non-ROI areas of diagnostic images.  

4. **Data Extraction and Decryption:**  
   - Extracted embedded data using a decryption key to ensure secure access and integrity.  

---

## Features  

- Secure embedding of medical records within diagnostic images.  
- Advanced encryption for safeguarding sensitive data.  
- Efficient image classification to preserve diagnostic image quality.  
- User-friendly interface for uploading, embedding, and extracting records.  

---

## Software Requirements  

1. **Java 8 or higher:** Back-end programming.  
2. **Spring Boot Framework:** Simplified application development.  
3. **OpenCV Library:** Image processing and analysis.  
4. **Java Cryptography Extension (JCE):** AES encryption and decryption.  
5. **HTML, CSS, and JavaScript:** Front-end development.  

---

## Hardware Requirements  

1. Computer or server with at least:  
   - **4 GB RAM**  
   - **2 GHz Processor**  
2. Adequate storage for diagnostic images and medical records.  

---

## Installation  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/yourusername/MediShield.git  
   ```  

2. Navigate to the project directory:  
   ```bash  
   cd MediShield  
   ```  

3. Install dependencies using Maven:  
   ```bash  
   mvn install  
   ```  

4. Run the Spring Boot application:  
   ```bash  
   mvn spring-boot:run  
   ```  

5. Open the application in a browser at:  
   ```  
   http://localhost:8080  
   ```  

---

## Usage  

1. **Upload Diagnostic Image:**  
   - Upload an image for embedding medical records.  

2. **Embed Medical Records:**  
   - Provide sensitive records and encrypt them using AES.  
   - The system classifies image regions and securely embeds data using IWT.  

3. **Extract and Decrypt Data:**  
   - Use the corresponding decryption key to retrieve and view embedded records.  

---

## References  

1. [Secure Medical Record Embedding in Diagnostic Images using Steganography](https://pubmed.ncbi.nlm.nih.gov)  
2. [Steganographic Model for Medical Image Security](https://www.sciencedirect.com)  
3. [Novel Steganographic Technique using SVM and IWT](https://link.springer.com)  

---

## License  

This project is licensed under the [MIT License](LICENSE).  

---

## Contact  

For further inquiries, feel free to reach out:  
- **Email:** your-email@example.com  
- **GitHub:** [yourusername](https://github.com/yourusername)  

---

Feel free to customize the above template with your specific details (e.g., repository URL, email address, etc.).
