# Official Tori Client Bug Tracker
Found something that isn't supposed to happen or want to request something be done differently, or even request something completely new?! You're in the right place! Head on over to the Issues tab and let us know what's going on, and we'll get back to you as soon as we can!

**NOTE:** We will not address your issue or request if you don't give any details. See the FAQ for examples of issues we'll ignore. [Here's a good article on how to write a good report.](https://sifterapp.com/blog/2012/08/tips-for-effectively-reporting-bugs-and-issues/)

## FAQ
### I have a general question about the client. Where can I ask it?
You can head over to our [discord server](discord.gg/toriclient) and either ask in the questions channel, or open a ticket.

### What if I find a severe security vurnerability that I want to be addressed privately?
You can head over to our [discord server](discord.gg/toriclient) and open a ticket there so our staff team can review it privately, or email us at support@toriclient.com.

### What if I just want to resolve a general issue privately?
You can open a ticket in our [discord server](discord.gg/toriclient), however we highly recommend you open an issue here so that other people that might encounter the same issue can have an idea on what to do. If you think your issue is rare and can't happen to anyone else, you'd be surprised.

### Are third-party cape mods supported?
Third-party cape mods are unfortunately **not supported** at the moment. Clients with cosmetics such as Essentials should work fine however.
#### If your game keeps crashing after you added your own mods, check to make sure you don't have a custom capes mod installed!

### How SHOULDN'T I submit an issue?
There is a very nice issue template available for you to use that will give us all the information we need in an organized matter.

Things like...
* `Help, it doesn't work!`
* `Something didn't work correctly, please fix!`
* `My mods aren't working.`
* `My game keeps crashing!`

...are generally not good ways to report an issue as it provides us with no information or context to help us resolve it.

### Where can I find the Tori Launcher log file?
⚠️ You can find more up-to-date and clearer instructions [here](https://help.toriclient.com/books/launcher-guides/page/obtaining-launcher-logs)! ⚠️

If you are able to login and access the launcher, the easiest way to send us the log file is to go to the Settings tab, and click `Upload`. This will find and send us the log file automatically.

![image](https://github.com/WifiRouterYT/Tori-Client-Bug-Tracker/assets/45213292/afd02e31-008c-4ffe-b2f2-4a78bae5916e)

Clicking that button should give you a 5 character random ID in a little message box that looks something like this:

![image](https://github.com/WifiRouterYT/Tori-Client-Bug-Tracker/assets/45213292/e1b53970-6731-48e2-8c1c-14520f5b5acc)

Simply copy this ID and add it to your issue report to help us resolve any possible issues you may have with the launcher or game.
#### If you can't log in or use the launcher properly, here's how to find the log file manually.
The ToriLauncher log file shares the same file name, `launcher.log`, across every platform, but the folder it's in varies depending on your operating system.
#### Windows
Open up the Run box `Windows Key + R` and paste in `%localappdata%\torilauncher\`

![image](https://github.com/WifiRouterYT/Tori-Client-Bug-Tracker/assets/45213292/f5a995ae-101e-43fd-a619-cebba94eff18)

In there you will see a couple folders and files. Look for folders named `app-x.x.x` and click on the last one (the latest version). For example, if there's 3 folders called `app-0.0.8`, `app-0.0.9`, and `app-0.1.0`, you would chose `app-0.1.0` because it's the latest one.

![image](https://github.com/WifiRouterYT/Tori-Client-Bug-Tracker/assets/45213292/4fcfb1b9-596b-43b1-b4fa-e533853a6a48)

In there you should be able to find a file called `launcher.log`. This file is automatically created when you open the launcher.

![image](https://github.com/WifiRouterYT/Tori-Client-Bug-Tracker/assets/45213292/33b8064e-84cd-4752-8659-b8fa7ead2c4c)

There you go! Upload that either to the issue and it will greatly assist us in resolving any launcher-related issues.
