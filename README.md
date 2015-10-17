# OPK CLI: Command line interface for Adafruit IO  

```
./push
  --feed [feed id] Example: feed r-pi-temperature
  --key [x-aio-key] Example: 2d3be35cf8f613afa0d59f2240c00aedf8bdanb49
  --verbose Use for debug output

Usage: echo 42 | ./push --feed r-pi-temperature --key 2d3be35cf8f613afa0d59f2240c00aedf8bdanb49 --verbose
Usage: echo '{"value":89}' | ./push --feed r-pi-temperature --key 2d3be35cf8f613afa0d59f2240c00aedf8bdanb49 --verbose
```

## Requirements
- Node.js v0.12.x

