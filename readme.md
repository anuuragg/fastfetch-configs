# Steps

# 1. Install Fastfetch

```bash
sudo apt update
sudo apt install fastfetch
```

### 2. Create the configuration directory

```bash
mkdir -p ~/.config/fastfetch
```

### 3. Copy the configuration file

Copy `config.jsonc` from the repository's `fastfetch/` directory to:

```text
~/.config/fastfetch/config.jsonc
```

### 4. Test Fastfetch

```bash
fastfetch
```

### 5. Enable automatic startup

```bash
echo 'fastfetch' >> ~/.bashrc
```

### 6. Apply the changes

```bash
source ~/.bashrc
```

