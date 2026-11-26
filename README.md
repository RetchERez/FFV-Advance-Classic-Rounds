# Final Fantasy V Advance: Classic Rounds

Turn-based battles for **Final Fantasy V Advance** (GBA), in the style of the classic Final Fantasy games.

In **Wait** mode, everyone picks a command, then the round plays out in speed order, fastest first. There are no ATB bars in Wait mode. **Active** mode is exactly the original game.

Pick the mode in **Config > Battle Mode**, as usual. There is no new switch.

## How Wait mode works now

- Every party member and every enemy gets one turn per round
- Party members pick commands one after another; time stays frozen while you choose
- When everyone has picked, the actions play out fastest first
- Speed uses the game's own formula (Agility and equipment weight); Haste and Slow change your place in the order
- Preemptive strike: the party gets a free first round
- Back attack: the enemies get a free first round
- Quick: the caster takes two turns in a row; everyone else keeps their picked action and acts after
- Counterattacks still happen right away, as reactions
- Statuses that run on a timer (Stop, Poison, Regen, Doom) only count down while actions play out, so they last a few more rounds than in Active

## Download

Get the zip from the [Releases](../../releases) page. It contains three IPS patches and a readme. No ROM is included.

| Patch | Apply to | CRC32 before | CRC32 after |
|---|---|---|---|
| `FFV_Advance_Classic_Rounds_v1.0_Europe.ips` | Final Fantasy V Advance (Europe) (En,Fr,De,Es,It) | `7197117E` | `FC53E188` |
| `FFV_Advance_Classic_Rounds_v1.0_USA.ips` | Final Fantasy V Advance (USA) | `7A24AB0C` | `5F7EF9E7` |
| `FFV_Advance_Classic_Rounds_v1.0_USA_for_Action_Growth_v1.4.ips` | USA ROM with [Action Growth v1.4](https://github.com/RetchERez/FFV-GBA-Action-Growth) | `58AAADE0` | `7DF0FF0B` |

Back up your save before patching.

## Works with

**Europe version**
- Final Fantasy V Advance Sound Restoration v3.0 by Bregalad, ipatix and Dwedit (with or without orchestra)
- Final Fantasy V Color Correction and Improvement (made for the Europe ROM only)
- Apply the patches in any order; the result is the same

**USA version**
- Sound Restoration v3.0 (America)
- Action Growth v1.4 (use the Action Growth file)
- Color Correction and Improvement does not work on the USA ROM; it scrambles sprites even without this mod

## Testing

Tested by script in an emulator on both regions:

- Wait mode: enemies never act while a menu is open; Active mode matches the original
- Regular battles, early and late game, and saves from both regions
- 74 boss and special battles per region, including Gilgamesh, Exdeath, Omega, Atomos, Soul Cannon, Archeoaevis and Necrophobe; none got stuck
- Galuf vs Exdeath ends as it should
- Jump, Mimic, Hide, Focus, Kick, Aim, Flee and L+R escape
- Stop, Paralyze, Berserk, Confuse and Sleep
- Quick, cast from the real menu
- Preemptive strikes and back attacks
- Europe with Sound Restoration and Color Correction stacked together

Please report anything odd in [Issues](../../issues), especially a battle that stops moving, with the battle name and what you picked that round.

## Credits

By RetchERezzed.
