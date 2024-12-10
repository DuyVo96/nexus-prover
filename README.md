<h2 align=center>Run Nexus Prover Beta</h2>

## Info
- Min 4 RAM
- Recommended : 6 GB RAM

## Installation
- You can use either this command
```bash
curl -sSL https://raw.githubusercontent.com/zunxbt/nexus-prover/main/nexus.sh | bash
```
- Or this command to run this script
```bash
wget -qO - https://raw.githubusercontent.com/zunxbt/nexus-prover/main/nexus.sh | bash
```

## Status
- You can check prover status using this command
```bash
systemctl status nexus.service
```
- To check logs, use the below command
```bash
journalctl -u nexus.service -f -n 50
```

![Screenshot 2024-10-09 115039](https://github.com/user-attachments/assets/3d3065d8-cb88-44ca-88b8-ac072bcf9eff)
