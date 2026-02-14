# Known Issues

Last updated: February 13, 2026

---

### Desktop Client
- Screenshare displays a little floating control box with tauri.localhost. This is the way the native OS webview2 screenshare works, looking at a way to bypass without overprocessing frames
- Settings menu half of the items don't work LOL
- Reordering communities and channels doesn't work unless you very carefully do it

### Web Client
- Settings menu half of the items don't work LOL


### Voice & Video
- Delay inbetween channel join and voice connection - likely CF Proxying the Livekit handshake chain, will look at undoing that.

### Messaging
- No E2EE on messages (DMs, Group Chats, etc)
- GIF limitations (i'm using a dev API key for Giphy, limited to 100 overall per hour so goodluck atm. I'll request a prod one in time)

---

Found something not listed here? [Submit feedback](https://github.com/kc-nz/silencedapp-feedback/issues).
