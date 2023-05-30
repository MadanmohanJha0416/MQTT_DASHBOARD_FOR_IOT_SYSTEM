Rename the .env.local to .env  
`mv .env.local .env`

Edit the .env and set the MQTT broker URL that you are using


NAME=MADANMOHANJHA
DASHBOARD_TITLE=MY DASHBOARD
MQTT_BROKER=ws:____________
MQTT_TOPIC=sensorReadings
```

Install the dependencies and run the project
`npm install && npm run dev`
