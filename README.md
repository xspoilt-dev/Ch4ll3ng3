# Ch4ll3ng3 - Change The Response!

Welcome to the Ch4ll3ng3 repository! This project is designed for those interested in binary patching challenges using the powerful tool Radare2. In this repository, you will find a collection of executable files that are specifically crafted for this purpose.

## Table of Contents
- [Installation](#installation)
- [Challenge Overview](#challenge-overview)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Installation

To get started with the Ch4ll3ng3 project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/xspoilt-dev/Ch4ll3ng3.git
   ```

2. Navigate into the project directory:
   ```bash
   cd Ch4ll3ng3
   ```

3. Make all scripts executable:
   ```bash
   cd binary-patching
   ```

4. Run the challenge:
   ```bash
   ls
   ```

## Challenge Overview

The `binary-patching` folder contains 10 ELF (Executable and Linkable Format) files. Each of these files presents a unique challenge that requires binary patching skills to solve. The goal is to modify the binaries in such a way that you can change their responses or behaviors.

## Usage

To tackle the challenges, you will need to use Radare2, a powerful open-source framework for reverse engineering and analyzing binaries. Here are some basic commands to get you started with Radare2:

- Open a binary:
  ```bash
  r2 <binary_file>
  ```

- Analyze the binary:
  ```bash
  [0x00000000]> aaa
  ```

- Patch the binary:
  ```bash
  [0x00000000]> wx <new_bytes>
  ```

- Save the patched binary:
  ```bash
  [0x00000000]> wq
  ```

Refer to the [Radare2 documentation](https://rada.re/n/) for more advanced usage and commands.

## Contributing

Contributions are welcome! If you have ideas for new challenges or improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

Happy hacking and good luck with the challenges!
