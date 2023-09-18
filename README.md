## Vector-role
This role can install Vector for Clickhouse

#### Role Variables
vector_version - version of Vector to install

#### Example Playbook
```
    - name: Install Vector
      hosts: servers
      roles:
        - vector
```
