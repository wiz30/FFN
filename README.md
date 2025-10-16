
<img width="1500" height="532" alt="logo" src="https://github.com/user-attachments/assets/52cff958-708d-441e-8a0b-96b38a8b7ac1" />


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

![auto response](https://github.com/user-attachments/assets/a87590dd-b343-40fd-9cb0-7c844ac85589)


<h3>Reply with custom message while you're alt tabbed</h3>

Includes:

* Adjustable message field

<ins>How it works:</ins>

Reply with custom message while you're alt tabbed

1. Set the needed text for reply
2. Hit the checkbox

---

<h3>Planned features for THIS version of FFN</h3>

1. Moonwalk
2. One-frame walk
3. Discord integration
4. Lua scripts reader (perhaps, I'm not sure)
5. Detect if another player uses FFN, if does - render his name purple (will send your username to a database server) (I'll think about this feature, perhaps useless but cool to see if someone is also in the same boat. This will not be included in the next client to avoid unnecessary detection)

...

You can submit your ideas in this repo by creating an issue with label "suggestion"

---

<h1>Installation</h1>

As soon as I will upload the source code

<h1>Build</h1>

As a regular DDNet build, do your steps

---

<h1>Pre-release changelog</h1>

<h3>1.1.0:</h3>

[+] Added text mimicking (type username to mimick from)

[^] Tricky words such as "i am a loser" will not be copied to not 'overplay' you
  
[^] You can't copy your dummy
  
[+] Added tabs in FFN window - Main, Fun

<h3>1.2.0</h3>

[+] Added ability to see who is using FFN client (scoreboard only)

[^] Requires a special trigger-text in chat that saves into a local file with usernames

<h3>1.3.0</h3>

[+] Added reply message when you're alt tabbed
