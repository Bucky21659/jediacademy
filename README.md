# Speed Academy

Source port of the singleplayer of Star Wars Jedi Knight: Jedi Academy.
Focuses on staying true to the original game to be used for speedrun purposes.
See the [speedrun.com leaderboard](https://www.speedrun.com/jka) for more information.

Based on the original source code released by Raven, see README.txt.

## New Console Variables

### HUD

#### `cg_drawMovementRestriction` (0 or 1)

Draw the currently active movement restriction.
`--` represents no restrictions.
Default: `1`.

#### `cg_drawOverbounceInfo` (0 or 1)

Draw overbounce probabilities, G is for Go, J is for Jump.
Default: `0`.

#### `cg_drawSpeedrunTotalTimer` (0-3)

Draw a total run timer.
Higher values show more decimals.
Note that this is currently not the timing that is used on the leaderboards.
Default: `0`.

#### `cg_drawSpeedrunLevelTimer` (0-3)

Draw a current level timer.
Higher values show more decimals.
Note that this is currently not the timing that is used on the leaderboards.
Default: `0`.

#### `cg_drawStrafeHelper` (0 or 1)

Draw a strafe helper.
Default: `0`.

#### `cg_strafeHelperCenter` (0 or 1)

Put the strafe helper in the center of the screen.
Default: `1`.

#### `cg_strafeHelperCenterMarker` (0 or 1)

Draw a marker in the center of the strafe helper.
Default: `1`.

#### `cg_strafeHelperHeight` (#)

Height of strafe helper bar.
Default: `20.0`.

#### `cg_strafeHelperScale` (#)

Horizontal scale of the strafe helper.
Angles correspond directly to the field of view if this scale is set to `360/cg_fov`.
Default: `4.0`.

#### `cg_strafeHelperSpeedScale` (#)

Scale of the text for speed display.
Default: `0.9`.

#### `cg_strafeHelperSpeedY` (#)

Vertical offset of the text for speed display, relative to the strafe helper.
Default: `0.0` (directly under the strafe helper).

#### `cg_strafeHelperY` (#)

Vertical position of the strafe helper.
Default: `50.0`.

### Gameplay

#### `g_stickLandings` (0 or 1)

Enable or disable the usual slowdown applied when landing ("velocity reduction on ground impact, VRGI").
Default: 1.

#### `g_disableCrouchBoosts` (0 or 1)

Disable "crouch boosting".
VRGI can not be bypassed by crouching anymore.
Default: `0`.

#### `g_fixSpinGlitch` (0 or 1)

Disable "spin glitch".
VRGI can not be bypassed by spinning anymore.
Default: `0`.

#### `g_disableRandomBoosts` (0 or 1)

Disable "random" boosts.
**Cheat protected**.
Default: `0`.

#### `g_selfKnockback` (0, or 1)

Allow players to damage boost themselves with explosive weapons.
**Cheat protected**.
Default: `0`.

#### `sv_speedrunModeIL` (0 or 1)

Individual-level run mode.
When set to `1`, ingame timer will reset every time an autosave is loaded.
When set to `0`, ingame timer will reset only when yavin1b is loaded.
Note that this is currently not the timing that is used on the leaderboards.
Default: `0`.
