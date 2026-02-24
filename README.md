# Free IP Stresser & Free IP Booter Tool 🚀

![Version](https://img.shields.io/badge/Version-5.0-blue)  
**Made by top10booters.co](top10booters.co)** 🌟  

- 🎉 Unleash **Python DDOS V1.0**—your ultimate **IP stresser** and **IP booter**!
- 🌊 Loaded with **UDP DDOS tools**, ⚡ **TCP DDOS tools**, and 🌐 proxy-powered HTTP/HTTPS floods.
- 💪 Built for network testing champs—this **DDOS tool** rocks!

> ⚠️ **Warning**: Educational and legal testing only! Hit your own servers or get permission. Illegal use? Nope! 🚨

---

## ✨ Features

- 🌟 **Flood Arsenal**:
  - 🌊 **UDP Floods** (*UDP DDOS Tool*):
    - 📦 *Plain*: Fixed-payload packet stream.
    - 🎲 *Random*: Random-payload chaos.
    - 💥 *Burst*: 10-packet bursts with pauses.
    - 🕵️ *Spoof*: Fake source IPs (simulated).
    - 🧩 *Frag*: Two-part fragmented packets.
    - ⏸️ *Pulse*: 5-packet pulses with random delays.
    - 📢 *Echo*: "ECHO" payload blasts.
    - 📡 *Multicast*: Random multicast IPs (simulated).
  - ⚡ **TCP Floods** (*TCP DDOS Tool*):
    - 🎯 *SYN Single*: Solo SYN packet spam.
    - 🧵 *SYN Multi*: 10-thread SYN storm.
    - 💾 *Data Single*: Data flood post-connection.
    - 🌩️ *Data Multi*: 10-thread data deluge.
    - 📡 *ACK*: Tiny ACK-like packets.
    - 🔄 *RST*: Quick connect-and-close RSTs.
    - 🎄 *XMAS*: All-flags confusion packets.
    - 🏁 *FIN*: FIN packets to end connections.
    - 🚀 *PSH*: PSH-flagged data pushes.
    - 🪟 *Window*: Random window size trickery.
  - 🌐 **HTTP/HTTPS Floods** (*IP Stresser*):
    - 📡 *GET*: GET request barrage.
    - 📨 *POST*: POST data slams.
    - 🐢 *Slowloris (HTTPS)*: Slow connection creep.
    - 🧠 *HEAD*: Lightweight HEAD requests.
    - 🎭 *Random UA*: Rotating User-Agents with proxies.
    - 🕶️ *Proxy*: Proxied GET flood (daily proxy list).

- 🎨 **Customization**:
  - 🎯 IP & port (1-65535) for precise **IP booter** strikes.
  - ⏱️ Duration in seconds—your game, your time!
  - 📏 Packet size (1-65500 bytes) for UDP/TCP Data.
  - 🧵 TCP styles: Single or 10-thread multi-action!

- 🖥️ **Slick Design**:
  - 🎨 ASCII art intro with "
  - 🌈 Colors: Cyan (start), Green (done), Red (oops).
  - ✨ Emojis: Rockets (🚀), checks (✅), crosses (❌).
  - 📊 Packet/connection counts every time.


