# Todo's

- [ ] Run only when just macbook
- [x] Media controls back to default F keys
- [ ] Port over QMK keymap
- [ ] Normal layers


# How to run 
```
sudo kanata --cfg your-config.kbd

sudo ~/Downloads/kanata_macos_arm64 --cfg '~/Users/mitchelvaneijgen~/Library/CloudStorage/Dropbox/Code/Github/kanata/internal.kbd'
```

# Macbook Pro M2 internatial keybaord layer
```
(defsrc
  esc    f1   f2   f3   f4   f5   f6   f7   f8   f9   f10  f11  f12
  IntlBackslash      1    2    3    4    5    6    7    8    9    0    -    =    bspc
  tab    q    w    e    r    t    y    u    i    o    p    [    ]
  caps   a    s    d    f    g    h    j    k    l    ;    '    \    ret
  lsft   `  z    x    c    v    b    n    m    ,    .    /    ▲   rsft
  fn   lctl  lalt lmet          spc         rmet ralt ◀    ▼    ▶
)
```