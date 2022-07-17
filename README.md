# Fix Replay Fov

A plugin for Rocket League that fixes FOV going crazy in replays.

### [Download](https://github.com/akuvfx/FixReplayFov/releases/download/0.1.0/FixReplayFovPlugin.dll)

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