- 🕶️ **Proxies**: Fetches fresh HTTP proxies daily from [this list](https://raw.githubusercontent.com/vakhov/fresh-proxy-list/refs/heads/master/http.txt)!

---

## 🛠️ Installation

- 📋 **What You Need**:
  - 🐍 Python 3.x—snag it at [python.org](https://www.python.org/downloads/).
  - 💻 A terminal (Command Prompt, PowerShell, Linux).

- 🚀 **Steps**:
  - 📥 Clone it:
    ```bash
    git clone https://github.com/yourusername/python-ddos-v1.0.git
    cd python-ddos-v1.0
    ```
    *Plug in `yourusername` after uploading!* 😉
  - 📦 Install libs:
    ```bash
    pip install colorama requests
    ```
    - 🌈 `colorama`: Colorful console vibes.
    - 🌐 `requests`: HTTP/HTTPS flood fuel.
  - ▶️ Run it:
    ```bash
    python ddos_tool.py
    ```
    *Rename `ddos_tool.py` to your script name!* 📜

- 💡 **Tips**:
  - 🪟 Windows? Try `python3` if `python` fails.
  - 🔑 TCP SYN/RST/XMAS/FIN/PSH might need admin/root power.
  - 🕶️ Proxies auto-download—needs internet on first run!

---

## 🎮 Usage

- ▶️ **Kick It Off**:
  - 🖥️ You’ll see:
    ```
    ____  ____   ____  _____    ____  ____    ____    ____ 
   /    ||    \ |    ||     |  /    ||    \  /    |  /    |
  |  o  ||  o  )|  o  ||   __| |  o  ||  o  )|  o  | |   __|
  |     ||     ||     ||  |_  |     ||     ||     | |  |  \
  |  _  ||  O  ||  _  ||   _] |  _  ||  O  ||  _  | |  |_  |
  |  |  ||     ||  |  ||  |   |  |  ||     ||  |  | |   _] |
  |__|__||_____||__|__||__|   |__|__||_____||__|__| |____|

    🔹 Protocols 🔹
      1. UDP 🌊
      2. TCP ⚡
      3. HTTP/HTTPS 🌐
    Select protocol (1-3):
    ```

- 🎯 **Pick Your Attack**:
  - 🌊 `1` for UDP, ⚡ `2` for TCP, 🌐 `3` for HTTP/HTTPS.

- ⚙️ **Set It Up**:
  - 🌊 **UDP**: Pick 1-8, add IP, port, duration, packet size.
  - ⚡ **TCP**: Pick 1-10, add IP, port, duration (packet size for Data).
  - 🌐 **HTTP/HTTPS**: Pick 1-6, add URL, duration.

- 📋 **Examples**:
  - 🌊 *UDP Pulse*:
    ```
    Select protocol (1-3): 1
    🔹 UDP Methods 🔹
      1. Plain  2. Random  3. Burst  4. Spoof  5. Frag
      6. Pulse  7. Echo  8. Multicast
    Select method (1-8): 6
    Enter server IP: 192.168.1.100
    Enter port (1-65535): 12345
    Enter duration (seconds): 5
    Enter packet size (1-65500): 1024
    [🚀] UDP Pulse Flood on 192.168.1.100:12345 | 1024 bytes | 5s...
    [✅] Done! Sent 250 packets.
    ```
  - ⚡ *TCP Window*:
    ```
    Select protocol (1-3): 2
    🔹 TCP Methods 🔹
      1. SYN Single  2. SYN Multi  3. Data Single  4. Data Multi
      5. ACK  6. RST  7. XMAS  8. FIN  9. PSH  10. Window
    Select method (1-10): 10
    Enter server IP: 192.168.1.100
    Enter port (1-65535): 80
    Enter duration (seconds): 5
    [🚀] TCP Window Flood on 192.168.1.100:80 | 5s...
    [✅] Done! Sent 1500 Window packets.
    ```
  - 🌐 *HTTP Proxy*:
    ```
    Select protocol (1-3): 3
    🔹 HTTP/HTTPS Methods 🔹
      1. GET  2. POST  3. Slowloris  4. HEAD  5. Random UA  6. Proxy
    Select method (1-6): 6
    Enter URL (e.g., http://example.com): http://192.168.1.100
    Enter duration (seconds): 10
    [🚀] HTTP Proxy Flood on http://192.168.1.100 | 10s (Proxies: 500)...
    [✅] Done! Sent 300 proxied requests.
    ```

---

## 🧠 How It Works

- 🌊 **UDP DDOS Tool**: Slams ports with plain, random, burst, spoofed, fragmented, pulsed, echoed, or multicast packets.
- ⚡ **TCP DDOS Tool**: Jams with SYN, data, ACK, RST, XMAS, FIN, PSH, or window-size tricks.
- 🌐 **IP Stresser**: Pounds web servers with GET, POST, HEAD, Slowloris, random UA, or proxied hits.
- 🎯 **IP Booter**: Locks onto IPs and ports with precision.

- 📈 Tracks every flood’s impact with packet/connection counts!

---

## 🙌 Credits
- 🎯 Your hub for elite **IP stresser** and **IP booter** tools—check us out!

---

## 📜 License

- ⚖️ For educational and legal testing only.
- 🚫 No formal license—keep it clean and legal!

---

## 🔑 Keywords

- 🌐 FREE IP Stresser
- 🎯 FREE IP Booter
- 💥 FREE DDOS Tool
- 🌊 UDP DDOS Tool
- ⚡ TCP DDOS Tool

