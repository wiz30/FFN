
<img width="1500" height="532" alt="Untitled-1" src="https://github.com/user-attachments/assets/c22069fc-7ae5-40f6-93e5-fc6c35ede26e" />

<div align="center">
  <h1 color=red>FFN</h1>
</div>

Brief description:

An open-source <a href='https://ddnet.org/'>DDNet</a>-based (TeeWorlds) custom client made by **oka**.

<div align="left">
  <h2>Features</h2>
</div>

<h3>Auto-response configurable text via FFN tab in settings</h3>

Includes:

* Trigger text
* Response to the triggered text

<ins>How it works:</ins>

Someone sends a message, for example: "oka: hi". And your client responds with "<sender's name>: hi" (<sender's name> can be disabled).

1. Enter text you want your client to respond to in global chat
2. Enter response text that your client will respond with

Example:

![2025-07-28 01-00-14 (1)](https://github.com/user-attachments/assets/804efaf4-053e-4095-ad25-d13ae150be93)


<h3>Avoid freezes (may be buggy at specific circumstances)</h3>

> ! Might get removed and moved into another project, since It's considered as 'cheating' many where

Includes:

* Adjustable slider from 0.0 to 5.0 tiles
  
<ins>How it works:</ins>

You get pushed away from a freezing tile, the distance to get pushed from can be set via slider in settings.

1. Check the box saying "Enabled" under "Auto-Move Away from Freeze Tiles:"

Example:

![2025-07-28 01-08-25](https://github.com/user-attachments/assets/05c03545-0c9b-426a-bc92-10c1021aecfa)


<h3>Auto-shoot laser before entering freezing tile</h3>

Includes:

* Adjustable slider from 0.0 to 5.0 tiles

<ins>How it works:</ins>

You grab laser gun, you ram into the freezing tile, before entering the freezing tile you automatically shoot laser

1. Enable this feature via FFN tab in settings
2. Adjust distance in tiles you want to trigger laser by moving slider (0.0 tiles is totally fine, tested)

> Disable freeze-tiles avoidance, otherwise it will not work

Example:

![2025-07-28 01-14-42](https://github.com/user-attachments/assets/63467c2b-9c16-45c1-b98e-6d013add7e7a)

---

<h3>Planned features for THIS version of FFN</h3>

1. Auto-unfreeze yourself with laser by pointing at pre-calculated direction before entering the freeze tile (I tried to implement this but I LACK knowledge, pls help)
^ This is a legendary function came from a self-named client "Baumalein" which is almost lost and isn't supported ATM

2. Moonwalk
3. One-frame walk
4. Discord integration
5. Lua scripts reader (perhaps, I'm not sure)
6. Detect if another player uses FFN, if does - render his name purple (will send your username to a database server) (I'll think about this feature, perhaps useless but cool to see if someone is also in the same boat. This will not be included in the next client to avoid unnecessary detection)

...

You can submit your ideas in this repo by creating an issue with label "suggestion"

---

<h3>Planned features for the forbidden version</h3>

1. A[][][][][]
2. Proxy toggle (will require your own proxy server, will think about it)
3. Name stealer
4. Raid

...

<h1>Installation</h1>

As soon as I will upload the source code

<h1>Build</h1>

As a regular DDNet build, do your steps

---

<h1>Pre-release changelog</h1>

<h3>1.1.0:</h3>

[+] Added text mimicking (type username to mimick from)

 [*] Tricky words such as "i am a loser" will not be copied to not 'overplay' you
  
 [*] You can't copy your dummy
  
[+] Added tabs in FFN window - Main, Fun, XPloit (temporary, will be included in the next client)
