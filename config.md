### Common configs
```
rate 128000
cl_cmdrate 128
cl_updaterate 128
cl_interp 0
cl_interp_ratio 1
cl_lagcompensation 1

```


### Radar

```
cl_radar_always_centered 0
cl_radar_scale 0.3
cl_hud_radar_scale 1.15
cl_radar_icon_scale_min 1
cl_radar_rotate 1
```

### Crosshairs Settings

```
cl_crosshairsize 3
cl_crosshairgap -2
cl_crosshairdot 0
cl_crosshairthickness 1.15
cl_crosshaircolor 1
```

### alias

```
alias "+jumpthrow" "+jump;-attack"; alias "-jumpthrow" "-jump"; bind "v" "+jumpthrow"
```


### launch config
```
-silent -novid -nojoy -threads 4 -tickrate 128 -high -maxdownloadfilesizemb 500 +cl_forcepreload 1 +cl_showfps 1 +fps_max 0 -noforcemparms -noforcemacel -refresh 144 -freq 240
```
