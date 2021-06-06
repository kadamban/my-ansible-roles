Edit the hosts.yml file, and ensure your key exists across all nodes (coming soon, this code will add it all for you), then simply run:

```
ansible-playbook -i hosts.yml site.yml
```
