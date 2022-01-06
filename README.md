---
- name: Demo message
  hosts: localhost
  tasks:
    - name: Printing message
      debug:
        msg: "Hello Automation Team"
