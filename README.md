# eegid
> Universal identifier in the Ethereum ecosystem

The identifier is composed of two parts separated by a colon (`:`):
1. dataset - `group`, `event`, etc. (see bellow)
2. random hexadecimal number - `58a`, `f30`, etc. (usually 3-4 characters)

Examples:
- `event:a8f`
- `person:11a`

## Datasets

| Dataset | Repository | ID Example |
| --- | --- | --- |
| Group | [ethcd](https://github.com/ethereumeg/ethcd) | `group:4da` |
| Person | [ethcd](https://github.com/ethereumeg/ethcd) | `person:f30` |
| Event Series | [ethevents](https://github.com/ethereumeg/ethevents-db) | `series:254` |
| Event | [ethevents](https://github.com/ethereumeg/ethevents-db) | `event:8a0` |
