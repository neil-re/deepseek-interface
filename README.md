# Web Interface for Ollama (with DeepSeek)

A simple and effective web interface to interact with Ollama models, specifically configured to use DeepSeek.<br>
It includes the connectivity to local Ollama with the respective AI installed locally. <br>It was developed to use with DeepSeek 14B parameteres, but you can change it as described below in the Configuration section. More details in the Features section<br> 
Also includes a 10 min timeout, since local AI might infere slowly, generating error when trying to connect through API, so timeout solves this issue.

## 🚀 Prerequisites

- [Ollama](https://ollama.ai/) installed on your system
- DeepSeek model downloaded (`ollama pull deepseek-r1:14b`)
- A modern web browser

## 📦 Installation

1. Clone this repository or download the files
2. Make sure Ollama is running on your system
3. Open the `index.html` file in your browser

## 💻 Usage

1. Ensure Ollama is running (`ollama serve`)
2. Open `index.html` in your browser
3. Type your query in the text field
4. Click "Send"
5. Wait for the model's response

## ⚙️ Configuration

By default, the interface is configured to use the `deepseek-r1:14b` model. If you want to use a different model, you can modify the following line in the code:

```javascript
model: "deepseek-r1:14b",
```

## 🔍 Features

- Simple and easy-to-use interface
- 10-minute timeout for long queries
- Loading indicator
- Error handling
- Responsive design

## 📝 Notes

- The Ollama API must be running on `localhost:11434`
- Internet connection required for font styles and YouTube button

## 🤝 Contributing

Contributions are welcome. Please open an issue or submit a pull request.

## 📺 More Information

For more AI tutorials and content, visit [Pradera Digital on YouTube](https://youtube.com/@praderadigital).

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
