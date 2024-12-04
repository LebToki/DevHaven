DevHaven Development Environment
=================================

**Author**: Tarek Tarabichi  
**GitHub**: https://github.com/lebToki/  
**Website**: https://2tinteractive.com

---

### Introduction
DevHaven is a modern, flexible, and developer-focused development stack inspired by Laragon, designed for multi-profile project management. Its core purpose is to provide developers with isolated, customizable, and lightweight development environments.

---

### Planned Features

#### Core Features
1. **Multi-Profile Management**
    - Bundle environment configurations per project.
    - Specify unique versions of software for each profile.
    - Quickly switch between profiles without restarting the entire stack.

2. **Lightweight and Portable**
    - Fully portable stack with no need for system-wide installations.
    - Can run from any directory or external drive.

3. **Cross-Platform Support**
    - Initial focus on Windows.
    - Planned support for Linux and macOS.

#### Software and Services
1. **Core Services**:
    - Apache
    - PHP (multiple versions)
    - MySQL/MariaDB
    - Node.js
    - Python
    - Nginx (optional)

2. **Dynamic Service Management**
    - Start, stop, and restart individual services per profile.
    - Wrapper scripts to isolate binaries for profile-specific environments.

3. **SSL Support**
    - Automatic SSL certificate generation for local domains.
    - Ability to import user-provided SSL certificates.

#### Usability Enhancements
1. **GUI Control Panel**:
    - Start and stop services with a click.
    - Easily switch between profiles.
    - Manage logs and configurations through an intuitive interface.

2. **CLI Interface**:
    - Manage profiles, services, and configurations from the command line.
    - Example commands:
        - `devstack create-profile <profile_name>`
        - `devstack use-profile <profile_name>`
        - `devstack start`
        - `devstack list-profiles`

3. **Profiles and Configurations**:
    - `profile.toml` for project-specific settings.
    - Templates for common configurations (e.g., PHP `php.ini`, Apache `.conf`).

#### Developer-Focused Features
1. **Customizable Environment**:
    - Fine-tune software versions and configurations.
    - Support for environment variables specific to projects.

2. **Version Control and Testing**:
    - Run and test projects on multiple versions of PHP, Node.js, etc.
    - Easily validate backward compatibility.

3. **Performance Optimization**:
    - Lightweight binaries and minimal system resource usage.
    - Optimized for quick startup times.

4. **Team Collaboration**:
    - Share profiles across teams to ensure consistent environments.

---

### Example Workflow
```bash
# Create a new profile for a project
devstack create-profile ProjectA

# Switch to the new profile
devstack use-profile ProjectA

# Start the stack with profile-specific services
devstack start

# List all available profiles
devstack list-profiles
```

---

### License
DevHaven is released under the MIT License.

---

### Contact
For questions, suggestions, or contributions, visit my [GitHub](https://github.com/lebToki/) or [website](https://2tinteractive.com).
