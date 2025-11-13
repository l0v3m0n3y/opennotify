# opennotify
api for open-notify.org nasa information site 
# Example
```nim
import asyncdispatch, opennotify, json, strutils
let data = waitFor iss_now()
echo data
```

# Launch (your script)
```
nim c -d:ssl -r  your_app.nim
```
