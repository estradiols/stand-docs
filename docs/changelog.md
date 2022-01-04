---
hide:
  - navigation
---

## Stand Changelog

### **0.71.4** - 2022/01/04 (Latest)
- Added a new root name (version only)
- Patched a new kick method
- Fixed save outfit not saving hair colour
- Fixed some slider commands opening command box despite valid syntax
- Some other improvements and bugfixes

---

### **0.71.3** - 2021/12/31
- Improved Game > YEET
- Fixed player tags not visually updating
- Fixed bst toggle not properly working via command box
- Fixed shader override not turning off
- Fixed blackout not disabling by loading state
- Fixed an issue where Stand is invisible but making sounds
- Some other improvements and bugfixes

---

### **0.71.2** - 2021/12/29
- Some improvements and bugfixes

---

### **0.71.1** - 2021/12/28 
- Added Players > Settings > Tags > "Next Host" & "Likely Modder"
- Improved {Online > Restrictions > Bypass Time Trial Vehicle Suitability} so you can also use planes
- Improved GeoGuessr's synergy with freecam
- Fixed disable dripfeeding not making vehicles purchasable
- Fixed session script start reactions not working
- Fixed being unable to block own session script starts
- Fixed noticable freeze when injecting with big player history
- Profanity filter bypass detection is now disabled when local profanity filter is being disabled by another menu
- Some other improvements and bugfixes

---

### **0.71.0** - 2021/12/25
- Web Interface is now functional again
- Added Vehicle > Current Personal Vehicle > Imani Tech Remote Control
- Added Vehicle > Movement > Custom Wings Behaviour
- Added Online > Restrictions > "Remote Control Any Vehicle" & "Disable Forced RC Perspective"
- Added Online > CEO/MC > Remove CEO/MC Ban
- Added Online > Get BST
- Added Players > Settings > When Leaving Player's List... > Stop Spectating Them
- Added World > GeoGuessr
- Added World > Clock > Smooth Transition
- Added Game > Info Overlay > "Rotation (Entity)" & "Rotation (Camera)"
- Added Stand > Settings > Hide Information > Hide GeoIP
- Added Stand > Settings > Language > "Engwish" & "Howny Engwish"
- Improved Game > Rewind Position
- Lua API
    - Added entities.delete_by_pointer
    - Renamed entities.delete to entities.delete_by_handle
    - Renamed entities.get_boost_charge_from_pointer to entities.get_boost_charge
    - Removed previously-deprecated util.async_http_get
- Other improvements and bugfixes

---

### **0.70.10** - 2021/12/23
- Stand User Identification, Session Invite Links, and Update Notifications are now functional again
- Some other improvements and bugfixes

---

### **0.70.9** - 2021/12/21
- Changed authentication system
- Some improvements and bugfixes

---

### **0.70.8** - 2021/12/20
- Re-added Online > Disable Daily Expenses
- Patched the first person fists to sniper crash that tryhards are crying at R* for
- Removed "Remove Attachments" because R* patched remote player attachments
- Fixed a crash when attempting to use "Remove Turret" in a hunter
- Fixed camera going rogue after rewinding position
- Some other improvements and bugfixes

---

### **0.70.7** - 2021/12/18
- Fixed random exceptions
- Fixed spoofed host token default state discrepancies

---

### **0.70.6** - 2021/12/18
- Fixed some issues when in a session with other people

---

### **0.70.5** - 2021/12/18
- Fixed issues with session scripts management
- Fixed "on foot" correlation producing wrong value when aiming in a vehicle
- Fixed modded character model false-positives with new missions
- Fixed attacking while invulnerable false-positives with new Imani Tech Remote Control
- Some other improvements and bugfixes

---

### **0.70.4** - 2021/12/16
- Some improvements and bugfixes

---

### **0.70.3** - 2021/12/15
- Addressed a few oversights

---

### **0.70.2** - 2021/12/15
- Updated for 1.58-2545 The Contract
- Lua: Added util.try_run & util.copy_to_clipboard
- Some improvements and bugfixes

---

### **0.70.1** - 2021/12/13
- You can now spoof your host token at any time
- Lua: Fixed players.get_host_token
- Some other improvements and bugfixes

---

### **0.70.0** - 2021/12/11
- Stand now allows you to have multiple profiles at {Stand > Profiles}. Note that "Automatically Saved State" is not migrated, so you have to manually enable it for your profile, if you so wish.
- Added Vehicle > Los Santos Customs > Appearance > Remove Turret
- [Regular] Added Online > Transitions > Matchmaking Region
- Added Online > Protections > Session Script Start > Disable Passive Mode
- Added Online > Player History > Settings > Write Tracking Updates To Log
- [Ultimate] Added Online > Session > Session Scripts > Run Script > Disable Passive Mode
- Added World > AR GPS
- Added Stand > Lua Scripts > Settings > Developer Mode
- Added Stand > Settings > In-Game UI > Tabs > "Show Left Icon", "Show Name" & "Show Right Icon"
- Lua API: Added menu.ref_by_path, menu.ref_by_rel_path, menu.ref_by_command_name, menu.trigger_command, menu.show_warning, menu.get_value, players.is_godmode, players.is_marked_as_attacker, util.rot_to_dir, util.v3_look_at, util.arspinner_enable, util.arspinner_disable & util.is_bigmap_active
- Some improvements and bugfixes

## Stand Launchpad Changelog

### **1.7.1** - 2021/12/23 (Latest)
- You can now say "No" to downloading Launchpad updates
- A run as administrator hint will now show if 0 DLLs were injected

---

### **1.7.0** - 2021/12/11
- Now in dark mode
- Some improvements and bugfixes