<img src="https://i.imgur.com/xkTrLGh.png">

## Battles

Contract address: `EQDUNg1MtGkY3c1bmQJsxvwuzLZ4RCYyimIoSy8NQdqqlE6V`<br>

[Website](https://jackpot-ton.com) <br>
[Telegram mini app](https://t.me/jackpot_ton_bot/Jackpot_ton)

A user can create a "Battle" for any amount above `min_battle_value` by sending a transaction with `OP = 1`.<br>
Getter: `get_min_battle_value`

After that, all TON will be sent to a new battle address.<br>
The battle address will remain active until either the second player joins the battle or the battle creator cancels it.

To participate in the battle, the second participant must send a slightly larger number of coins to the battle address with `OP = 777`.<br>
`(50 TON vs 50.0001 TON)`

**Each battle participant has a 50% chance of winning.**<br>
However, the fees for participants will be different.

In case of victory, the fee for the battle creator will be 2.5%.<br>
For the battle participant, it will be 5%.
