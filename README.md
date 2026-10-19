# Tea Time

A small Mac menu bar app for office teams. Click once, and a ninja walks onto everyone's screen with a cup of chai.

![Tea Time animation](assets/chai.gif)

When someone calls Tea Time, every teammate running the app on the same network sees the animation at the same moment and hears a soft sound. It never takes over the keyboard, it appears over full-screen apps, and it goes away on its own. If you miss it, the menu bar icon keeps a small orange dot and "Chai call" for a while.

There is no account and no server. Tea Time finds teammates on the local network by itself.

## Download

| Release date | Download |
| --- | --- |
| 19 Oct 2026 | [TeaTime-1.0.0.dmg](https://github.com/ntsh08/Tea-Time/releases/download/v1.0.0/TeaTime-1.0.0.dmg) |

Open the DMG and drag Tea Time into Applications. If you already have Tea Time, quit it first and choose Replace.

Needs macOS 13 or later. Works on Apple Silicon and Intel Macs.

### Opening it the first time

Tea Time is not yet signed with an Apple developer certificate, so macOS will say it cannot check the app for malicious software the first time you open it. You only do this once.

**macOS 15 (Sequoia) or later**
1. Open TeaTime from Applications. macOS says "TeaTime" Not Opened. Click **Done** (not Move to Bin).
2. Open **System Settings → Privacy & Security** and scroll down.
3. Next to "TeaTime was blocked to protect your Mac", click **Open Anyway** and confirm.

**macOS 13 or 14**
1. In Applications, right-click TeaTime and choose **Open**.
2. Click **Open** in the dialog.

If macOS asks to find devices on your local network, choose **Allow**. Tea Time needs it to reach your teammates.

## Using it

Click the cup in the menu bar.

- **Recent** lists calls from the last half hour. An orange dot means you haven't looked at one yet.
- **Send a call**
  - **Animation** picks which one to send (Chai or Sutta).
  - **Notify** sends to everyone nearby, or only the people you tick.
  - **Display name** is the name teammates see when you call. Click it to change it.
  - **Preview** plays it on your screen only. **Call** sends it. There is a 30 second wait before you can call again, and you see a small "call sent" card instead of the animation.
- **On this Mac**
  - **Animation style** switches between Plain (calm) and Dramatic.
  - **Animation position** puts the animation in the center or a corner of your screen.
  - **Allow sound**, **Snooze for 1 hour** (calls only show in the menu bar) and **Open at login**.
- **Read FAQs**, **Send feedback…**, **Check for updates…** and **Quit Tea Time**.

If you miss a call, the cup keeps an orange dot and "Chai call" for a while.

Ask your teammates to install it too. Everyone has to be on the same network.

## More

- [FAQ](FAQ.md)
- Found a bug or have an idea? [Open an issue](https://github.com/ntsh08/Tea-Time/issues).

## Terms

Free to use at home or at work. See [LICENSE](LICENSE). The source code is not published.

Made by [Nitish Bhardwaj](https://nitishux.com). The ninja artwork was generated with AI image tools.
