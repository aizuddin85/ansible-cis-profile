# ansible-cis-profile
Usage:
1. From AWX or Tower.
On tower, the delegation must not be localhost for report generating due to python virtlenv.
2. Or CLI  
```#> ansible-playbook -i  inventory_file sec_hardening.yaml```

Basic HTML report generated with Jinja2.
  
