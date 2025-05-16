# 🗄️ Bash Backup Scripts

A collection of simple Bash scripts to automate backups of files, directories, or services (like Pi-hole), using only standard tools available on most Linux distributions.

## 📦 Contents

This repository includes:

- `pihole_backup.sh`: Backs up Pi-hole configuration and retains only the 3 most recent backups.

- (More scripts coming soon...)

## 🛠 Requirements

- Bash
- Standard Unix utilities like `tar`, `find`, `xargs`, `mkdir`, `rm`, etc.
- Sufficient permissions to access the files or services being backed up (may require `sudo`)

## 🚀 Usage

For each script:

```bash
chmod +x script_name.sh
./script_name.sh

To automate via cron:
0 3 * * * /absolute/path/to/script.sh >> /var/log/script.log 2>&1

🔒 Security

Make sure to:

    Avoid storing sensitive backups in public or unsecured locations.

    Restrict access to the scripts and generated backup files.

🧾 License

This project is released under The Unlicense: you are free to do whatever you want with this code. It is dedicated to the public domain, with no restrictions.

For more information, visit: unlicense.org
🙋‍♂️ Contributing

Contributions, ideas, and feedback are welcome! Feel free to open an issue or a pull request.
