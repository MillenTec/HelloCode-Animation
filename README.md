<div align="center">
<h1>Hello Code After Effects Project</h1>
<img src="img/Project Image/Project Image.png" width="100%" alt="Header Image">
<p><a href="README.zh-cn.md">简体中文</a> | English</p>
<strong><big>MG Animation for the 2025 October 24th Programmer's Day</big></strong></p>

<hr>
</div>

>First of all, my English is not very good, so I used AI to help me translate the English version of the README. Therefore, there may be some translation errors or inappropriate parts. Please forgive me.

This is an MG animation created using `After Effects`, which connects various programming languages and IDEs through the clue of **"Hello World"**. It is made to celebrate this special day for developers on October 24th, in honor of every programmer who loves coding.

## 1. Project Overview
I am a beginner with After Effects, learning AE knowledge while making open-source projects. This is my second AE work, and I would appreciate your guidance from more experienced peers.

My understanding of MG animation (and the reason for learning After Effects) was greatly influenced by Apple's famous MG animation: **"Wonderful Tools"** (you can watch it on [Bilibili](https://www.bilibili.com/video/BV1MJ411A77x)). So — perhaps you may notice some similar scenes in my animation to "Wonderful Tools."

As the 2025 October 24th Programmer's Day approaches, I wanted to make such an animation to celebrate this day, and that’s how this project came about.

In fact, the time for this animation was quite tight. My production time was roughly four full days, so there are still many details that aren't perfect. I may revise them later — you can see more in the following text; the rendering of this animation took over three hours...

## 2. Open Source Information
This work will be open-sourced under the **[CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/legalcode.txt)** license, which means you can:
- **Share** — Replicate and distribute this work.
- **Adapt** — Modify, convert, or create new works based on this.

However, you must also comply with the following conditions:
- **Attribution** — You must credit the original author (**MillenTec**) and source (Bilibili video), and provide a link to the original license.
- **Non-commercial Use** — **You may not use this work for commercial purposes.**

