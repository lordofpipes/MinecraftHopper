---
layout: article
title: "Getting a HijackThis Log"
name: "hjt-log"
desc: "Getting a HijackThis log for further troubleshooting"
---

# Getting a HijackThis Log for Further Troubleshooting

HijackThis is a utility that is used to collect diagnostic reports of your computer to help narrow down the cause of any issues you may be having. It helps us to cut down on a lot of guesswork by allowing us to see exactly what programs are installed on your computer and what kind of settings are set on your computer. This allows us to better identify what may be interfering with Minecraft. **No personal information is saved in these logs.**

For more information, see the [Wikipedia article](https://en.wikipedia.org/wiki/HijackThis) about this tool. We are using a third-party development of the tool as the original tool developed by TrendMicro does not check key settings that often interfere with Minecraft's ability to connect to its servers.

Follow the instructions below to generate a HijackThis log.

### Windows
<details data-platform="windows">
    <summary>Click for instructions</summary>

{{ "
#### Step 1
[Download the program](https://github.com/dragokas/hijackthis/raw/devel/binary/HiJackThis.exe).
![](/static/images/help/hjt/win-download-url.png)

#### Step 2

Navigate to your Downloads folder and open the downloaded file. Click **Yes** at the UAC prompt.
![](/static/images/help/hjt/win-open.png)

#### Step 3

Click **Do a system scan and save a logfile**. The scan will begin. It may take some time for the scan to complete.
![](/static/images/help/hjt/win-scan.png)

#### Step 4

When the scan completes, a Notepad window will open. Select all the text (**Ctrl-A**) and copy it (**Ctrl-C**).
![](/static/images/help/hjt/win-report-ctrl-a.png)

#### Step 5

Open [https://paste.gg](https://paste.gg) and paste (**Ctrl-V** or **Cmd-V**) the contents into the largest field. Put your Discord username into the **'Paste name'** field, and a description (e.g. 'HiJackThis report') in the **'Description'** field.
![](/static/images/help/hjt/win-pastegg-pasted.png)

#### Step 6

Click **Submit Anonymously**. On the next page, copy the URL from the address bar and give that URL to whoever requested it. Wait for further instructions.
![](/static/images/help/hjt/win-pastegg-url.png)
" | markdownify }}
</details>

### Mac/Linux
<details data-platform="macos linux">
	<summary>Click for instructions</summary>

{{"
#### Step 1
Open the terminal.

On a Mac, in the Finder, press **Cmd-Space** to open Spotlight, and type **'terminal'** and press **Enter**.
![](/static/images/help/hjt/mac-spotlight-terminal.png)

#### Step 2
In the terminal, type `curl -L https://is.gd/xV3Mxu | sh` and press enter.
![](/static/images/help/hjt/mac-terminal-command.png)

#### Step 3
<p>The script will run for a minute or two. If a java error pops up asking you to install JDK, click OK. When the script completes, a URL will appear in the terminal.</p>
![](/static/images/help/hjt/mac-terminal-command-java-error.png)
![](/static/images/help/hjt/mac-terminal-command-completed.png)

#### Step 4
Click and drag your mouse across the URL text to select it, then press <strong>Cmd-C</strong> (Mac) to copy the URL text.
![](/static/images/help/hjt/mac-terminal-command-select.png)

#### Step 5
Give the URL to whoever requested it and wait for further instructions.
" | markdownify}}
</details>
