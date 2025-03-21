# Temporary

## Command für erstes Macbook
```bash
curl -so wazuh-agent.pkg https://packages.wazuh.com/4.x/macos/wazuh-agent-4.11.1-1.arm64.pkg && echo "WAZUH_MANAGER='213.239.216.151' && WAZUH_AGENT_NAME='Test-Macbook-1'" > /tmp/wazuh_envs && sudo installer -pkg ./wazuh-agent.pkg -target /
sudo /Library/Ossec/bin/wazuh-control start
```

---
## Command für zweites Macbook
```bash
curl -so wazuh-agent.pkg https://packages.wazuh.com/4.x/macos/wazuh-agent-4.11.1-1.arm64.pkg && echo "WAZUH_MANAGER='213.239.216.151' && WAZUH_AGENT_NAME='Test-Macbook-2'" > /tmp/wazuh_envs && sudo installer -pkg ./wazuh-agent.pkg -target /
sudo /Library/Ossec/bin/wazuh-control start
```

---
## Command für drittes Macbook
```bash
curl -so wazuh-agent.pkg https://packages.wazuh.com/4.x/macos/wazuh-agent-4.11.1-1.arm64.pkg && echo "WAZUH_MANAGER='213.239.216.151' && WAZUH_AGENT_NAME='Test-Macbook-3'" > /tmp/wazuh_envs && sudo installer -pkg ./wazuh-agent.pkg -target /
sudo /Library/Ossec/bin/wazuh-control start
```
