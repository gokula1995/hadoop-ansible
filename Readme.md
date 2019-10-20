### To run the playbook
```
ansible-playbook -i hosts/abc main.yaml --become
```


## Handlers to start the service
```
 ansible -i /hosts/abc hadoop-nodes -m shell -a "/opt/hadoop-3.0.0/bin/start-all.sh"
```

## Handlers to stop the Service

```
ansible -i /hosts/abc hadoop-nodes -m shell -a "/opt/hadoop-3.0.0/bin/stop-all.sh"
```


