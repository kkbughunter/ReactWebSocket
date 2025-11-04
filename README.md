# Run 
```bash
npm install mqtt
npm install recharts
npm run dev
```

# Run Broker
```bash
./bin/vernemq stop
./bin/vernemq start
```

```bash
mosquitto_pub -h astraval.com -p 1883 -u testuser -P password1 -i testclient -t iet/temp -m hi

mosquitto_sub -h astraval.com -p 1883 -u testuser -P password1 -i testclient -t iet/temp
```