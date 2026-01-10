
<img width="1500" height="532" alt="logo" src="https://github.com/user-attachments/assets/52cff958-708d-441e-8a0b-96b38a8b7ac1" />


<div align="center">
  <h1 color=red>FFN</h1>
</div>

Brief description:

An open-source (?) <a href='https://ddnet.org/'>DDNet</a>-based (TeeWorlds) custom client made by **oka**.

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

![auto response (2)](https://github.com/user-attachments/assets/c5e4f6d9-ff1c-4bfc-b0da-2a4fea0628a8)

<h3>Reply with custom message while you're alt tabbed</h3>

Includes:

* Adjustable message field

<ins>How it works:</ins>

Reply with custom message while you're alt tabbed

1. Set the needed text for reply
2. Hit the checkbox

Example:

![alt tab](https://github.com/user-attachments/assets/63c72ebf-1a31-4fcc-8051-e09c1474e9dc)

<h3>Text mimicking</h3>

Includes:

* Username field

<ins>How it works:</ins>

Mimic someone's text right after

1. Input someone's username in the field

Example:

![mimic](https://github.com/user-attachments/assets/68320c4a-64e5-4e35-99d0-6a2da33f67e4)

(to disable, leave the username field empty)

<h3>Custom version</h3>

Includes:

* Adjustable field from 0 to about 99999. Can write numbers manually by double clicking the field

1. Set wanted version, join the server

Example:

![version](https://github.com/user-attachments/assets/69ad9820-04aa-4cd6-8af5-b523b98b9cf1)

<h3>FFN Network</h3>

You will be able to see who is using FFN, players who use FFN will also see that you are using the same client.

If you're a newcomer, the system will register your username upon joining a server. After you re-join it, your username will have specific logo in scoreboard and spectators list. Entering a server with FFN users does not require re-join, you will be able to see them immediately.

Keep in mind. Your dummy will not be registered in FFN list.

Example:

<img width="704" height="161" alt="image" src="https://github.com/user-attachments/assets/4539ab9a-7cea-413c-8c59-09903105f415" />

---

<h3>Planned features for THIS version of FFN</h3>

1. Moonwalk
2. One-frame walk
3. Lua scripts reader (perhaps, I'm not sure)
4. Nearby players detection (fyi it's legal)
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

[+] Version spoofing

<h3>1.2.0</h3>

[+] Added ability to see who is using FFN client (scoreboard only)

[^] Requires a special trigger-text in chat that saves into a local file with usernames

<h3>1.3.0</h3>

[+] Added reply message when you're alt tabbed

<h3>1.3.1</h3>

[*] Upscaled wallpaper

[-] Removed junk from code and UI

<h3>1.3.2</h3>

[+] Discord RPC

<h3>2.3.1</h3>

[*] Updated to 19070

[+][*] Removed red color from FFN recognition, instead added a red logo beside player's username

I'm starting to think this project will not be open sourced due to sensitive fields...

<h3>2.4.1</h3>

[+] FFNNetwork. You can see whoever is using FFN. Check scoreboard and see logo beside usernames

[*] Fixed alt-tab message being triggered if sender's message contains your name (ex. "okay" would trigger alt-tab message).

<h3>2.4.2</h3>

[*] UI changes
