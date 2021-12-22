#Sohcahtoa82's Toolbelt

---

My personal utility for functions I want but don't need separate programs for:

- Saving/restoring window positions and sizes, useful for when Windows decides to screw with your windows when it unplug and replug a monitor, or when a program changes your desktop resolution.

  NOTE: Does not behave well with windows that span multiple monitors.  You may need to hit Restore twice if a window moves between monitors with different scaling.

- Easy copy/paste function for some fun emoticons.

Make this program run on startup in Windows by opening Task Scheduler and adding a task that runs on log on that starts a program.  The Program/script path should be the location of `pythonw.exe` (Note the `w` - It makes Python run without a terminal window), with the argument being the path to `Toolbelt.py`.  If the path contains spaces, be sure to put quotes around it.  