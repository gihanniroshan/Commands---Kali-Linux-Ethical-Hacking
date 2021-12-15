### Simple Scan using dirb `default wordlist`

```
dirb http://10.10.3.123
```

### with `SSL`
```
dirb https://10.10.3.123
```

### `-X` flag --> finding `.php` extension files
```
dirb http://10.10.3.123 -X .php
```
Other extensions - `.html`, `.js`, `.css`
### using another wordlist
```
dirb http://10.10.3.123 /usr/share/wordlists/rockyou.txt
```
