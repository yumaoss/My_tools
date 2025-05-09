wget -qO - https://raw.githubusercontent.com/yumaoss/my_tools/refs/heads/main/archive.key | sudo gpg --dearmor -vo /etc/apt/keyrings/xanmod-archive-keyring.gpg


wget https://raw.githubusercontent.com/yumaoss/my_tools/refs/heads/main/check_x86-64_psabi.sh && chmod +x check_x86-64_psabi.sh && ./check_x86-64_psabi.sh
