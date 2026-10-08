# Agent Energy

A small macOS menu-bar utility that keeps your Mac awake. Click the can to start a session; click again to return to Standby.

[Closed-lid setup and companion download](https://nickrinke.github.io/agent-energy/)

## Agent Energy Companion

Closed-lid sessions require the separately installed companion. The companion installs an administrator-approved background power helper. The main Agent Energy app remains sandboxed and does not download or install the companion itself.

The companion is not an Apple product and does not imply App Store approval of Agent Energy. The main app's App Store submission is separate.

### Install

1. Download the companion disk image from the setup page or this repository's Releases.
2. Drag **Agent Energy Companion** into **Applications** and open it there.
3. Click **Install Companion** and approve it in **System Settings → General → Login Items & Extensions**.
4. Reopen Agent Energy's menu. If a lid-open session is active, switch to Standby first, then click the can to start a new session.

### Sleep behavior

Without the companion, Agent Energy prevents idle system sleep while the lid remains open. The display can sleep normally.

With the companion, an active session blocks system sleep, including manual Sleep. Turning the session off or quitting Agent Energy restores the previous system sleep setting. The helper also attempts restoration after a lost connection, expired session, or restart. Screen-lock settings are not changed.

Keep an active Mac on a ventilated surface. Switch to Standby before putting it in a bag.

### Remove

Switch Agent Energy to Standby. Open Agent Energy Companion and choose **Remove Companion**. Once removal succeeds, move the companion app to the Trash.

## Privacy

Agent Energy and its companion do not collect analytics, create accounts, or transmit your activity. The companion stores a local recovery record of the previous sleep setting so it can restore it after an interruption. Visiting the setup page or downloading a release connects to GitHub under GitHub's privacy policy.

## Support

[Report a problem](https://github.com/nickrinke/agent-energy/issues). Include your macOS version, Mac model, whether the companion is installed, and the error message. Never post passwords or private files.
