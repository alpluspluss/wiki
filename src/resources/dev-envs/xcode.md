# Setting Up Xcode

Xcode is Apple's official IDE for macOS. It provides toolchains for C & C++ development on macOS. Xcode can be 
downloaded for free from the Mac App Store by simply clicking the "Get" or "Download" button to begin installation.

::: info
Beta and older releases can be found [here](https://xcodereleases.com/).
:::

After installation is done, launch Xcode. When opening Xcode for the first time, you may be prompted to 
install additional components or agree to license terms. Follow the on-screen instructions to complete this process.

When Xcode opens, you'll see the Xcode menu. Click on "Create New Project...".

![Xcode - Home](/assets/xcode-home.png)

In the project template selection window, choose "Command Line Tool" under the "macOS" tab and click "Next".

![Xcode - Create Project](/assets/xcode-create-project.png)

The IDE will now be asking you to configure your project. First of all, enter a name for your project then enter 
a reverse domain name format (e.g. com.tccpp), and then choose a location to save your project to and click "Create". 
You should see the Xcode development interface once the project is successfully created.

![Xcode - Setting up](/assets/xcode-setting-up.png)

::: info
Xcode keeps your code organized through projects and workspaces. Each project contains everything needed to build 
software i.e. source code, images, binaries, config files like `info.plist` and other assets, whereas a workspace 
is a container that can hold multiple projects. Workspaces come in quite handy as they let you manage multiple 
related projects in one place for a large codebase.
:::

## Writing Your First Program

![Xcode - Project Directory](/assets/xcode-project-dir.png)

Xcode has already created a `main.c` or `main.cpp` file for you depending on your language selection with a 
basic "Hello, World!" program which can be found on the leftside bar.

Click on the main file to open it in the Editor Area where to modify 
[your first program](/resources/getting-started#your-first-program).

## Running Your Program

To run your program, click the "Play" button (green triangle) in the top-left corner of the Xcode window, 
or press `⌘ + R` which will then build and run your code.
