# Cyber Steganography Project  
### Hide & Extract Data Using Image Steganography

 📌 Introduction  
This project demonstrates a complete **Cyber Steganography System** that allows users to **hide secret messages inside images** using LSB (Least Significant Bit) encoding and extract them securely.  
It includes a **frontend dashboard**, **authentication UI**, and a **backend Python stego engine**.

This project was built as part of a university Cyber Security module.

---
 🎯 Objectives  
- Implement a secure method to hide text inside an image.  
- Build an easy-to-use dashboard for encryption and decryption.  
- Validate payload capacity and image quality before embedding.  
- Provide a clean, functional end-to-end system demonstrating cyber concepts.

---
 🧠 Features  
✔ Hide secret messages inside images (LSB Steganography)  
✔ Extract message from encoded images  
✔ Payload/capacity calculation  
✔ Drag-and-drop upload UI  
✔ Login page + Dashboard interface  
✔ Professional project structure  
✔ Clear error messages & validation  

 

🔐 Steganography Engine (Python)
- LSB-based message embedding  
- Message extraction  
- Payload calculation  
- Lossless encoding  
- Input validation & error handling  

 💻 Frontend Interface
- Login & authentication screen  
- Dashboard UI  
- Upload previews  
- Encode/Decode modules  
- Clean CSS styling  

 📦 Technology Stack
- Python (Pillow, NumPy)  
- HTML5, CSS3, JavaScript**  
- Steganography & Cybersecurity Concepts**
---

 📁 Project Structure  
bash
📁 Cyber-Stego-Project
│
├── index.html
├── login.html
├── dashboard.html
│
├── static/
│   ├── styles.css
│   ├── script.js
│   ├── images/
│
├── stego_hide.py
├── stego_extract.py
│
├── requirements.txt
└── README.md

 ⚙️ How it Works  

 🔹 1. Hiding Message (Encoding)  
- The script reads the input image pixel-by-pixel  
- It modifies the **least significant bit** of each pixel  
- Secret message is converted to binary and embedded  
- Output is a stego image that looks identical to the normal image  

 🔹 2. Extracting Message (Decoding)  
- Reverse process  
- Reads LSB values  
- Rebuilds the binary data into readable text  

---

## ▶️ How to Run  

1️⃣ Install Dependencies**
```bash
pip install -r requirements.txt


⚙️ How it Works  

 🔹 1. Hiding Message (Encoding)  
- The script reads the input image pixel-by-pixel  
- It modifies the **least significant bit** of each pixel  
- Secret message is converted to binary and embedded  
- Output is a stego image that looks identical to the normal image  

 🔹 2. Extracting Message (Decoding)  
- Reverse process  
- Reads LSB values  
- Rebuilds the binary data into readable text  

---

 ▶️ How to Run  

1️⃣ Install Dependencies**

pip install -r requirements.txt

