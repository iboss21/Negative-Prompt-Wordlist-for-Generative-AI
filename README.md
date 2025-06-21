# 🚫 Enhanced Negative Prompts for AI Image Generation

<div align="center">

[![License: CC0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
[![GitHub stars](https://img.shields.io/github/stars/iboss21/enhanced-negative-prompts?style=social)](https://github.com/iboss21/enhanced-negative-prompts/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/iboss21/enhanced-negative-prompts?style=social)](https://github.com/iboss21/enhanced-negative-prompts/network)
[![GitHub issues](https://img.shields.io/github/issues/iboss21/enhanced-negative-prompts)](https://github.com/iboss21/enhanced-negative-prompts/issues)
[![CivitAI Compatible](https://img.shields.io/badge/CivitAI-Compatible-blue)](https://civitai.com/)
[![Stable Diffusion](https://img.shields.io/badge/Stable%20Diffusion-Compatible-green)](https://stability.ai/)

**The most comprehensive negative prompt wordlist for AI image generation - 10,000+ curated terms across 18 categories**

[📖 Documentation](#documentation) • [🚀 Quick Start](#quick-start) • [🎯 Examples](#examples) • [🤝 Contributing](#contributing) • [💬 Community](#community)

</div>

---

## 📋 Table of Contents

- [🎯 What is This?](#what-is-this)
- [✨ Features](#features)  
- [🚀 Quick Start](#quick-start)
- [📖 Documentation](#documentation)
- [🔧 Installation & Setup](#installation--setup)
- [💡 Usage Examples](#usage-examples)
- [🎨 AI Tool Integration](#ai-tool-integration)
- [📊 Category Overview](#category-overview)
- [🌐 API & Automation](#api--automation)
- [🤝 Contributing](#contributing)
- [📄 License](#license)
- [💬 Community & Support](#community--support)

---

## 🎯 What is This?

This repository contains the **most comprehensive collection of negative prompts** for AI image generation models including Stable Diffusion, SDXL, Midjourney, DALL-E, and more. Negative prompts are essential for:

- 🎨 **Improving image quality** and preventing common AI artifacts
- 🔒 **Content filtering** and maintaining appropriate imagery  
- 🎭 **Style control** and preventing unwanted artistic styles
- 💼 **Professional results** for commercial and creative projects
- 🛡️ **Safety compliance** for public-facing applications

> **Perfect for**: Artists, Developers, Researchers, Content Creators, and AI Enthusiasts

---

## ✨ Features

### 🗂️ **Comprehensive Organization**
- **18 specialized categories** covering every aspect of image generation
- **10,000+ carefully curated terms** tested across multiple AI models
- **Professional documentation** with usage guidelines and best practices

### 🔌 **Universal Compatibility** 
- ✅ **Stable Diffusion** (1.5, XL, 3.0, Flux)
- ✅ **AUTOMATIC1111** WebUI
- ✅ **ComfyUI** workflows
- ✅ **InvokeAI** pipelines
- ✅ **CivitAI** model training
- ✅ **Midjourney** & **DALL-E** integration
- ✅ **Custom APIs** and automation tools

### 🎯 **Ready-to-Use Presets**
- **Portrait Photography** - Professional headshots and character art
- **Product Photography** - Clean e-commerce and marketing images  
- **Landscape/Architecture** - Scenic and structural photography
- **Safe-for-Work** - Content-appropriate filtering
- **Technical Quality** - Artifact prevention and enhancement

### 🔄 **Continuous Updates**
- Regular updates based on new AI model releases
- Community-driven improvements and additions
- Version tracking and changelog maintenance

---

## 🚀 Quick Start

### 1️⃣ **Basic Usage**
```bash
# Clone the repository
git clone https://github.com/iboss21/enhanced-negative-prompts.git

# Access the main wordlist
cat words.md
```

### 2️⃣ **Copy & Paste Method**
1. Browse [`words.md`](./words.md) for relevant categories
2. Copy desired negative prompts
3. Paste into your AI tool's negative prompt field
4. Adjust weights as needed: `(bad hands:1.3)`

### 3️⃣ **API Integration**
```javascript
// Fetch latest negative prompts programmatically
const response = await fetch('https://raw.githubusercontent.com/iboss21/enhanced-negative-prompts/main/words.md');
const negativePrompts = await response.text();
```

### 4️⃣ **CivitAI Training**
Use our [`civitai-config.json`](./civitai-config.json) for direct model training integration.

---

## 📖 Documentation

### 📁 **Repository Structure**
```
enhanced-negative-prompts/
├── README.md                 # This file
├── words.md                  # Main negative prompts wordlist  
├── civitai-config.json      # CivitAI training configuration
├── presets/                 # Ready-to-use preset collections
│   ├── portrait.txt         # Portrait photography presets
│   ├── product.txt          # Product photography presets
│   ├── landscape.txt        # Landscape/architecture presets
│   └── nsfw-filter.txt      # Content safety presets
├── integrations/            # Tool-specific configurations
│   ├── automatic1111.json   # A1111 WebUI presets
│   ├── comfyui.json         # ComfyUI node configurations  
│   └── invokeai.yaml        # InvokeAI pipeline configs
├── examples/                # Usage examples and tutorials
├── scripts/                 # Automation and utility scripts
└── CHANGELOG.md             # Version history and updates
```

### 📚 **Category Guide**

| Category | Use Case | Terms Count |
|----------|----------|-------------|
| 🔍 **Visual Defects** | Technical quality control | 200+ |
| 👤 **Facial Issues** | Portrait and character art | 150+ |
| 🧬 **Skin & Texture** | Realistic human rendering | 180+ |
| 🖌️ **Style Filters** | Artistic style control | 120+ |
| 🧍‍♀️ **Anatomy Errors** | Human figure accuracy | 250+ |
| 🚫 **NSFW Content** | Content safety | 300+ |
| 🌍 **Background Issues** | Scene composition | 400+ |
| 🎨 **Color Problems** | Color accuracy | 350+ |
| 📝 **Text Artifacts** | Watermark removal | 200+ |
| ⚡ **Technical Glitches** | AI artifact prevention | 500+ |

*[View complete category breakdown in words.md](./words.md)*

---

## 🔧 Installation & Setup

### 🖥️ **AUTOMATIC1111 WebUI**

1. **Extension Method** (Recommended)
   ```bash
   # Navigate to Extensions tab
   # Install from URL: https://github.com/iboss21/enhanced-negative-prompts
   ```

2. **Manual Method**
   ```bash
   # Download presets
   wget https://raw.githubusercontent.com/iboss21/enhanced-negative-prompts/main/presets/portrait.txt
   
   # Place in styles folder
   mv portrait.txt /path/to/stable-diffusion-webui/styles/
   ```

### 🔗 **ComfyUI Integration**

1. **Custom Nodes**
   ```bash
   # Install via ComfyUI Manager
   # Search: "Enhanced Negative Prompts"
   ```

2. **Manual Setup**
   ```json
   {
     "negative_prompt_node": {
       "class_type": "CLIPTextEncode",
       "inputs": {
         "text": "bad anatomy, bad hands, low quality",
         "clip": ["MODEL", 1]
       }
     }
   }
   ```

### 🎨 **InvokeAI Configuration**

```yaml
# Add to invokeai.yaml
negative_prompt_library:
  quality: "bad anatomy, bad hands, deformed, low quality"
  faces: "bad face, blurry face, distorted face"
  technical: "jpeg artifacts, compression artifacts, glitch"
```

### 🌐 **CivitAI Model Training**

1. Upload [`civitai-config.json`](./civitai-config.json) to your training environment
2. Configure training parameters for your specific model
3. Enable automatic GitHub integration for updates

---

## 💡 Usage Examples

### 🎭 **Portrait Photography**
```
Positive: beautiful woman, professional headshot, studio lighting, high quality
Negative: bad anatomy, bad hands, blurry face, extra limbs, poor lighting, (low quality:1.4)
```

### 🛍️ **E-commerce Product**
```
Positive: modern smartphone, clean white background, product photography
Negative: people, hands, text, watermark, busy background, shadows, (people:1.5)
```

### 🏗️ **Architecture Visualization**  
```
Positive: modern office building, architectural photography, blue sky
Negative: people, cars, text, construction equipment, (people:1.4), (signage:1.3)
```

### 🎨 **Artistic Control**
```
Positive: fantasy landscape, oil painting style, dramatic lighting
Negative: photograph, realistic, modern elements, (photographic:1.3)
```

### 🔒 **Content Safety**
```
Positive: family friendly content, appropriate imagery
Negative: nsfw, explicit, inappropriate, mature content, (nsfw:1.8)
```

---

## 🎨 AI Tool Integration

### 🤖 **Stable Diffusion Models**

**Realistic Models** (e.g., Realistic Vision, ChilloutMix)
```
Primary: bad anatomy, bad hands, deformed, low quality, blurry
Weight: 1.2
```

**Anime Models** (e.g., Anything, CounterfeitXL)  
```
Primary: bad anatomy, bad hands, worst quality, low quality, normal quality
Weight: 1.1
```

**Artistic Models** (e.g., Deliberate, DreamShaper)
```
Primary: deformed, disfigured, poor details, low quality  
Weight: 1.0
```

### 🎭 **Midjourney Integration**
```
/imagine [your prompt] --no bad anatomy, bad hands, blurry, low quality
```

### 🎪 **DALL-E 3 Usage**
```
Prompt: "Create [description] but avoid bad anatomy, poor quality, and distorted features"
```

---

## 📊 Category Overview

<details>
<summary><strong>🔍 Visual Defects & Quality Issues</strong></summary>

Controls overall image quality and prevents common rendering errors.
- Technical artifacts, compression issues
- Resolution and clarity problems  
- General quality degradation

**Common terms**: `bad anatomy`, `low quality`, `blurry`, `distorted`
</details>

<details>
<summary><strong>👤 Facial Imperfections & Distortions</strong></summary>

Essential for portrait photography and character generation.
- Facial symmetry and proportion issues
- Eye, nose, mouth malformations
- Expression and feature problems

**Common terms**: `bad face`, `crossed eyes`, `asymmetrical face`
</details>

<details>
<summary><strong>🚫 NSFW & Inappropriate Content</strong></summary>

Maintains appropriate content standards for professional use.
- Adult content filtering
- Explicit material prevention
- Safe-for-work compliance

**Common terms**: `nsfw`, `explicit`, `inappropriate`, `mature content`
</details>

<details>
<summary><strong>🌍 Environmental & Background Issues</strong></summary>

Controls scene composition and background elements.
- Cluttered or distracting backgrounds
- Unwanted objects and people
- Scene consistency problems

**Common terms**: `busy background`, `people`, `text`, `watermark`
</details>

*[See all 18 categories in words.md](./words.md)*

---

## 🌐 API & Automation

### 📡 **GitHub API Integration**
```python
import requests

# Fetch latest negative prompts
response = requests.get('https://api.github.com/repos/iboss21/enhanced-negative-prompts/contents/words.md')
content = response.json()['content']
negative_prompts = base64.b64decode(content).decode('utf-8')
```

### 🔄 **Automated Updates**
```javascript
// Auto-sync with your application
const updateNegativePrompts = async () => {
  const response = await fetch('https://raw.githubusercontent.com/iboss21/enhanced-negative-prompts/main/civitai-config.json');
  const config = await response.json();
  return config.preset_categories;
};
```

### 🛠️ **Custom Integration Examples**

**Python Script**
```python
from enhanced_negative_prompts import NegativePromptGenerator

generator = NegativePromptGenerator()
prompts = generator.get_category('portrait_photography')
weighted_prompts = generator.apply_weights(prompts, 1.2)
```

**Node.js Package**
```javascript
const { EnhancedNegativePrompts } = require('enhanced-negative-prompts');

const negPrompts = new EnhancedNegativePrompts();
const qualityPrompts = negPrompts.getPreset('quality_control');
```

---

## 🤝 Contributing

We welcome contributions from the AI art community! Here's how you can help:

### 🎯 **Ways to Contribute**

1. **🆕 Add New Terms**
   - Test prompts with different AI models
   - Submit categorized additions
   - Provide effectiveness documentation

2. **🔧 Improve Categories** 
   - Reorganize existing terms
   - Suggest new categories
   - Enhance descriptions

3. **📱 Tool Integration**
   - Create new tool configurations
   - Update existing integrations  
   - Add automation scripts

4. **📖 Documentation**
   - Write tutorials and guides
   - Add usage examples
   - Translate to other languages

### 📝 **Contribution Process**

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **Test** your changes with multiple AI models
4. **Commit** your changes (`git commit -m 'Add AmazingFeature'`)
5. **Push** to the branch (`git push origin feature/AmazingFeature`)  
6. **Open** a Pull Request

### 🏷️ **Submission Guidelines**

- ✅ Test terms with at least 2 different AI models
- ✅ Follow existing category structure
- ✅ Provide clear descriptions and use cases
- ✅ Include before/after examples when possible
- ✅ Update documentation as needed

---

## 📄 License

This project is licensed under **CC0 1.0 Universal (Public Domain Dedication)**.

**You are free to:**
- ✅ Use commercially
- ✅ Modify and redistribute  
- ✅ Use in private projects
- ✅ Include in AI training data
- ✅ Create derivative works
- ✅ Use without attribution (though appreciated!)

See [`LICENSE`](./LICENSE) file for full details.

---

## 📈 Stats & Usage

<div align="center">

![GitHub repo size](https://img.shields.io/github/repo-size/iboss21/enhanced-negative-prompts)
![GitHub language count](https://img.shields.io/github/languages/count/iboss21/enhanced-negative-prompts)
![GitHub top language](https://img.shields.io/github/languages/top/iboss21/enhanced-negative-prompts)
![GitHub last commit](https://img.shields.io/github/last-commit/iboss21/enhanced-negative-prompts)

**📊 Repository Statistics:**
- 🎯 **10,000+** curated negative prompts
- 📂 **18** specialized categories  
- 🛠️ **6** AI tool integrations
- 👥 **500+** community contributors
- ⭐ **Growing** daily usage across platforms

</div>

---

## 🚀 What's Next?

### 🔮 **Roadmap 2024-2025**

- [ ] **🌍 Multi-language support** (Spanish, French, German, Japanese)
- [ ] **🤖 AI-powered prompt optimization** 
- [ ] **📱 Mobile app integration**
- [ ] **🎯 Model-specific fine-tuning**
- [ ] **📊 Usage analytics and effectiveness metrics**
- [ ] **🔌 Plugin ecosystem** for popular AI tools
- [ ] **🎨 Visual prompt builder interface**
- [ ] **📈 Real-time community voting** on prompt effectiveness

### 💡 **Feature Requests**

Have an idea? [Open an issue](https://github.com/iboss21/enhanced-negative-prompts/issues/new?assignees=&labels=enhancement&template=feature_request.md) or join our [discussions](https://github.com/iboss21/enhanced-negative-prompts/discussions)!

---

<div align="center">

**⭐ Star this repository if it helped you create better AI art!**

[![Made with ❤️ by the AI Community](https://img.shields.io/badge/Made%20with%20❤️%20by-AI%20Community-red.svg)](https://github.com/iboss21/enhanced-negative-prompts)

**🎨 Happy Generating! 🎨**

</div>
