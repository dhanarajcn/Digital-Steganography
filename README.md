# 🔐 Digital Steganography System using Java

## 📌 Introduction
Digital steganography is the practice of concealing sensitive information within digital media—such as images, audio, or video—without altering its visible or audible appearance. This project focuses on building a secure and user-friendly steganography system using **Java**, capable of hiding and extracting confidential messages within image files.

## 🧩 Problem Statement
With increasing digital communication, protecting sensitive data from interception is crucial. Traditional encryption hides **content**, but steganography hides the **existence** of communication itself. This project addresses the need for a **robust, efficient, and secure steganography system** that can embed hidden data in images, with minimal perceptual change and high security.

## 🎯 Objectives
- ✅ Develop a steganography system using Java  
- ✅ Implement LSB and (optionally) DCT steganography techniques  
- ✅ Ensure high concealment with minimal visual distortion  
- ✅ Evaluate system performance and security  
- ✅ Build a user-friendly GUI with multiple screens (Home, Compose, BreakPage)  
- ✅ Explore encryption integration for added security  
- ✅ Document the development and testing process for future improvements  

## 🏗️ System Design

**Architecture Overview:**
- **User Interface (GUI):** Provides screens for message composition and decoding.
- **Encoding/Decoding Module:** Embeds/extracts messages using steganography algorithms (e.g., LSB).
- **File Management:** Handles media file selection and integrity validation.
- **Encryption Module (Optional):** Provides additional layer of security by encrypting message before embedding.

**Screens:**
- `Home`: Main entry point to the application  
- `ComposePage`: GUI for encoding/embedding messages  
- `BreakPage`: GUI for decoding/extracting hidden messages  

## ⚙️ Implementation

The project uses the **Least Significant Bit (LSB)** technique:
- Each pixel in an image is made of RGB values (8-bit integers).
- The **LSB of each color component** is modified to store secret data bits.
- Since the change is minimal, the image appears unchanged to the human eye.
- Simple, fast, and efficient for basic steganographic needs.

## 🖥️ Technologies Used
- Java (Core Language)
- Java Swing (for GUI)
- File I/O
- Image Processing Libraries
- (Optional) Java Encryption APIs

## 💡 Key Features
- Embed and extract text data into image files
- Minimal visual distortion in stego-image
- Simple, intuitive graphical user interface
- Secure communication through covert channels
- Extendable for audio/video steganography or encryption support

## 🚀 Getting Started

1. Clone this repo:
   ```bash
   git@github.com:dhanarajcn/Digital-Steganography.git
