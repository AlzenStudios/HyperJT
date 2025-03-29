# HyperJT Language 🚀  
**HyperJT Language** is an advanced JSON-based library that introduces a powerful **regular expression pattern matching system**, designed for **real-time** applications such as video games, authentication systems, dynamic fetching, and more.  

![image](https://github.com/user-attachments/assets/b7b44b1f-ffe2-4dcf-a821-ac731cf00ab6)

## ✨ Features  
- 📌 **Advanced Pattern Matching** → Use regular expressions in JSON keys and values for dynamic searches and transformations.  
- ⚡ **Optimized for Real-Time** → Perfect for video games, login pages, registration, and other live functionalities.  
- 🔄 **Dynamic Parsing and Validation** → Define flexible JSON schemas and validate them on the fly.  
- 🔍 **Powerful Querying** → Supports advanced path expressions similar to XPath for JSON.  
- 🌍 **Web & Networking Compatible** → Ideal for dynamic fetching, WebSockets, and REST APIs.  

## 📜 Usage Example  
```json
{
  "{user_.*}": {
    "id": "\\d+",
    "email": "^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\\.[a-zA-Z]{2,}$"
  }
}
```
➡️ This schema dynamically validates users with numeric IDs and properly formatted emails!  

## 🛠️ Technologies  
- C++ (based on nlohmann/json or custom parser)  
- Advanced regex for pattern matching  
- Cross-platform support  

## 📦 Installation  
```sh
git clone https://github.com/AlzenStudios/HyperJT.git
cd HyperJT
mkdir build && cd build
cmake ..
make
```

## 📢 Contribute  
If you want to improve **HyperJT Language**, feel free to open issues or pull requests! 🚀  

🔗 **Repo:** [https://github.com/AlzenStudios/HyperJT](https://github.com/AlzenStudios/HyperJT)  
📖 **Docs:** Coming soon...  

---
