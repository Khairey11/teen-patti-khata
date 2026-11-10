# Teen Patti Khata

A points ledger for Teen Patti played with real cards. Create a room, share the link, and everyone's phone shows the same points live. No sign-in needed.

- Starting points per player, adjustable boot
- One tap collects the boot; quick bet buttons per seat
- One tap records the winner; latest winner and full winnings record
- Undo the last action

Hosted on GitHub Pages. Scores sync through Supabase (table `tp_rooms`; the publishable key in `index.html` is meant to be public, and row-level security limits it to reading, creating and updating rooms).
