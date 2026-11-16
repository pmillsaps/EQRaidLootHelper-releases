# EQ Raid Loot Helper: releases

Download the latest **EQRaidLootHelper.exe** from [Releases](https://github.com/pmillsaps/EQRaidLootHelper-releases/releases/latest).

A Windows helper for an EverQuest raid **loot holder**:
- reads your character's log and collects the DKP bid tells for the items you put up (`pst for <item> 1st call`),
- shows each bidder's DKP and 30-day attendance from OpenDKP, and flags overbids, phase eligibility and bot/alt bids,
- works out the winner and price and builds the `Item ; price ; Name gratss` line for you to paste.

It only **reads** the log. It never sends keystrokes or anything else to EverQuest.

## Install
1. Download `EQRaidLootHelper.exe` and put it in a folder you own (e.g. next to EverQuest or in Documents).
2. Run it. Windows SmartScreen may warn because the exe isn't code-signed: **More info → Run anyway**.
3. Point it at your EverQuest folder and pick the loot holder's log.

## Updates
The app checks this page when it starts (and from **Help ▸ Check for updates…**), and updates itself in place.
Each release includes `EQRaidLootHelper.exe.sha256`; the app verifies the download against it.

This repository only holds published builds; the source is kept separately.