> In short, as long as you do not use it for commercial purposes and attribute the original author, you can use it for any purpose (please see [CC BY-NC 4.0 License](https://creativecommons.org/licenses/by-nc/4.0/legalcode.txt) for details).

## 3. Guidelines for Reposting/Adaptation  
This is a detailed reposting/adaptation guide, which serves as a supplement and explanation to the license above. If you follow these guidelines, you will generally not violate our licensing terms. If you wish to understand more details, please continue reading.

### 3.1. Reposting (Without Content Changes)  
#### 3.1.1. Reposting Within Bilibili  
**What You Need:**  
- **Attribution:** You must include the following or equivalent text in the video description:  
  ```text
  Reposted from @MillenTec  
  Original Video: BV1v8sbzQEiU  
  Original Video License: CC BY-NC 4.0
  ```
- **Repost Declaration:** You must declare it as a "repost" and set the upload type to "repost."

**What You Can Do:**  
- **No Application Required:** As long as you comply with the [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/legalcode.txt) license terms, you do not need to apply for reposting. You can directly repost the video. You can download the rendered, watermark-free 4K 120fps original video (H.265) from [GitHub Releases](https://github.com/MillenTec/HelloCode-Animation/releases).

#### 3.2. Reposting on Other Platforms  
**What You Need:**  
- **Attribution:** You must include the following or equivalent text in the video description:  
  ```text
  Reposted from [bilibili@MillenTec](https://space.bilibili.com/3546591566760474)  
  Original Video: [Hello Code](https://www.bilibili.com/video/BV1v8sbzQEiU)  
  Original Video License: CC BY-NC 4.0
  ```
- **Repost Declaration:** You must declare it as a "repost" and set the upload type to "repost" (if supported by the platform).

**What You Can Do:**  
- **No Application Required:** As long as you comply with the [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/legalcode.txt) license terms, you do not need to apply for reposting. You can directly repost the video. You can download the rendered, watermark-free 4K 120fps original video (H.265) from [GitHub Releases](https://github.com/MillenTec/HelloCode-Animation/releases).

### 3.2. Adaptation  
**What You Need:**  
- **Attribution and Declaration of Adaptation:** You must include the following text in the description or README file of your video/project:  
  ```markdown
  ## This Project is Based on the Open-Source Project `Hello Code`
  **Adapted from MillenTec:**
  - [bilibili](https://space.bilibili.com/3546591566760474)
  - [GitHub](https://github.com/MillenTec)
  - [Gitee](https://gitee.com/MillenTec/HelloCode-Animation)

  **Source Project:**
  - [bilibili](https://www.bilibili.com/video/BV1v8sbzQEiU)
  - [GitHub](https://github.com/MillenTec/HelloCode-Animation)
  - [Gitee](https://gitee.com/MillenTec/HelloCode-Animation)

  **Source Project License:** [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/legalcode.txt)  
  **Open-Source Scope:** Illustrator project files, Premiere Pro project files

  This project complies with the open-source license requirements of the source project, and it attributes to the original author for non-commercial use only.
  ```
- **Non-Commercial Use Only:** Regardless of the form of adaptation, you must **not use it for commercial purposes**.
- **If Your Adapted Project is Open Source**, You Need:  
  - **Include a Copy of the Original License (if open-source):** If your adapted project will be open-sourced, you must include a file named `LICENSE.original` in the root directory of your open-source project. The content should match that of [LICENSE.txt](LICENSE.txt).
  - **Use a Non-Commercial Open Source License:** You can choose any open-source license you prefer for your project, but it must be a **non-commercial** license (i.e., the license must not allow commercial use).
  - **Traceability:** I hope that projects derived from your work will also include links to this project and the Bilibili video. This helps with traceability, although this is **not a strict requirement**.

**What You Can Do:**  
- **No Application Required:** You can adapt and re-release the project without any prior application.
- **Optional Open Source:** Your adapted project may choose to remain closed-source, but I sincerely hope you contribute to the open-source community.

## 4. Directory Structure
```powershell
.
├── Ai/ # All original vector illustrations (Adobe Illustrator source files)
├── img/ # All non-vector image resources used in the project
├── Sounds/ # Sound effects and background music
├── Hello Code.aep # Main AE project file (does not include audio)
├── Hello Code.prproj # PR project file (includes audio)
├── LICENSE.txt # License text (legal document)
├── README.md # Description file (en-US)
└── README.zh-cn.md # Description file (zh-CN)
```

## 5. Environment and Platform
### 5.1 Software Environment
- **Windows 11 25H2**
- **Adobe Illustrator 2024**
- **Adobe After Effects 2024**
- **Adobe Premiere Pro 2024**
> Please use the corresponding (or higher) Adobe version to open the project files.

### 5.2 Hardware Platform
- **Intel Core i7-12700H**
- **NVIDIA GeForce RTX 3060 Laptop GPU**
- **6GB GDDR6 VRAM**
- **8GB*2 DDR5 4800MT/s RAM**
> Your device may need to meet or exceed these specifications for smooth playback in After Effects.

## 6. Release Platforms
### 6.1 Open Source Projects
- **GitHub**  
  - https://github.com/MillenTec/HelloCode-Animation  
  - All modifications will be pushed to the GitHub repository first, and you can get the latest source files here.
- **Gitee**
  - https://gitee.com/MillenTec/HelloCode-Animation  
  - A mirror site for users in mainland China; it is expected to sync with GitHub once a week.
>Note: The main track video file in the `.prproj` file of an open source project is not included in the project (offline). It is a video file rendered by Ae. After you have completed rendering the main composition in Ae, you can replace the main track's material with the video file you have rendered.

### 6.2 Animation Release
- **Only on [Bilibili](https://space.bilibili.com/3546591566760474)**

## 7. Third Party
### 7.1 Background Music
- **Flirting With June** - Les Gordon

### 7.2 Main Fonts
- **HarmonyOS Sans**
  - Chinese characters and Western text
  - Arabic script and its variants
- **JetBrains Mono**
  - Western text requiring monospacing
- **Some Windows System UI fonts**
  - Minority languages (including but not limited to: Thai, Inuktitut, Persian, Hindi, etc.)

### 7.3 Plugins
- **Saber**
  - Used for lighting effects
  - Located in [the-third-party](the-third-party/Saber.zip); installation instructions are provided in the `Installation.txt` file within the compressed package.

## 8.Contact Me
- **[Bilibili](https://space.bilibili.com/3546591566760474)**
- **[GitHub](https://github.com/MillenTec)**
- **[Gitee](https://gitee.com/MillenTec)**
- **Email**: MillenTec@outlook.com
