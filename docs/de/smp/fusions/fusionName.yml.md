# Fusion Example Configuration

```yaml
enabled: true
```

```yaml
name: Invisible Item Frame
```

```yaml
displayItem: ITEM_FRAME
```

```yaml
description: <white>Craft an <gold>invisible <white>Item Frame
```

```yaml
tags: Decoration; Display; Aesthetic;
```

```yaml
input:
  (Glow) Item Frame:
    '0':
    - item: ITEM_FRAME
    - amount: '1'
    - data: ''
    '1':
    - item: GLOW_ITEM_FRAME
    - amount: '1'
    - data: ''
  Any sort of Glass Pane:
    '0':
    - item: Glass_Pane
    - amount: '4'
    - data: ''
    ...
```

```yaml
output:
  '0':
  - item: ITEM_FRAME
  - amount: '4'
  - name: <gold>Invisible Item Frame
  - lore: <white>Place this Item Frame and it will be invisible! <newline><red>Empty
      Item Frames will be destroyed and dropped after one minute!
  - data: INVISIBLE
  ...
```
