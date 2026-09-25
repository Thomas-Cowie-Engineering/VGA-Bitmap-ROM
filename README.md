# VGA Bitmap ROM

<p align="center">
  <em>A custom, SHaRC-inspired sprite, made in Verilog for VGA output.</em>
</p>


---

## 📸 Screenshots


 <img src="https://github.com/user-attachments/assets/57d4b54c-7020-4a87-b52d-1d19b89dd644" width="380" alt="VGA Sprite Output 1" /> <img src="https://github.com/user-attachments/assets/25798571-a2a8-4bdf-9ef0-a5a673b864c9" width="380" alt="VGA Sprite Output 2" /> 

---

## ⚡ Quick Start

You can emulate and test this custom sprite directly in your browser without installing local EDA tools:

1. **Open the Simulator:** Launch the [VGA Playground Logo Environment](https://vga-playground.com/?preset=logo).
2. **Copy the Source Code:** Grab the Verilog source files located in the [`src/`](./src) folder of this repository.
3. **Run the Simulation:** Replace the modules in the VGA Playground editor with the contents from `src/` to instantly view the custom sprite.

---

## 🛠️ How It Works

This project intercepts standard VGA timing logic to index into a modified Read-Only Memory (ROM) module:

* **`bitmap_rom.v`**: Holds the pixel array representing the custom SHaRC sprite artwork.
* **VGA Signal Generator**: Maps current pixel $(X, Y)$ coordinates to memory addresses in real-time to drive output RGB signals.

---

## 🙏 Credits & Acknowledgments

* Built upon the open-source **Logo** preset provided by [Tiny Tapeout VGA Playground](https://tinytapeout.com/).
* **Modifications:** The default bitmap module was replaced with a custom-engineered `bitmap_rom.v` sprite map.
