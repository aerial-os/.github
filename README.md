# 🚁 AerialOS

**Universal Drone Operating System — Open Source Ground Control for Any Drone**

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Discord](https://img.shields.io/discord/XXXXXXXXX?color=7289da&label=Discord&logo=discord&logoColor=white)](https://discord.gg/aerialos)
[![GitHub Stars](https://img.shields.io/github/stars/aerial-os/aerialos?style=social)](https://github.com/aerial-os/aerialos)

---

## 🎯 Mission

Break free from locked-down phone apps and proprietary SDKs. AerialOS lets you control **any drone** from your laptop with real AI-powered autonomy.
```python
from aerialos import Drone

drone = Drone.connect("n11_pro_gps")
drone.takeoff()
drone.enable_tracking(model="yolov8")  # Real-time AI tracking
drone.land()
```

---

## ✨ Features

| Feature | Community (Free) | Enterprise |
|---------|-----------------|------------|
| Multi-drone support | ✅ | ✅ |
| Live video streaming | ✅ | ✅ |
| AI object detection | ✅ (150-250ms) | ✅ (<50ms) |
| Autonomous waypoints | ✅ | ✅ |
| Swarm coordination | ❌ | ✅ |
| TensorRT optimization | ❌ | ✅ |
| 24/7 Support | ❌ | ✅ |

---

## 🚀 Quick Start
```bash
# Install
pip install aerialos

# Connect to your drone's WiFi, then:
aerialos connect --discover
aerialos stream --display
aerialos fly --interactive
```

---

## 📦 Repositories

| Repository | Description |
|------------|-------------|
| [aerialos](https://github.com/aerial-os/aerialos) | Core platform - Python SDK & CLI |
| [aerialos-ui](https://github.com/aerial-os/aerialos-ui) | Blazor WebAssembly ground control station |
| [aerialos-protocols](https://github.com/aerial-os/aerialos-protocols) | Drone protocol reverse engineering & docs |
| [aerialos-ml](https://github.com/aerial-os/aerialos-ml) | ML models for tracking, detection, following |

---

## 🤝 Contributing

We welcome contributions! See our [Contributing Guide](https://github.com/aerial-os/aerialos/blob/main/CONTRIBUTING.md).

- 💬 [Discord Community](https://discord.gg/aerialos)
- 🐛 [Report Issues](https://github.com/aerial-os/aerialos/issues)
- 📖 [Documentation](https://docs.aerialos.dev)

---

## 📄 License

MIT License — Free for personal and commercial use.

---

<p align="center">
  <b>Built with ❤️ for the drone community</b><br>
  <i>"One Platform. Any Drone. Real AI."</i>
</p>
