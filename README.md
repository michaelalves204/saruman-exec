## Saruman

Monitor the CPU and memory performance of your processes

## How to use

```
chmod +x saruman

./saruman 8080 # use whatever port you want
```
Example:
```
curl -X POST "http://localhost:8080/processes" -d '{"message": "measuring firefox performance", "processName": "firefox-bin"}'
```

A file will be generated with the name of the process, containing the monitoring log, following the example the generated file would be **firefox-bin.json**
