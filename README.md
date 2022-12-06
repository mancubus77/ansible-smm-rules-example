Simple example how to capture list smm IDs and run show SMM rules based on these IDs 

**Run**
```
git clone https://github.com/mancubus77/ansible-smm-rules-example.git
cd ansible-smm-rules-example
ansible-playbook main.yaml
```

**Output**
```
TASK [Generate show smm command] ***************************************************************************************************************
ok: [localhost] => {
    "msg": "show SmmRuleSet=1"
}

TASK [Generate show smm command] ***************************************************************************************************************
ok: [localhost] => {
    "msg": "show SmmRuleSet=2"
}

TASK [Generate show smm command] ***************************************************************************************************************
ok: [localhost] => {
    "msg": "show SmmRuleSet=3"
}

TASK [Generate show smm command] ***************************************************************************************************************
ok: [localhost] => {
    "msg": "show SmmRuleSet=4"
}

```
