philranzato.configure-network
=========

Configure network for a VM:
- Assign a static IP
- Change hostname

Requirements
------------

None.

Role Variables
--------------

```yaml
network:
  conn_name: ens33-test
  ifname: ens33
  ip4: 172.16.15.193
  gw4: 172.16.15.2
  dns4:
  - 172.16.15.2
  - 8.8.8.8
```

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- name: "Configure Network"
  hosts: servers
  roles:
  - role: philranzato.configure-network
```

License
-------

MIT License

Author Information
------------------

Get in touch with me at:
- [LinkedIn](www.linkedin.com/in/phil-ranzato-47b8bb194)
- [GitHub](https://github.com/PhilRanzato)
- [Medium](https://medium.com/@philranzato)
