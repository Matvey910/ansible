# Ansible file

## 安裝
```bash
    #安裝
    dnf -y install eppel-release
    dnf -y install ansible

    # 檢查版本
    ansible --version

    #測試 Ping 模組可以執行
    ansible -m ping localhost
```

## 機器庫存清單 inventory

- 預設檔案 /etc/ansible/hosts
- 自訂清單
  ```bash
  mkdir ~/ansible
  cd ~/ansible
  vi hosts
  ```