# system-wide key remap

## create a new file **scancode.reg**

```
Windows Registry Editor Version 5.00
[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Keyboard Layout]
"Scancode Map"=hex:00,00,00,00,00,00,00,00,02,00,00,00,##,##,##,##,00,00,00,00 
```

replace the sharps with key codes in format:
to-key(2 bytes), from-key(2 bytes)

## double click the file to write its content to `regedit`

## reboot the computer 