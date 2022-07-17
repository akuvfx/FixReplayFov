# Installation

- Download latest version from [releases page](https://github.com/akuvfx/FixReplayFov/releases).
- Put `FixReplayFovPlugin.dll` in bakkesmod's plugins folder.
- Load plugin in game: `plugin load FixReplayFovPlugin`.

# Usage

You can set fov using `cl_fov` cvar, and modify fov for povs using `cl_fov_pov`.

To fix chaning the FOV via scroll wheel, you need to bind `cl_fov_zoom_in` and `cl_fov_zoom_out` like this:

```
bind MouseScrollDown "cl_fov_zoom_out 2.5"
bind MouseScrollUp "cl_fov_zoom_in 2.5"
```

## Cvars and Notifiers

Cvars:

- `cl_fov`
- `cl_fov_pov`

Notifiers:

- `cl_fov_zoom_in <value>`
- `cl_fov_zoom_out <value>`
