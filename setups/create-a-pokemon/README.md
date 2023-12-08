## Create-a-Pokemon

Create-a-Pokemon is mail corruption that targets an empty PC slot to create something from nothing.

### Cloner + Master Ball

One corruption CAP produces data that sums to 0 modulo 65536.

Here the species 0xFFFF and the item 1 meets that criteria. This cloner will softlock the Move Items cursor, so Move Items should be opened directly to box 3 to bag the Master Ball.

|||
|---|---|
| _ _ _ _ _ _ _ | AIR LOCK |
| *???* | BEAUTY |

### Grab ACE glitch species

Two corruption CAP begins like one corruption then does an action to change the checksum favorably for the second corruption.

Here an egg is created that should be picked up and put down in the PC before the second set of phrases. The result is species 0x1453 which can [execute arbitrary code.](https://pastebin.com/raw/pDXf5rGD)

|||
|---|---|
| BECOMES | NATURAL |
| *???* | _ _ _ _ _ _ _ |

|||
|---|---|
| UNDERSTAND | *NATURAL* |
| TAKE THAT | I |
