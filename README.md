# Tea Time

A small Mac app for office teams, in your menu bar and Dock. Click once, and a ninja walks onto everyone's screen with a cup of chai.

![Tea Time animation](assets/chai.gif)

When someone calls Tea Time, everyone in your network sees the animation at the same moment and hears a soft sound. It never takes over the keyboard, it appears over full-screen apps, and it goes away on its own. If you miss it, the menu bar icon keeps a small orange dot and "Chai call" for a while.

There is no account and no server. Tea Time finds people on the same Wi-Fi or office network by itself, and you add the ones you want to call.

## Download

| Release date | Download |
| --- | --- |
| 21 Oct 2026 | [TeaTime-1.1.6.dmg](https://github.com/ntsh08/Tea-Time/releases/download/v1.1.6/TeaTime-1.1.6.dmg) |

Open the DMG and drag Tea Time into Applications. If you have an older Tea Time (named TeaTime), quit it and delete it from Applications first. Everyone should be on 1.1 or later: it doesn't work with 1.0.0.

Needs macOS 13 or later. Works on Apple Silicon and Intel Macs.

### Opening it the first time

Tea Time is not yet signed with an Apple developer certificate, so macOS will say it cannot check the app for malicious software the first time you open it. You only do this once.

**macOS 15 (Sequoia) or later**
1. Open Tea Time from Applications. macOS says "Tea Time" Not Opened. Click **Done** (not Move to Bin).
2. Open **System Settings → Privacy & Security** and scroll down.
3. Next to "Tea Time was blocked to protect your Mac", click **Open Anyway** and confirm.

**macOS 13 or 14**
1. In Applications, right-click Tea Time and choose **Open**.
2. Click **Open** in the dialog.

If macOS asks to find devices on your local network, choose **Allow**. Tea Time needs it to find people nearby.

## Using it

Open Tea Time from the Dock, or click the cup in the menu bar. On first launch it walks you through your display name and finding people nearby.

**Your network**

- **Add People…** opens a list of people nearby who have Tea Time running. Click **Add** next to the ones you want. **Invite People…** shares the download link.
- Each person shows **Connected** (you have both added each other), **Waiting for them to add you**, or **Not nearby**.
- A call only reaches people who have added you back, so everyone adds each other once.
- Hover over a person to **Remove** them.
- **Invite People…** shares the download link from the main window too.

**Call animation** is a list: click Chai or Sutta to pick one, and hover over it to **Preview** it on your screen only. **Call Chai** sends it; there is a 30 second wait before you can call again, and you see a small "call sent" card instead of the animation.

The menu bar menu has the same options, plus **Recent** (calls from the last half hour), **Notify** (leave people out of a call), **Display name…**, **Animation style** (Plain or Dramatic), **Animation position**, **Allow sound**, **Snooze for 1 hour** and **Open at login**.

If you miss a call, the cup keeps an orange dot and "Chai call" for a while.

Everyone needs Tea Time running and has to be on the same network.

## More

- [FAQ](FAQ.md)
- Found a bug or have an idea? [Open an issue](https://github.com/ntsh08/Tea-Time/issues).

## Terms

Free to use at home or at work. See [LICENSE](LICENSE). The source code is not published.

Made by [Nitish Bhardwaj](https://nitishux.com). The ninja artwork was generated with AI image tools.
