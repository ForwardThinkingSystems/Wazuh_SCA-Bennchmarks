# Wazuh_SCA-Benchmarks

##Deploy the agent with RHEL8 CIS profile 

curl -sSL https://raw.githubusercontent.com/ForwardThinkingSystems/Wazuh_SCA-Benchmarks/main/wazuh-agent-deploy.sh | bash


##Deploy the AuditD setup

```sudo curl -s -L https://raw.githubusercontent.com/ForwardThinkingSystems/Wazuh_SCA-Benchmarks/main/FTS-Audit-Rules.sh | bash```


##Deploy the CIS setup script (Run as root 'sudo su')

```curl -s -L https://raw.githubusercontent.com/ForwardThinkingSystems/Wazuh_SCA-Benchmarks/main/FTS-CIS-Profile.sh | bash```

