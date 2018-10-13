# ansible-cis-profile
Usage:
1. From AWX or Tower.  
On AWX or Tower, special consideration for python virtenv. E.g report generation from localhost will not work. Delegate to play host.
2. Or CLI  
```#> ansible-playbook -i  inventory_file sec_hardening.yaml```

Basic HTML report generated with Jinja2.
  
