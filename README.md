# Tea Time

A small Mac menu bar app for office teams. Click once, and a ninja walks onto everyone's screen with a cup of chai.

![Tea Time animation](assets/chai.gif)

When someone calls Tea Time, every teammate running the app on the same network sees the animation at the same moment and hears a soft sound. It never takes over the keyboard, it appears over full-screen apps, and it goes away on its own. If you miss it, the menu bar icon keeps a small orange dot and "Chai call" for a while.

There is no account and no server. Tea Time finds teammates on the local network by itself.

## Download

| Release date | Download |
| --- | --- |
| 19 Oct 2026 | [TeaTime-0.1.0.dmg](https://github.com/ntsh08/Tea-Time/releases/download/v0.1.0/TeaTime-0.1.0.dmg) |

Open the DMG and drag Tea Time into Applications.

Needs macOS 13 or later. Works on Apple Silicon and Intel Macs.

### Opening it the first time

Tea Time is not yet signed with an Apple developer certificate, so macOS will say it cannot check the app for malicious software the first time you open it. You only do this once.

**macOS 15 (Sequoia) or later**
1. Open Tea Time from Applications. macOS shows the warning. Click **Done**.
2. Open **System Settings → Privacy & Security** and scroll down.
3. Next to "Tea Time was blocked", click **Open Anyway** and confirm.

**macOS 13 or 14**
1. In Applications, right-click Tea Time and choose **Open**.
2. Click **Open** in the dialog.

If macOS asks to find devices on your local network, choose **Allow**. Tea Time needs it to reach your teammates.

## Using it

Click the cup in the menu bar.

- **Call Tea Time** sends it to everyone nearby. There is a 30 second wait before you can call again.
- **Preview on this Mac** plays an animation only on your screen.
- **Animation style** switches between Plain (calm) and Dramatic.
- **Snooze for 1 hour** skips the animation. The call still shows in the menu bar.
- **Open at login** keeps Tea Time running.

Ask your teammates to install it too. Everyone has to be on the same network.

## More

- [FAQ](FAQ.md)
- Found a bug or have an idea? [Open an issue](https://github.com/ntsh08/Tea-Time/issues).

## Terms

Free to use at home or at work. See [LICENSE](LICENSE). The source code is not published.

Made by [Nitish Bhardwaj](https://nitishux.com). The ninja artwork was generated with AI image tools.
