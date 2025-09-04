# 🧠 GGTune - Professional AI Model Training & Fine-tuning Platform

<div align="center">

![GGTune Logo](assets/icon.png)

**The Ultimate Open Source AI Model Training Platform**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/version-2.0.0-blue.svg)](https://github.com/shaiqjamal/ggtune)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20macOS-lightgrey.svg)](https://github.com/shaiqjamal/ggtune)
[![Python](https://img.shields.io/badge/python-3.8+-blue.svg)](https://python.org)
[![Node.js](https://img.shields.io/badge/node.js-16+-green.svg)](https://nodejs.org)

[🌐 Website](https://www.ggtune.com) • [📖 Documentation](https://www.ggtune.com/docs) • [🐛 Issues](https://github.com/shaiqjamal/ggtune/issues) • [💬 Discussions](https://github.com/shaiqjamal/ggtune/discussions)

</div>

---

## 🚀 Quick Start

### One-Line Installation

**Linux/macOS:**
```bash
git clone https://github.com/shaiqjamal/ggtune.git && cd ggtune && chmod +x install.sh && ./install.sh
```

**Windows:**
```cmd
git clone https://github.com/shaiqjamal/ggtune.git && cd ggtune && install.bat
```

### Launch GGTune
```bash
# Linux/macOS
./ggtune.sh

# Windows
ggtune.bat

# Or use npm
npm start
```

## 🚀 Overview

**GGTune** is a revolutionary, professional-grade AI model training platform that makes fine-tuning and converting AI models accessible to everyone. Built with cutting-edge technology and an intuitive interface, GGTune supports the latest model architectures and provides enterprise-level features in an open-source package.

### ✨ Key Features

- 🤖 **Universal Model Support** - Works with 20+ model architectures (Qwen3, Phi-4, Llama 3.3, Gemma, Mistral, etc.)
- 🎯 **Smart Auto-Detection** - Automatically detects and configures any model
- 📊 **Intelligent Dataset Conversion** - Converts any dataset format to work with any model
- 🔧 **Professional Fine-tuning** - LoRA, QLoRA, and full fine-tuning with optimal parameters
- ⚡ **Hardware Optimization** - Automatic configuration for your GPU (RTX 4090/4080/4070/3060/4060)
- 🎨 **Modern UI** - Beautiful, responsive interface with real-time monitoring
- 🔄 **GGUF Conversion** - Convert models to GGUF format with advanced quantization
- 📈 **Real-time Monitoring** - Live training progress, metrics, and logs
- 💾 **Preset Management** - Save and load training configurations
- 🌐 **Cross-platform** - Windows, Linux, and macOS support

## 🎯 Supported Models

### Latest Models (2024)
- **Qwen3** (0.5B, 1.5B, 7B) - Alibaba's latest multilingual models
- **Phi-4** (14B) - Microsoft's newest reasoning model
- **Llama 3.3** (70B) - Meta's latest flagship model
- **DeepSeek V3** (7B) - Advanced reasoning capabilities
- **Yi-1.5** (9B) - 01.AI's improved model

### Established Models
- **Gemma** (270M, 2B) - Google's efficient models
- **Llama 3.2** (1B, 3B) - Meta's compact models
- **Qwen2.5** (0.5B, 1.5B) - Proven multilingual performance
- **Phi-3 Mini** - Microsoft's compact model
- **Mistral 7B** - High-performance general model
- **CodeLlama 7B** - Specialized for code generation

## 🛠️ Installation

### System Requirements

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| **OS** | Windows 10, Ubuntu 18.04, macOS 10.15 | Windows 11, Ubuntu 22.04, macOS 12+ |
| **Python** | 3.8+ | 3.10+ |
| **Node.js** | 16+ | 18+ |
| **RAM** | 8GB | 16GB+ |
| **Storage** | 10GB free | 50GB+ free |
| **GPU** | Optional | NVIDIA RTX 3060+ with 8GB+ VRAM |

### Automatic Installation (Recommended)

#### Linux/macOS
```bash
# One-line installation
curl -fsSL https://raw.githubusercontent.com/shaiqjamal/ggtune/main/install.sh | bash

# Or manual
git clone https://github.com/shaiqjamal/ggtune.git
cd ggtune
chmod +x install.sh
./install.sh
```

#### Windows
```cmd
# Download and run
git clone https://github.com/shaiqjamal/ggtune.git
cd ggtune
install.bat
```

### Manual Installation

#### 1. Clone Repository
```bash
git clone https://github.com/shaiqjamal/ggtune.git
cd ggtune
```

#### 2. Create Virtual Environment
```bash
# Linux/macOS
python3 -m venv venv
source venv/bin/activate

# Windows
python -m venv venv
venv\Scripts\activate
```

#### 3. Install Dependencies
```bash
# Upgrade pip
pip install --upgrade pip

# Install PyTorch (CUDA)
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121

# Install PyTorch (CPU only)
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cpu

# Install other dependencies
pip install -r requirements.txt

# Install Node.js dependencies
npm install
```

#### 4. Optional: Advanced Training Methods
```bash
# Unsloth (2-5x faster training)
pip install "unsloth[colab-new] @ git+https://github.com/unslothai/unsloth.git"

# Axolotl (YAML-based training)
pip install axolotl

# LLaMA-Factory (GUI training)
pip install llamafactory-cli
```

### Download Pre-built Packages
1. Visit [GitHub Releases](https://github.com/shaiqjamal/ggtune/releases)
2. Download for your platform:
   - **Linux**: `.AppImage`, `.deb`, `.rpm`
   - **Windows**: `.exe`, `.zip`
   - **macOS**: `.dmg`

## 🎮 Quick Usage Guide

### 1. **Model Training**
1. Open GGTune
2. Go to **Fine-tuning** tab
3. **Scan Directory** or select your model
4. **Load dataset** (any format - automatically converted)
5. **Click "Start Fine-tuning"** (everything auto-configured!)

### 2. **Model Conversion**
1. Go to **Conversion** tab
2. Select your model format (HuggingFace, LoRA, etc.)
3. Choose output format (GGUF with quantization)
4. **Click "Convert"**

### 3. **Dataset Management**
1. **Load any dataset** (Alpaca, ShareGPT, ChatML, etc.)
2. **Click "Analyze"** to check quality
3. **Click "Convert for Model"** to optimize for your selected model
4. **Preview conversion** to see the results

## 🔧 Advanced Features

### Dynamic Model Registry
- **Auto-detects** any HuggingFace model
- **Intelligent configuration** based on model architecture
- **Hardware optimization** for your specific GPU
- **Pattern matching** for new model families

### Smart Dataset Converter
- **Format detection** (Alpaca, ShareGPT, ChatML, Code, Q&A)
- **Model-specific conversion** with proper chat templates
- **Quality analysis** with metrics and recommendations
- **Duplicate removal** and data cleaning

### Professional Training
- **LoRA/QLoRA** fine-tuning with optimal parameters
- **Real-time monitoring** with progress bars and metrics
- **Preset management** for different projects
- **Automatic merging** and GGUF conversion

## 📊 Hardware Requirements

### Minimum Requirements
- **RAM:** 8GB
- **Storage:** 10GB free space
- **GPU:** Any CUDA-compatible GPU (optional)

### Recommended Configurations

| GPU | VRAM | Recommended Models | Batch Size |
|-----|------|-------------------|------------|
| RTX 4090 | 24GB | Any model up to 70B | Large |
| RTX 4080 | 16GB | Models up to 14B | Medium |
| RTX 4070 | 12GB | Models up to 7B | Medium |
| RTX 3060 | 12GB | Models up to 3B | Small |
| RTX 4060 | 8GB | Models up to 1.5B | Small |
| CPU Only | 16GB+ RAM | Small models only | Very Small |

## 🌟 Why Choose GGTune?

### For Researchers
- **Latest models** supported immediately
- **Reproducible results** with preset management
- **Comprehensive logging** for research papers
- **Open source** for transparency

### For Developers
- **Easy integration** with existing workflows
- **API support** for automation
- **Cross-platform** compatibility
- **Professional documentation**

### For Enterprises
- **Scalable** to multiple GPUs
- **Secure** local processing
- **Cost-effective** compared to cloud solutions
- **Professional support** available

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

### Ways to Contribute
- 🐛 **Report bugs** via [GitHub Issues](https://github.com/shaiqjamal/ggtune/issues)
- 💡 **Suggest features** in [Discussions](https://github.com/shaiqjamal/ggtune/discussions)
- 📝 **Improve documentation**
- 🔧 **Submit pull requests**
- 🌟 **Star the repository** to show support

### Development Setup
```bash
# Fork and clone your fork
git clone https://github.com/yourusername/ggtune.git
cd ggtune

# Create a feature branch
git checkout -b feature/amazing-feature

# Install development dependencies
npm install --dev
pip install -r requirements-dev.txt

# Make your changes and test
npm test
python -m pytest

# Submit a pull request
```

## 🔧 Building from Source

### Development Setup
```bash
# Clone and install
git clone https://github.com/shaiqjamal/ggtune.git
cd ggtune
npm install
pip install -r requirements-dev.txt

# Run in development mode
npm run dev
```

### Build Packages
```bash
# Build for all platforms
npm run build

# Build for specific platforms
npm run build:linux    # Linux packages
npm run build:win      # Windows packages
npm run build:mac      # macOS packages
```

### Package Types Generated
- **Linux**: AppImage, .deb, .rpm, .tar.gz
- **Windows**: .exe installer, portable .exe, .zip
- **macOS**: .dmg, .zip

## 🐛 Troubleshooting

### Common Issues

#### Installation Issues
```bash
# Python version issues
python3 --version  # Should be 3.8+
pip install --upgrade pip

# Node.js version issues
node --version     # Should be 16+
npm --version

# Permission issues (Linux/macOS)
sudo chown -R $USER:$USER ~/.npm
```

#### CUDA Issues
```bash
# Check CUDA installation
nvidia-smi

# Install CUDA toolkit
# Ubuntu/Debian
sudo apt install nvidia-cuda-toolkit

# Check PyTorch CUDA
python -c "import torch; print(torch.cuda.is_available())"
```

#### Memory Issues
```bash
# Reduce batch size in training
# Enable gradient checkpointing
# Use 4-bit quantization
# Close other applications
```

#### Training Method Issues
```bash
# Check available methods
python scripts/dependency_manager.py

# Install missing dependencies
pip install unsloth axolotl llamafactory-cli
```

### Getting Help
1. **Check Issues**: [GitHub Issues](https://github.com/shaiqjamal/ggtune/issues)
2. **Discussions**: [GitHub Discussions](https://github.com/shaiqjamal/ggtune/discussions)
3. **Email**: [shaiqjamal2@gmail.com](mailto:shaiqjamal2@gmail.com)
4. **Website**: [www.ggtune.com](https://www.ggtune.com)

### Reporting Bugs
Please include:
- Operating system and version
- Python and Node.js versions
- GPU information (if applicable)
- Error messages and logs
- Steps to reproduce

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Shaiq Jamal ZARIFI**
- 🌐 Website: [www.ggtune.com](https://www.ggtune.com)
- 📧 Email: [shaiqjamal2@gmail.com](mailto:shaiqjamal2@gmail.com)
- 🐙 GitHub: [@shaiqjamal](https://github.com/shaiqjamal)

## 🙏 Acknowledgments

- **HuggingFace** for the transformers library
- **Meta** for Llama models
- **Google** for Gemma models
- **Microsoft** for Phi models
- **Alibaba** for Qwen models
- **The open-source community** for continuous support

## 📈 Project Stats

<div align="center">

![GitHub stars](https://img.shields.io/github/stars/shaiqjamal/ggtune?style=social)
![GitHub forks](https://img.shields.io/github/forks/shaiqjamal/ggtune?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/shaiqjamal/ggtune?style=social)

</div>

## 🔮 Roadmap

### Version 2.1 (Q1 2025)
- [ ] **Cloud integration** (AWS, Azure, GCP)
- [ ] **Distributed training** across multiple machines
- [ ] **Model marketplace** for sharing fine-tuned models
- [ ] **Advanced analytics** dashboard

### Version 2.2 (Q2 2025)
- [ ] **Plugin system** for custom training methods
- [ ] **API endpoints** for programmatic access
- [ ] **Docker containers** for easy deployment
- [ ] **Kubernetes** support for enterprise

### Version 3.0 (Q3 2025)
- [ ] **AI-powered optimization** suggestions
- [ ] **Automated hyperparameter tuning**
- [ ] **Model compression** techniques
- [ ] **Edge deployment** support

---

<div align="center">

**Made with ❤️ by [Shaiq Jamal ZARIFI](https://github.com/shaiqjamal)**

[⭐ Star this repository](https://github.com/shaiqjamal/ggtune) if you find it useful!

</div>
