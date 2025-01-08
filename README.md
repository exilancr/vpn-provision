# Amnezia server deploy
> [!CAUTION]
> Make sure that you checked and understood everything in this repo.
>
> This repo is **NOT** intended for end users.

# How to use

0. Clone the repo.

1. Create configs:
- `inventory.yml`
- `group_vars/all.yml`
- `roles/amnezia/defaults/main.yml`

2. Run ansible.
```bash
ansible-playbook -i inventory.yml provision.yml
```

3. Find client configs in `client_configs`

4. Configure AmneziaWG client(s)
