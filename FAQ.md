# Tea Time FAQ

## Why didn't I see a call?
Snooze might be on, your Mac might have been asleep, or you are on a different Wi-Fi network from the person who called. Tea Time only reaches Macs that are awake, on the same network, running Tea Time, and have added you. A call you miss leaves an orange dot and "Chai call" in the menu bar.

## Who can see my calls?
Only people in your network who have added you back. Calls never go over the internet. The one time Tea Time contacts the internet is when you choose **Check for updates…**, which asks GitHub for the newest version number.

## What does Tea Time send over the network?
A very small message with your display name and a random ID, so people know who called. There are no accounts, no tracking and no servers.

## How do I add people?
Click **Add People…** in the Tea Time window. It lists people nearby who have Tea Time running. Click **Add** next to each person you want to call. They need to add you too: until they do, you see "Waiting for them to add you" and calls don't reach them. Once you have both added each other, you stay connected whenever you are both online.

## How do I choose who gets a call?
Everyone you're connected with gets the call. To leave someone out for now, open the menu, then **Send a call → Notify**, and untick them. To remove someone completely, hover over them in the Tea Time window and click **Remove**.

## Where does the animation appear?
Open the menu, then **On this Mac → Animation position**, and pick the center or a corner. This only changes your own screen.

## How do I change the name people see?
Open the menu and click **Display name…** under **Send a call**. Leave it empty to use your Mac's first name.

## Can someone spam everyone?
No. You can call once every 30 seconds, and anyone can snooze for an hour.

## Can I stop calls after office hours?
Yes. Turn on **Work hours** in the Tea Time window and pick a start and end time. Outside them you can't call, and calls you get only show in the menu bar.

## Does it interrupt meetings?
It never takes your keyboard focus and it goes away on its own. If you are presenting, turn on **Snooze for 1 hour** from the menu. The call still shows in the menu bar, without the animation.

## Does it work in full screen?
Yes. The animation appears over full-screen apps.

## macOS says it cannot open the app. What do I do?
See [Opening it the first time](README.md#opening-it-the-first-time). It is a one-time step.

## macOS asked about the local network. Should I allow it?
Yes. Tea Time uses the local network to find people nearby. If you chose Don't Allow by mistake, turn it back on in **System Settings → Privacy & Security → Local Network**.

## Add People says no one was found.
Check that the other person has Tea Time running (the app, not just installed) and is on the same Wi-Fi or network as you. Some office and guest networks stop devices from seeing each other. If yours does, please [open an issue](https://github.com/ntsh08/Tea-Time/issues) and say which network setup you have.

## Does it work on Windows or Linux?
Not yet. Tea Time is a Mac app for now.

## How do I turn off the sound?
Switch off **Allow sound** under **On this Mac**. Tea Time also follows the macOS **Reduce Motion** setting and plays the calm version when that is on.

## I can't see the cup in the menu bar.
Tea Time is probably running, but your menu bar is full. This is common on MacBooks with a notch, where macOS hides the icons that don't fit.
- Hold **⌘** and drag a few icons you don't need off the menu bar. The cup appears as soon as there is room.
- Or open **System Settings → Menu Bar** and switch off items you don't use.
- Click Tea Time in the Dock. It opens the window, even while the menu bar icon is hidden.

## How do I quit it?
Choose **Tea Time → Quit Tea Time** (⌘Q), or click the cup in the menu bar and choose **Quit Tea Time**.

## How do I report a bug or ask for a feature?
Choose **Send feedback…** in the menu, write what happened, and click Send. It opens a new GitHub issue with your text already filled in, so you need a GitHub account. You can also [open an issue](https://github.com/ntsh08/Tea-Time/issues) yourself. Say what you did, what you expected, and your macOS version.
