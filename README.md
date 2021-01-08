# serial_report

default structure for ansible

Generates Serial Number Reports for Cisco devices and emails them in either CSV or TXT format.

If using in AWX (or modify in ansible playbook) include these vars:
```
email_address:
from_email:
smtp_server:
report_format:
```