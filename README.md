TF-FOV allows players to manually set their field of view beyond the arbitrary limit of the `fov_desired` cvar.

Console Elements
==================
This plugin exposes the following console elements:
| Name | Description | Default | Notes |
|------|------|------|------|
| `sv_fov_max` | Maximum value players can set their FOV to. | 120.0 | None |
| `sm_fov` | Set the calling players FOV to the specified value. | N/A | Input must be an integer or a float. |
| `sm_fov_clear` | Clear the calling players FOV override. | N/A | None |

Dependencies
==================
- [morecolors](https://raw.githubusercontent.com/DoctorMcKay/sourcemod-plugins/master/scripting/include/morecolors.inc) (*compilation only*)

# License
TF-FOV is released under version 3 of the GNU Affero General Public License. For more info, see `LICENSE.md`.

# Notes
Currently only works on servers hosted on Linux machines.

Servers running a SourceMod version <1.11.6820 will need to manually install [DHooks](https://forums.alliedmods.net/showthread.php?p=2588686#post2588686).
