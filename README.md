# mqtt-mysql
MQTT mysql client and server


Login mqsql and run: 
```
create user mqttuser identified by 'mqttpass';
grant all privileges on mqtt.* to mqttuser@'%' identified by 'mqttpass';
```

Run ```mqtt-mysql-admin``` to clean up database.
