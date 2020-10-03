# pycolour

Easily colour your text in the command line

black   = '\033[30m'
red = '\033[31m'
green   = '\033[32m'
yellow  = '\033[33m'
blue    = '\033[34m'
purple  = '\033[35m'
cyan    = '\033[36m'
white   = '\033[37m'
bold    = '\033[1m'
normal  = '\033[22m'
end     = '\033[0m'

- Black
- Red
- Green
- Yellow
- Blue
- Purple
- Cyan
- White
- Bold
- Normal
- end

Usage:
```print(pycolour.red + "Red Text" + pycolour.end)```

Recommendation:
Use ```import pycolour as p``` instead of ```import pycolour``` to make referencing easier