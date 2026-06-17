<p align="center">
  <a href="https://heroku.com/deploy?template=https://github.com/TEAM-VBIT/NXBIT">
    <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
  </a>
</p>

---

### 🔧 Quick Setup

1. **Upgrade & Update:**
   ```bash
   sudo apt-get update && sudo apt-get upgrade -y
   ```

2. **Install Required Packages:**
   ```bash
   sudo apt-get install python3-pip ffmpeg -y
   ```
3. **Setting up PIP**
   ```bash
   sudo pip3 install -U pip
   ```
4. **Clone the Repository**
   ```bash
   git clone https://github.com/TEAM-VBIT/NXBIT && cd NXBIT
   ```
5. **Install Requirements**
   ```bash
   pip3 install -U -r requirements.txt
   ```
6. **Create .env  with sample.env**
   ```bash
   cp sample.env .env
   ```
   - Edit .env with your vars
7. **Editing Vars:**
   ```bash
   vi .env
   ```
   - Edit .env with your values.
   - Press `I` button on keyboard to start editing.
   - Press `Ctrl + C`  once you are done with editing vars and type `:wq` to save .env or `:qa` to exit editing.
8. **Installing tmux**
    ```bash
    sudo apt install tmux -y && tmux
    ```
9. **Run the Bot**
    ```bash
    bash start
    ```

---
