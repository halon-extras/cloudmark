## cloudmark_as(options, senderip, senderhelo, sender, recipients, fp)
Scan a message with Cloudmarks Authority server (using HTTP POST).

**Params**

- options `array` - options array

**Returns**: score as number, None on error.

The following options are available in the **options** array.

- host `string` - IP-address of the Authority server. required
- port `number` - TCP port. The default is 80.
- timeout `number` - Timeout in seconds. The default is 5 seconds.

## cloudmark_ip(options, senderip)
Scan an IP with Cloudmarks Authority server (using HTTP POST).

**Params**

- options `array` - options array
- senderip `string` - IP address

**Returns**: score as number, None on error.

The following options are available in the **options** array.

- host `string` - IP-address or hostname of the Authority server. required
- port `number` - TCP port. The default is 80.
- timeout `number` - Timeout in seconds. The default is 5 seconds.
