# check_postfixmailqueue
icinga/nagios plugin to monitor the postfix mailqueue using the `postqueue` command.

based on: https://exchange.icinga.org/exchange/check_postfixmailqueue

this version mainly adds perfomance data to the plugin output.

## Usage

`check_postfixmailqueue -w -c [ -v ] [ -h ]`

```
-w  Queue size at which a warning is triggered"
-c  Queue size at which a critical is triggered"
-v  Verbose output (ignored for now)"
-h  Show this page"
```

NOTE: Depending on your config, the nagios user will probably be needed to be added to the postfix group for this script to function correctly

