# Likely

| dice:1d6 | Header 1                       |
| -------- | ------------------------------ |
| 1        | No, and a random event occurs  |
| 2        | Yes, but...                    |
| 3        | No                             |
| 4        | Yes                            |
| 5        | No, but...                     |
| 6        | Yes, and a random event occurs |
^likely

# Unlikely

| dice:1d% | Header 1                     |
| -------- | ---------------------------- |
| 1-3      | Exceptional yes              |
| 4-14     | No and a random event occurs |
| 15-73    | No                           |
| 74-78    | Yes, but...                  |
| 79-94    | Yes                          |
| 95-97    | Exceptional no               |
| 98-100   | No, but...                   |
^unlikely

The above table was adapted by simulating dicerolls 10k times using  ~/Documents/obsidianshellcommands/test-probs-unlikely.py and then working backwards to a percentage table

# Impossible

| dice:1d% | Header 1                       |
| -------- | ------------------------------ |
| 1-6      | Yes, and a random event occurs |
| 7-58     | No, but...                     |
| 59-84    | No                             |
| 85-92    | No, and a random event occurs  |
| 93-97    | Yes                            |
| 98-99    | Exceptional yes                |
| 99-100   | Exceptional no                 |
^impossible

The above table was adapted by simulating dicerolls 10k times using  ~/Documents/obsidianshellcommands/test-probs-impossible.py and then working backwards to a percentage table
# Random event

| dice:2d6 | Header                              |
| -------- | ----------------------------------- |
| 2        | A very bad thing happens to the PC  |
| 3        | A very bad thing happens to an NPC  |
| 4        | A curious thing happens             |
| 5        | A bad thing happens to the PC       |
| 6        | A bad thing happens to an NPC       |
| 7        | A new character is introduced       |
| 8        | A good thing happens to the PC      |
| 9        | A good thing happens to an NPC      |
| 10       | A truth is revealed                 |
| 11       | A very good thing happens to the PC |
| 12       | A very good thing happens to an NPC |
^randomEvent