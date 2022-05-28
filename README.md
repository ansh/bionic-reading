# bionic-reading
A Chrome Extension for Bionic Reading on ANY website!

This extension was made by me on May 20th in about 15 minutes of coding time. Please forgive any bugs as it hasn't been widely tested. Feel free to report them in Github Issues. Also, feel free to open a PR to fix any issues. I will review them quickly.

If there is interest, I am happy to work on this more and make it a dedicated screen reader. 

# Table of Contents
- [bionic-reading](#bionic-reading)
- [Table of Contents](#table-of-contents)
- [Installation Instructions Chrome, Edge and chromium-based browsers](#installation-instructions-chrome-edge-and-chromium-based-browsers)
  - [Chrome](#chrome)
    - [Text instructions](#text-instructions)
    - [Image instructions](#image-instructions)
  - [Firefox](#firefox)
  - [Opera](#opera)
- [What is Bionic Reading?](#what-is-bionic-reading)
- [How to build](#how-to-build)
- [Development](#development)

# Installation Instructions Chrome, Edge and chromium-based browsers

## Chrome

### Text instructions
1. Download the latest build `chrome.zip` in [releases](https://github.com/ansh/bionic-reading/releases)
2. Open the file location (e.g. Download).
3. Right click the ZIP file > Extract All > OK.
4. Open the folder in the command line (Suggesting to use bash terminal in case you are using the Windows operating system).
5. Run `yarn install; yarn build;` .
6. Open Chrome > go to this link `chrome://extensions/` .
7. Enable "Developer mode".
8. Click "Load unpacked" and then choose `extension/chrome` inside the extracted folder. 
9. To pin the extension, click the puzzle icon on the top right of Chrome, then pin the extension.

### Image instructions
1. Download code as zip.
![download](https://user-images.githubusercontent.com/15909768/169638232-7f664570-1cc8-4c9b-8954-5e4ad9d6ec72.png)

2. extract.
![extract](https://user-images.githubusercontent.com/15909768/169638240-df7e0fd8-bbc9-4f9b-9df0-bde4908540af.png)

3. Open extensions in chrome settings.
![extensions](https://user-images.githubusercontent.com/15909768/169638245-852414ad-ddb4-4308-90c9-08077b433e5b.png)

4. Enable developer mode.
![developer](https://user-images.githubusercontent.com/15909768/169638247-6d2fefee-7fe7-4bbf-aec2-0ab2a8401bdb.png)

5. "Load unpacked" select the folder you extracted to.
![load unpacked](https://user-images.githubusercontent.com/15909768/169638261-563a64cc-019d-4d1e-929d-030c2c577d8f.png)
![select folder](https://user-images.githubusercontent.com/15909768/169638257-54d9a69b-d577-4353-ac5a-6b99a910ff07.png)

6. Click on extension.  should be under "access requested".
![access](https://user-images.githubusercontent.com/15909768/169638268-47f74e01-455c-4222-8b82-4d79bb4e1ea0.png)

7. Click convert.
![convert](https://user-images.githubusercontent.com/15909768/169638273-b70c3aaf-8a52-4dd0-bf58-a4a7dffe8608.png)



## Firefox

- Download the latest build `firefox.xpi` in [releases](https://github.com/ansh/bionic-reading/releases) (Use other browsers, Firefox won't allow downloading unsigned xip files)
- open Firefox
- enter `about:debugging#/runtime/this-firefox` in the URL bar
- click "Load Temporary Add-on"
- select the `firefox.xpi`

## Opera

- Download the latest build `chrome.zip` in [releases](https://github.com/ansh/bionic-reading/releases) and unzip it
- open Opera
- Enable Developer mode in Extension page
- click "Load Unpacked"
- select the folder

# What is Bionic Reading?
Bionic Reading is a new method facilitating the reading process by guiding the eyes through text with artficial fixation points.
As a result, the reader is only focusing on the highlighted initial letters and lets the brain center complete the word.
In a digital world dominated by shallow forms of reading, Bionic Reading aims to encourage a more in-depth reading and understanding of written content.

Read more about [Bionic Reading](https://bionic-reading.com/about/).

# How to build
Need to install npm and yarn
To build run followings
1. yarn install
2. yarn build (This will create extentions for chrome, firefox and opera inside extention folder)
to debug run 

# Development
1. Run ```yarn dev:chrome``` to start dev server with hot reloading <br/>
You may enable vscode to run ```yarn dev:chrome``` by copying .vscode/tasks.json.example to .vscode/tasks.json
