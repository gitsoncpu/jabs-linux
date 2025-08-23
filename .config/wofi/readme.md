for exiting on repeated keypresses, make ~/.local/bin/wofi-toggle.sh 

```bash
#!/bin/bash
if pgrep -x "wofi" > /dev/null; then
  pkill wofi
else
  wofi
fi
