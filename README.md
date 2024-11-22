# DevHaven: The Modern Stack Manager

## Welcome Laragon Community and Developers!

Are you a fan of Laragon and looking for a modern, actively maintained alternative? Welcome to **DevHaven**, a next-generation stack controller designed for simplicity, flexibility, and modern development workflows.

## Why DevHaven?
DevHaven builds on the strengths of Laragon while introducing new features to adapt to evolving developer needs. It’s your all-in-one stack manager for PHP, MySQL, Apache, Node.js, Python, and beyond.

### Key Features:
- **Auto Virtual Hosts**: Seamlessly manage your local development domains. Just drop your project into the `www` directory and get a pretty URL like `http://project.test`.
- **Quick Apps**: Easily download, set up, and manage popular frameworks like Laravel, WordPress, Joomla, and more.
- **Service Management**: Start, stop, and restart services like Apache, MySQL, Redis, and more—right from the GUI.
- **Modern GUI with Fyne**: A lightweight, cross-platform graphical interface powered by the Fyne library.
- **Cross-Platform**: Windows-first with plans for Linux and macOS compatibility.
- **Extensible**: Add your own services, apps, and configurations.

## Current Status
We’re actively developing the core features and refining the GUI. Contributions, feedback, and feature requests are welcome.

## How to Get Involved?
1. **Test the App**: Clone the repository and build the app using Go.
2. **Contribute**: Fork the repo, fix bugs, add features, and submit pull requests.
3. **Share Ideas**: Open issues for feature requests, feedback, or suggestions.

## Join the Community
This project is an open invitation to the Laragoners. Let’s create a vibrant community around DevHaven and ensure a reliable stack manager for all developers.

### Planned Features:
- **Certificate Management**: Auto-generate and manage SSL certificates for local development.
- **Multi-Version Support**: Run multiple PHP, MySQL, or Node.js versions side-by-side.
- **Cloud Integration**: Seamlessly deploy projects to AWS, DigitalOcean, or other cloud providers.
- **Docker Support**: Add Docker container orchestration for advanced workflows.

## Installation
### Requirements:
- Go 1.18 or later
- MinGW-w64 (for Windows)
- GCC 64-bit
- Fyne library for GUI

### Build and Run:
```bash
git clone https://github.com/LebToki/DevHaven.git
cd DevHaven/devhaven-controller
go mod tidy
go run main.go
```

## Contributing
Pull requests, issues, and ideas are welcome! Check out our `CONTRIBUTING.md` for details.

## License
This project is licensed under the MIT License.

---

### Acknowledgments
Thank you to the Laragon community for inspiring this project. Let’s build something amazing together!

---

### Stay Connected
- GitHub: [DevHaven Repo](https://github.com/LebToki/DevHaven)
- Issues: [Submit Feedback](https://github.com/LebToki/DevHaven/issues)
