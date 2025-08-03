## 📥 Корисні команди з відео:

### 1. Snapcraft — [https://snapcraft.io/node](https://snapcraft.io/node)

```bash
sudo snap install node --classic
```

### 2. Node.js офіційний сайт — [https://nodejs.org](https://nodejs.org)

**Встановлення через nvm:**

```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash
\. "$HOME/.nvm/nvm.sh"
nvm install 22
```

### 3. Node.js офіційний сайт — [https://nodejs.org](https://nodejs.org)

**Standalone binary встановлення:**

```bash
tar -xf node-v22.0.0-linux-x64.tar.xz
sudo mv node-v22.0.0-linux-x64 /usr/local/nodejs
echo 'export PATH=/usr/local/nodejs/bin:$PATH' >> ~/.bashrc
source ~/.bashrc
```

### 4. Встановлення через офіційний репозиторій Ubuntu (APT):

```bash
sudo apt install nodejs
sudo apt install npm
```

### 5. Встановлення через NodeSource:

```bash
curl -fsSL https://deb.nodesource.com/setup_22.x | sudo -E bash -
sudo apt install nodejs
```
