# sabi-games
SABI Brain Games


#Music Player Notes
Browser A (PC, not logged in)

Track ends naturally → auto-advances and plays the next track. (unchanged, still perfect)
Next/Prev while playing → switches track, loads it, now waits for a manual play press (changed — previously autoplayed)
Click another track while playing → switches track, loads it, now waits for a manual play press (changed — previously autoplayed)
Currently-playing track unclickable in the list → unchanged, perfect

Browser B (iPhone, not logged in)

Track ends naturally → advances, loaded and ready, waits for a manual play press (unchanged — this was already the case)
Next/Prev while playing → switches track, waits for a manual play press (unchanged — same as before)
Click another track while playing → switches track, waits for a manual play press (unchanged — same as before)
Currently-playing track unclickable → unchanged, perfect

Browser C (laptop, logged in)

Track ends naturally → auto-advances and plays the next track. (unchanged, still perfect)
Next/Prev while playing → switches track, now waits for a manual play press instead of the fake "playing" state (changed and fixed — no more silent/confusing autoplay)
Click another track while playing → switches track, now waits for a manual play press instead of the fake "playing" state (changed and fixed)
Currently-playing track unclickable → unchanged, perfect
