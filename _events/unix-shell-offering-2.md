---
title: "The Unix Shell"
date_label: "SEP 3"
display_dates: "September 3"
sort_order: 2
track: "foundational"
detail: "Offering 2 - repeat"
lesson_key: "unix"
registration_url: "https://forms.cloud.microsoft/Pages/ResponsePage.aspx?id=-Mr-ZsA9LE24uO_w3epG8Pd9xp4roEtFpGN_dLD6pNxURTJPWUpIQlg0SzYxWUxMQlJMSllRNkkxSy4u"
setup_ready: true
---


<div class="event-setup" markdown="1">

## Prepare for The Unix Shell

**Thursday, September 3, 2026**  
**6:00–9:00 PM Central Time**  
**Bruner Hall, Room 126**

No previous command-line experience is required. Please complete the steps below before the workshop begins.

### What to bring

- A laptop running macOS, Windows, or Linux
- Your laptop’s charging cable

### Complete these steps before the workshop

1. Follow the operating-system instructions below to confirm that you have access to Bash.
2. [Download `shell-lesson-data.zip`](https://swcarpentry.github.io/shell-novice/data/shell-lesson-data.zip).
3. Move the downloaded ZIP file to your Desktop.
4. Extract the file. You should have a folder named `shell-lesson-data` on your Desktop.
5. [Complete the pre-workshop survey](https://carpentries.typeform.com/to/wi32rS?slug=2026-08-27-tntech). If you have completed this for a previous workshop this semester, you may receive an error, in that case, this step is finished. 
6. Review [The Carpentries Code of Conduct](https://docs.carpentries.org/policies/coc/). All workshop participants are expected to follow this Code of Conduct.

### Operating-system instructions

#### Windows

For this workshop, we recommend **Git Bash**, which is installed with Git for Windows.

##### Check whether Git Bash is already installed

1. Open the Windows Start menu.
2. Search for **Git Bash**.
3. If Git Bash opens, you are ready. You do not need to reinstall it.

##### Install Git Bash

If Git Bash is not already installed:

1. Download [Git for Windows](https://gitforwindows.org/).
2. Run the installer. Keep the default selections except for the following screens:

   - On **Choosing the default editor used by Git**, select **Use the Nano editor by default**.

    <figure class="event-setup-screenshot">
        <a href="{{ '/assets/img/workshop/nano_git_bash.png' | relative_url }}" target="_blank">
            <img src="{{ '/assets/img/workshop/nano_git_bash.png' | relative_url }}"
            alt="Select Nano as the default Git editor in the Git for Windows installer.">
        </a>
    </figure>

   - On **Adjusting the name of the initial branch in new repositories**, select **Override the default branch name for new repositories** and enter `main`.

    <figure class="event-setup-screenshot">
        <a href="{{ '/assets/img/workshop/main_branch_git_bash.png' | relative_url }}" target="_blank">
            <img src="{{ '/assets/img/workshop/main_branch_git_bash.png' | relative_url }}"
            alt="Set main as the default initial branch name in the Git for Windows installer.">
        </a>
    </figure>

    - On **Configuring the terminal emulator to use with Git Bash**, select
    **Use Windows' default console window**.

    This provides better compatibility with interactive programs such as Python that may be used in later workshops.

    <figure class="event-setup-screenshot">
        <a href="{{ '/assets/img/workshop/default_console_window.png' | relative_url }}" target="_blank">
            <img src="{{ '/assets/img/workshop/default_console_window.png' | relative_url }}"
            alt="Select Use Windows' default console window in the Git for Windows installer.">
        </a>
    </figure>

3. Continue through the remaining screens using the default selections, and then select **Install**.
4. When installation finishes, open the Windows Start menu and launch **Git Bash**.

If your Tennessee Tech-managed computer prevents installation, contact the ITS Help Desk, visit our open office hours, or bring the computer to the workshop and arrive early.

> Already use WSL? You may use an existing WSL installation if you are comfortable with it, but file paths may differ from those demonstrated during the workshop. Our Windows demonstrations and support will use Git Bash.

#### macOS

macOS already includes the software needed for this workshop.

1. Open **Terminal** from Applications → Utilities, or search for it with Spotlight.
2. At the prompt, type `bash` and press Return.

#### Linux

Linux normally includes Bash or another compatible Unix shell.

1. Open your preferred terminal application.
2. Type `bash` and press Enter.

### Confirm that Bash works

Open your shell application and enter:

```bash
bash --version
```
You should see version information beginning with `GNU bash`.

Also confirm that your Desktop contains the extracted folder:
```
shell-lesson-data
```

If both checks succeed, you are ready for the workshop.

> **Need help?** Need help before the workshop? Bring your laptop to our open office hours from **11:00 AM–12:00 PM on Tuesdays and Thursdays in Clement Hall, Room 218**, or join office hours through [Microsoft Teams](https://teams.microsoft.com/l/message/19:qhYmpc6K2S_9k8aKk5M6qVWskyioXHT9PbVAdzxkCAc1@thread.tacv2/1762809784970?tenantId=66fecaf8-3dc0-4d2c-b8b8-eff0ddea46f0&groupId=11fa6b12-60b1-4d73-86c1-49fb49889045&parentMessageId=1762809784970&teamName=ITS%20Research%20Computing%20and%20Data&channelName=General&createdTime=1762809784970). If you still need assistance on the workshop date, bring your laptop and arrive a few minutes early.

</div>