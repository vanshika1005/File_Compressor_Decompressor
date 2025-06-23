# File_Compressor_Decompressor
HuffmanCompressor is a C++ project that implements lossless compression and decompression of files using an advanced Huffman coding algorithm. This tool works at a word-level for text files.
🔧 Features
📁 Compress a single file or all text files in a folder

🧠 Intelligent detection of already compressed files

✍️ Word-level Huffman coding for better compression efficiency

🔐 Stores code map in a separate .map file for decompression

🖥️ Console-based interaction with clear logs and messages

📂 Folder Structure
bash
Copy
Edit
HuffmanCompressor/
├── src/                    # Source code
│   ├── compressor.cpp      # Compression logic
│   ├── decompressor.cpp    # Decompression logic
│   ├── huffman.cpp         # Huffman tree implementation
│   ├── main.cpp            # Entry point
├── assets/                 # Test text files
├── compressed/             # Output compressed files
├── decompressed/           # Output decompressed files
├── README.md               # Project documentation
