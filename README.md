<h2 align=center>Run Nexus Prover Beta</h2>

## Cấu hình yêu cầu
- Min 4 RAM 
- Nên : 6 GB RAM
- Có thể mua ở đây: ([https://pq.hosting/?from=622403&lang=en](https://contabo.com/en/vps/cloud-vps-0/)) 
---

## Cài đặt
- lệnh
```bash
curl -sSL https://raw.githubusercontent.com/zunxbt/nexus-prover/main/nexus.sh | bash
```
- hoặc lệnh
```bash
wget -qO - https://raw.githubusercontent.com/zunxbt/nexus-prover/main/nexus.sh | bash
```

## Kiểm tra trạng thái
- Lệnh để kiểm tra
```bash
systemctl status nexus.service
```
- Lệnh check log
```bash
journalctl -u nexus.service -f -n 50
```
- You will see something like this, it means, it is fine

![Screenshot 2024-10-09 115039](https://github.com/user-attachments/assets/3d3065d8-cb88-44ca-88b8-ac072bcf9eff)
