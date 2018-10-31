quick steps to replicate:
1. edit logstash.conf to specify your own elasticsearch host/credentials in the `ouptut{}` section
2. in kibana dev console, paste in and execute all the calls in `users_roles.json`
3. in kibana dev consule, paste in and excute the index mappings/settings in `mapping.json`
4. ingest data (500k records) into your elasticsearch cluser via
  ```
  cat data-500k.csv.bz2 | logstash -f logstash.conf
  ```
5. do enjoy!
