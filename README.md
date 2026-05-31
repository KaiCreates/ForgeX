<div align="center">

<!-- ForgeX Logo with Animation -->
<svg width="200" height="200" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg" style="animation: spin 20s linear infinite;">
  <defs>
    <linearGradient id="forgeGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0066FF;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#1A1A2E;stop-opacity:1" />
    </linearGradient>
    <style>
      @keyframes spin {
        from { transform: rotate(0deg); }
        to { transform: rotate(360deg); }
      }
      @keyframes pulse {
        0%, 100% { opacity: 1; }
        50% { opacity: 0.6; }
      }
      @keyframes glow {
        0%, 100% { filter: drop-shadow(0 0 5px #0066FF); }
        50% { filter: drop-shadow(0 0 15px #0066FF); }
      }
    </style>
  </defs>
  
  <!-- Outer Circle -->
  <circle cx="100" cy="100" r="95" fill="none" stroke="url(#forgeGradient)" stroke-width="3" style="animation: pulse 2s ease-in-out infinite;"/>
  
  <!-- Inner Forge Icon -->
  <g transform="translate(100, 100)">
    <!-- Hammer Head -->
    <rect x="-35" y="-45" width="35" height="40" rx="5" fill="#0066FF" style="animation: glow 2s ease-in-out infinite;"/>
    <!-- Hammer Handle -->
    <rect x="-5" y="-15" width="10" height="50" fill="#1A1A2E"/>
    <!-- Anvil -->
    <ellipse cx="25" cy="20" rx="25" ry="15" fill="#0066FF" style="animation: glow 2s ease-in-out infinite 0.5s;"/>
    <!-- X Accent -->
    <line x1="-15" y1="0" x2="15" y2="30" stroke="#00D4FF" stroke-width="3" stroke-linecap="round"/>
    <line x1="15" y1="0" x2="-15" y2="30" stroke="#00D4FF" stroke-width="3" stroke-linecap="round"/>
  </g>
</svg>

# 🔨 ForgeX

### Advanced Blender Toolkit for GTA V and FiveM Asset Development

*Created and maintained by Kai and Bobby*

---

</div>

<div style="background: linear-gradient(135deg, #0066FF 0%, #1A1A2E 100%); padding: 20px; border-radius: 15px; color: white; margin: 20px 0;">

## 🚀 Overview

ForgeX is a **modern Blender toolkit** designed to streamline the creation, editing, optimization, and export of GTA V and FiveM assets. Built upon the foundation of open-source community tooling, ForgeX combines powerful features with an intuitive interface.

</div>

---

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin: 30px 0;">

<!-- Features Section -->
<div style="background: #f8f9fa; border: 2px solid #0066FF; border-radius: 15px; padding: 20px;">

### ✨ Core Features

<svg width="100%" height="200" viewBox="0 0 300 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      @keyframes slideIn {
        from { transform: translateX(-300px); opacity: 0; }
        to { transform: translateX(0); opacity: 1; }
      }
      .feature-item { animation: slideIn 1s ease-out forwards; }
      .feature-1 { animation-delay: 0.1s; }
      .feature-2 { animation-delay: 0.3s; }
      .feature-3 { animation-delay: 0.5s; }
    </style>
  </defs>
  
  <g class="feature-item feature-1">
    <rect x="10" y="10" width="80" height="60" rx="8" fill="#0066FF" opacity="0.2" stroke="#0066FF" stroke-width="2"/>
    <text x="50" y="45" text-anchor="middle" font-size="24" fill="#0066FF">⚙️</text>
  </g>
  
  <g class="feature-item feature-2">
    <rect x="110" y="10" width="80" height="60" rx="8" fill="#0066FF" opacity="0.2" stroke="#0066FF" stroke-width="2"/>
    <text x="150" y="45" text-anchor="middle" font-size="24" fill="#0066FF">🎨</text>
  </g>
  
  <g class="feature-item feature-3">
    <rect x="210" y="10" width="80" height="60" rx="8" fill="#0066FF" opacity="0.2" stroke="#0066FF" stroke-width="2"/>
    <text x="250" y="45" text-anchor="middle" font-size="24" fill="#0066FF">📦</text>
  </g>
</svg>

- **Import & Export Tools** - Seamless asset pipeline
- **Auto Texture Detection** - Smart material recognition
- **Advanced Material Editor** - Professional controls
- **Vertex Color Support** - Full color management
- **Collision Generation** - Automatic mesh optimization
- **LOD Generation** - Performance optimization
- **Resource Packaging** - One-click export

</div>

<!-- Asset Types Section -->
<div style="background: #f8f9fa; border: 2px solid #1A1A2E; border-radius: 15px; padding: 20px;">

### 🎯 Supported Asset Types

<svg width="100%" height="200" viewBox="0 0 300 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      @keyframes fadeIn {
        from { opacity: 0; }
        to { opacity: 1; }
      }
      .asset-icon { animation: fadeIn 1s ease-in forwards; }
      .a1 { animation-delay: 0.1s; }
      .a2 { animation-delay: 0.2s; }
      .a3 { animation-delay: 0.3s; }
      .a4 { animation-delay: 0.4s; }
    </style>
  </defs>
  
  <circle cx="50" cy="50" r="35" fill="#1A1A2E" opacity="0.3" class="asset-icon a1"/>
  <text x="50" y="60" text-anchor="middle" font-size="30" class="asset-icon a1">🚗</text>
  
  <circle cx="130" cy="50" r="35" fill="#1A1A2E" opacity="0.3" class="asset-icon a2"/>
  <text x="130" y="60" text-anchor="middle" font-size="30" class="asset-icon a2">👕</text>
  
  <circle cx="210" cy="50" r="35" fill="#1A1A2E" opacity="0.3" class="asset-icon a3"/>
  <text x="210" y="60" text-anchor="middle" font-size="30" class="asset-icon a3">🎯</text>
  
  <circle cx="90" cy="130" r="35" fill="#1A1A2E" opacity="0.3" class="asset-icon a4"/>
  <text x="90" y="140" text-anchor="middle" font-size="30" class="asset-icon a4">🎬</text>
</svg>

- **Vehicles** - Car models & rigs
- **Clothing** - Armor, outfits & skins
- **Weapons** - Firearms & melee
- **Props** - World objects
- **Animations** - Character & object motion
- **Map Assets** - World building
- **Collision Files** - Physics geometry
- **Texture Dictionaries** - Material sets

</div>

</div>

---

<!-- FiveM Tools Section -->
<div style="background: linear-gradient(135deg, #1A1A2E 0%, #0066FF 100%); padding: 20px; border-radius: 15px; color: white; margin: 20px 0;">

## 🎮 FiveM Tools

<svg width="100%" height="150" viewBox="0 0 600 150" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      @keyframes bounce {
        0%, 100% { transform: translateY(0); }
        50% { transform: translateY(-10px); }
      }
      .fivem-box { animation: bounce 2s ease-in-out infinite; }
      .b1 { animation-delay: 0s; }
      .b2 { animation-delay: 0.2s; }
      .b3 { animation-delay: 0.4s; }
      .b4 { animation-delay: 0.6s; }
    </style>
  </defs>
  
  <g class="fivem-box b1">
    <rect x="20" y="30" width="120" height="100" rx="10" fill="rgba(255,255,255,0.1)" stroke="#00D4FF" stroke-width="2"/>
    <text x="80" y="85" text-anchor="middle" font-size="14" fill="white" font-weight="bold">One-Click</text>
    <text x="80" y="105" text-anchor="middle" font-size="12" fill="#00D4FF">Export</text>
  </g>
  
  <g class="fivem-box b2">
    <rect x="160" y="30" width="120" height="100" rx="10" fill="rgba(255,255,255,0.1)" stroke="#00D4FF" stroke-width="2"/>
    <text x="220" y="85" text-anchor="middle" font-size="14" fill="white" font-weight="bold">Resource</text>
    <text x="220" y="105" text-anchor="middle" font-size="12" fill="#00D4FF">Generator</text>
  </g>
  
  <g class="fivem-box b3">
    <rect x="300" y="30" width="120" height="100" rx="10" fill="rgba(255,255,255,0.1)" stroke="#00D4FF" stroke-width="2"/>
    <text x="360" y="85" text-anchor="middle" font-size="14" fill="white" font-weight="bold">FXManifest</text>
    <text x="360" y="105" text-anchor="middle" font-size="12" fill="#00D4FF">Generator</text>
  </g>
  
  <g class="fivem-box b4">
    <rect x="440" y="30" width="120" height="100" rx="10" fill="rgba(255,255,255,0.1)" stroke="#00D4FF" stroke-width="2"/>
    <text x="500" y="85" text-anchor="middle" font-size="14" fill="white" font-weight="bold">Validation &</text>
    <text x="500" y="105" text-anchor="middle" font-size="12" fill="#00D4FF">Analysis</text>
  </g>
</svg>

- ✅ **One-Click Resource Export** - Instant FiveM package generation
- 🏗️ **Resource Structure Generator** - Automatic folder organization
- 📝 **FXManifest Generator** - Complete manifest creation
- 🔍 **Asset Validation System** - Error detection & fixing
- ⚡ **Performance Analysis** - Optimization reports
- 🖼️ **Texture Optimization** - Size reduction without quality loss
- 📂 **Streaming Folder Builder** - Professional packaging

</div>

---

<!-- ForgeX Assistant Section -->
<div style="background: #f8f9fa; border-left: 5px solid #0066FF; border-radius: 15px; padding: 20px; margin: 20px 0;">

## 🤖 ForgeX Assistant

<svg width="100%" height="120" viewBox="0 0 400 120" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      @keyframes float {
        0%, 100% { transform: translateY(0px); }
        50% { transform: translateY(-10px); }
      }
      .assistant { animation: float 3s ease-in-out infinite; }
    </style>
  </defs>
  
  <g class="assistant">
    <!-- Brain -->
    <circle cx="50" cy="60" r="30" fill="none" stroke="#0066FF" stroke-width="2"/>
    <circle cx="45" cy="45" r="8" fill="#0066FF" opacity="0.6"/>
    <circle cx="55" cy="45" r="8" fill="#0066FF" opacity="0.6"/>
    <circle cx="50" cy="60" r="6" fill="#0066FF"/>
    
    <!-- Arrows to features -->
    <path d="M 85 30 L 130 30" stroke="#00D4FF" stroke-width="2" fill="none" marker-end="url(#arrowhead)"/>
    <path d="M 85 60 L 130 60" stroke="#00D4FF" stroke-width="2" fill="none" marker-end="url(#arrowhead)"/>
    <path d="M 85 90 L 130 90" stroke="#00D4FF" stroke-width="2" fill="none" marker-end="url(#arrowhead)"/>
    
    <defs>
      <marker id="arrowhead" markerWidth="10" markerHeight="10" refX="9" refY="3" orient="auto">
        <polygon points="0 0, 10 3, 0 6" fill="#00D4FF" />
      </marker>
    </defs>
    
    <!-- Feature boxes -->
    <rect x="130" y="15" width="100" height="30" rx="5" fill="#0066FF" opacity="0.2" stroke="#0066FF" stroke-width="1"/>
    <text x="180" y="35" text-anchor="middle" font-size="12" fill="#0066FF" font-weight="bold">Validation</text>
    
    <rect x="130" y="45" width="100" height="30" rx="5" fill="#0066FF" opacity="0.2" stroke="#0066FF" stroke-width="1"/>
    <text x="180" y="65" text-anchor="middle" font-size="12" fill="#0066FF" font-weight="bold">Detection</text>
    
    <rect x="130" y="75" width="100" height="30" rx="5" fill="#0066FF" opacity="0.2" stroke="#0066FF" stroke-width="1"/>
    <text x="180" y="95" text-anchor="middle" font-size="12" fill="#0066FF" font-weight="bold">Recommendations</text>
    
    <rect x="250" y="35" width="120" height="50" rx="5" fill="#1A1A2E" opacity="0.1" stroke="#1A1A2E" stroke-width="1"/>
    <text x="310" y="58" text-anchor="middle" font-size="11" fill="#1A1A2E" font-weight="bold">Automated Workflows</text>
  </g>
</svg>

- 🔎 **Project Validation** - Check project integrity
- 🚨 **Missing Asset Detection** - Identify missing files
- 💡 **Material Recommendations** - Smart suggestions
- 📊 **Optimization Reports** - Performance insights
- ⚙️ **Automated Workflow Tools** - Streamlined processes

</div>

---

<!-- Requirements & Installation -->
<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin: 30px 0;">

<div style="background: #f8f9fa; border: 2px solid #0066FF; border-radius: 15px; padding: 20px;">

## 📋 Requirements

- **Blender 4.0+** - Latest version recommended
- **GTA V Modding Knowledge** - Recommended
- **FiveM Development Knowledge** - Helpful but not required
- **Python 3.8+** - For advanced scripting

</div>

<div style="background: #f8f9fa; border: 2px solid #1A1A2E; border-radius: 15px; padding: 20px;">

## 📥 Installation

1. Download the latest **ForgeX release**
2. Open Blender and go to:
   ```
   Edit → Preferences → Add-ons → Install
   ```
3. Select the ForgeX package
4. **Enable the addon**
5. Start creating! 🚀

</div>

</div>

---

<!-- Community Section -->
<div style="background: linear-gradient(135deg, #00D4FF 0%, #0066FF 100%); padding: 30px; border-radius: 15px; color: white; margin: 20px 0;">

## 🌍 Community & Support

<svg width="100%" height="100" viewBox="0 0 400 100" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      @keyframes rotate {
        from { transform: rotate(0deg); }
        to { transform: rotate(360deg); }
      }
      .community-icon { animation: rotate 20s linear infinite; }
    </style>
  </defs>
  
  <g class="community-icon" transform="translate(200, 50)">
    <circle cx="0" cy="0" r="45" fill="none" stroke="rgba(255,255,255,0.3)" stroke-width="2"/>
    <circle cx="0" cy="-40" r="12" fill="white" opacity="0.8"/>
    <circle cx="35" cy="20" r="12" fill="white" opacity="0.8"/>
    <circle cx="-35" cy="20" r="12" fill="white" opacity="0.8"/>
    <text x="0" y="10" text-anchor="middle" font-size="20">🤝</text>
  </g>
</svg>

Join our thriving community to:

| 📚 Documentation | 🎥 Tutorials | 💬 Support | 🗺️ Roadmap |
|:---:|:---:|:---:|:---:|
| User Guides & Docs | Video Walkthroughs | Community Support | Development Plans |
| In-depth Guides | Step-by-step Videos | Direct Assistance | Feature Requests |
| API Reference | Best Practices | Bug Reports | Milestones |

</div>

---

<!-- Vision Section -->
<div style="background: #1A1A2E; color: white; padding: 30px; border-radius: 15px; text-align: center; margin: 20px 0; border: 2px solid #0066FF;">

## 🎯 Our Vision

<svg width="100%" height="80" viewBox="0 0 400 80" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      @keyframes expandRing {
        0% { r: 5; opacity: 1; }
        100% { r: 40; opacity: 0; }
      }
      .ring { animation: expandRing 2s ease-out infinite; }
      .ring1 { animation-delay: 0s; }
      .ring2 { animation-delay: 0.5s; }
      .ring3 { animation-delay: 1s; }
    </style>
  </defs>
  
  <circle cx="50" cy="40" r="15" fill="#0066FF"/>
  <circle cx="50" cy="40" r="5" fill="white" class="ring ring1"/>
  <circle cx="50" cy="40" r="5" fill="white" class="ring ring2"/>
  <circle cx="50" cy="40" r="5" fill="white" class="ring ring3"/>
  
  <text x="200" y="45" font-size="16" fill="white" font-weight="bold">
    Complete Blender-to-FiveM Pipeline
  </text>
</svg>

**ForgeX** aims to provide creators with a **complete, integrated workflow** that:

- ✅ Eliminates unnecessary external tools
- ✅ Reduces development time through automation
- ✅ Provides intelligent validation & suggestions
- ✅ Streamlines asset creation & optimization
- ✅ Empowers creators to focus on creativity

**Built for creators. Designed for FiveM.**

— **Kai & Bobby** 🚀

</div>

---

<div align="center">

### 💪 Start Forging Today

[⬇️ Download ForgeX](#installation) | [📖 Read Docs](#community--support) | [🎥 Watch Tutorials](#community--support)

---

**Made with ❤️ for the modding community**

</div>