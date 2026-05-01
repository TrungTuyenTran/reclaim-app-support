# Reclaim — App Support

**Developer:** Tuyen Tran  
**Contact:** reclaim.feedback@gmail.com

Welcome to the Reclaim support page. Find answers to common questions below. For anything not covered here, email us directly — we read every message.

---

## Contact Us

**Email:** reclaim.feedback@gmail.com  
We typically respond within 1–2 business days.

For bug reports, please include:
- Your iPhone model (e.g. iPhone 15 Pro)
- iOS version (Settings → General → About)
- A short description of what happened and what you expected

---

## Frequently Asked Questions

### Timer & Sessions

**Why did my timer reset after I closed the app?**  
Reclaim saves your session state automatically. If the timer resets unexpectedly, it is most likely because the device restarted or the app was force-quit during an active session. For best results, swipe away and reopen the app rather than force-quitting it.

**Can I pause during a break?**  
No — breaks run uninterrupted by design. Your only options during a break are to wait it out or tap **Skip Break** to jump straight into the next focus session.

**Can I change my Pomodoro or break duration while a task is running?**  
Not while a task is active or paused. Tap **Stop Task** on the Timer screen first, then tap the task card to edit it. Once saved, you can restart the task.

**The tick sound plays over my music — can I disable it?**  
The tick sound uses the ambient audio category so it mixes with your music rather than interrupting it. A toggle to turn off the tick sound is planned for a future update.

**Why does the timer sometimes show a slightly different time after I reopen the app?**  
When the app is in the background, Reclaim uses a timestamp-based approach to correct the remaining time when you return. In most cases this is accurate to within a second. A very long background period on a low-memory device can cause a small drift — this is a known limitation being improved.

---

### Tasks

**How do I reorder my tasks?**  
On the Task List, long-press any task card to lift it, then drag it to the position you want. Reordering is available on the **Active** tab only. Completed tasks cannot be reordered.

**How do I edit a task?**  
Tap the task card body to open it. Note: a task can only be edited when it is **Not Started**. If a task is in progress or paused, stop it from the Timer screen first.

**How do I delete a task?**  
Open the task in edit mode (tap the card), scroll to the bottom, and tap **Delete Task**. A confirmation prompt will appear before anything is deleted.

**What happens if I start a new task while one is already running?**  
Reclaim will show a warning: *"You have an active task."* If you confirm, the current task is stopped and reset, and the new task starts immediately.

---

### Notifications

**I'm not receiving my morning or end-of-day notification.**  
Check that notifications are enabled: go to **iPhone Settings → Reclaim → Notifications** and make sure they are turned on. The morning reminder fires at **8 AM** and the end-of-day summary at **7 PM** in your device's local timezone.

**Can I change the notification times?**  
Not in the current version — 8 AM and 7 PM are fixed. Configurable notification times are planned for a future release.

---

### Widgets & Live Activity

**The widget is not showing my active task.**  
Widget content is refreshed by iOS on a schedule. Try removing and re-adding the widget from your Home Screen to force a reload. If the problem persists, restart the app.

**The widget shows "No active task" even though I have one running.**  
This is a known iOS limitation — widget updates are throttled by the system and can lag behind the app by up to a minute. Open the app to see the live state.

**The Live Activity on my Dynamic Island or Lock Screen disappeared.**  
Live Activities are automatically dismissed when a task is completed or stopped. If it disappeared while a task was still running, check that Live Activities are enabled: **iPhone Settings → Reclaim → Live Activities**.

---

### Data & Privacy

**Where is my data stored?**  
All tasks and session history are stored locally on your iPhone using CoreData. Nothing is uploaded to a server or the cloud. Uninstalling the app permanently deletes all data.

**Does Reclaim sync between my devices?**  
Not yet. Optional iCloud sync is planned for a future release.

**Does Reclaim track my usage or collect analytics?**  
No. The only external service used is Firebase Remote Config, which delivers app configuration (like the minimum required version). No task data, session data, or personal information is collected. See the [Privacy Policy](privacy-policy.md) for full details.

---

## Known Limitations (v1.0)

| Issue | Status |
|-------|--------|
| Tapping a notification does not deep-link to a specific screen | Planned fix in a future update |
| Widget countdown can lag up to ~1 minute behind the in-app timer | iOS system limitation |
| Tick sound toggle not available | Planned for a future Settings update |
| Configurable notification times not available | Planned for a future Settings update |
| No iCloud sync | Planned for a future release |

---

## Feature Requests

Have an idea? Email **reclaim.feedback@gmail.com** with the subject line `Feature Request: [your idea]`. All suggestions are read and taken seriously when planning future releases.

---

## Privacy Policy

Read the full [Privacy Policy](privacy-policy.md).
