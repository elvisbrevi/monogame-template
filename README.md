# 🎮 MonoGame Project Template

A powerful and flexible template for creating cross-platform games using MonoGame Framework. This template provides a solid foundation for building 2D and 3D games that can run on multiple platforms.

## 📸 Screenshot

[Your game screenshot here]

## ✨ Features

- 🚀 Ready-to-use project structure
- 🎨 Basic content pipeline setup
- 🖼️ Example sprite loading and rendering
- 🎯 Cross-platform compatibility (Windows, macOS, Linux)
- 🛠️ Pre-configured development environment

## 🚀 Getting Started

### Prerequisites

- [.NET 8.0 SDK](https://dotnet.microsoft.com/download)
- [Visual Studio Code](https://code.visualstudio.com/) or [Visual Studio](https://visualstudio.microsoft.com/)
- [MonoGame Extension](https://marketplace.visualstudio.com/items?itemName=MonoGame.MonoGame-Templates-CSharp) (for Visual Studio)

### 🔧 Installation

1. Clone this repository:

```bash
git clone https://github.com/elvisbrevi/monogame-template.git
cd monogame-template
```

2. Build the project:

```bash
dotnet build
```

3. Run the game:

```bash
dotnet run
```

## 🎮 Project Structure

```
├── Content/            # Game assets and content
│   ├── Content.mgcb    # MonoGame Content Builder file
│   └── ...            # Your game assets
├── Game1.cs           # Main game class
└── Program.cs         # Entry point
```

## 🛠️ Development

### Adding Content

1. Open the Content Pipeline Tool:

```bash
mgcb-editor Content/Content.mgcb
```

2. Add your assets through the MGCB Editor
3. Build the content
4. Reference your content in the game using `Content.Load<T>()`

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📫 Contact

Your Name - [@elvisbrevi](https://twitter.com/elvisbrevi)

Project Link: [https://github.com/elvisbrevi/monogame-template](https://github.com/elvisbrevi/monogame-template)

## 🙏 Acknowledgments

- [MonoGame Framework](https://www.monogame.net/)
- [.NET Foundation](https://dotnetfoundation.org/)
