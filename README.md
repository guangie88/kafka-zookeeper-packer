# `kafka-zookeeper-packer`

Packer set-up to build image with Kafka + Zookeeper.

## What to do

Install Packer and Ansible.

Run the following command:

```bash
packer build \
    -var-file=vars.json \
    packer.json
```
