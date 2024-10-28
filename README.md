wget -qO - https://github.com/yumaoss/xanmod_tools/raw/refs/heads/main/archive.key | sudo gpg --dearmor -vo /usr/share/keyrings/xanmod-archive-keyring.gpg
wget https://raw.githubusercontent.com/yumaoss/xanmod_tools/refs/heads/main/check_x86-64_psabi.sh && chmod +x check_x86-64_psabi.sh && ./check_x86-64_psabi.sh
