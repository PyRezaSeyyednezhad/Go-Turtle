# Go-Turtle

A Turtle graphics implementation in Go, inspired by Python's turtle module, providing an interactive way to learn programming and create graphics.

## 🚀 Features

- **Turtle Graphics**: Classic turtle graphics commands (forward, backward, left, right, etc.)
- **Multiple Drawing Modes**: 
  - **Manual Mode**: Step-by-step turtle control
  - **Custom Draw Mode**: Define your own drawing patterns
  - **Preset Mode**: Built-in geometric patterns
- **Color Support**: Set pen color for vibrant drawings
- **Speed Control**: Adjustable drawing speed
- **Canvas Operations**: Clear screen, reset turtle position, and more
- **Interactive CLI**: User-friendly command-line interface

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/PyRezaSeyyednezhad/Go-Turtle.git

# Navigate to the project directory
cd Go-Turtle

# Run the program
go run main.go
```

## 🎮 Usage

### Interactive Mode

Run the program and follow the interactive menu:

```bash
go run main.go
```

You'll see:
```
████████ ██    ██ ██████  ████████ ██      ███████ 
   ██     ██  ██  ██   ██    ██    ██      ██     
   ██      ████   ██████     ██    ██      ███████ 
   ██       ██    ██   ██    ██    ██           ██ 
   ██       ██    ██████     ██    ███████ ███████ 

Choose Drawing Mode:
1. Manual Mode
2. Custom Draw Mode
3. Preset Mode
4. Exit
```

### Modes

#### 1. Manual Mode
Control the turtle step by step with commands:
- `f` or `forward`: Move forward
- `b` or `backward`: Move backward
- `l` or `left`: Turn left
- `r` or `right`: Turn right
- `c` or `color`: Change pen color
- `s` or `speed`: Change drawing speed
- `clear`: Clear the screen
- `home`: Return to starting position
- `exit`: Exit to main menu

#### 2. Custom Draw Mode
Define custom drawing patterns using turtle commands. Example pattern:
```
f 100
r 90
f 50
l 45
f 75
```

#### 3. Preset Mode
Choose from built-in patterns:
- Square
- Circle
- Triangle
- Star
- Spiral

## 📁 Project Structure

```
Go-Turtle/
├── main.go              # Main entry point
├── README.md            # This file
├── .gitignore          # Git ignore file
└── docs/               # Documentation
    └── HowToUse.txt    # Detailed usage instructions
```

## 🔧 Implementation Details

The project implements a `Turtle` struct with methods for:
- Movement (`Forward()`, `Backward()`)
- Rotation (`Left()`, `Right()`)
- Drawing control (`PenUp()`, `PenDown()`)
- Canvas operations (`Clear()`, `Home()`)
- Appearance control (`SetColor()`, `SetSpeed()`)

The turtle maintains:
- Current position (x, y)
- Heading direction
- Pen state (up/down)
- Drawing color
- Movement speed

## 🎨 Examples

### Draw a Square
```go
// In Custom Draw Mode:
f 100
r 90
f 100
r 90
f 100
r 90
f 100
```

### Draw a Circle
```go
// Using Preset Mode -> Circle
// Or manually:
repeat 36 {
    f 10
    r 10
}
```

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Areas for Contribution:
- Add new preset patterns
- Implement color gradients
- Add save/load functionality for drawings
- Create a GUI interface
- Add unit tests
- Improve documentation

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Inspired by Python's turtle graphics module
- Thanks to all contributors who have helped with this project

## 📞 Support

For questions, issues, or suggestions:
- Open an [Issue](https://github.com/PyRezaSeyyednezhad/Go-Turtle/issues)
- Check the [docs/HowToUse.txt](docs/HowToUse.txt) for detailed instructions

---

**Happy Coding! 🐢✨**

*Built with Go and ❤️ by the Go-Turtle community*
