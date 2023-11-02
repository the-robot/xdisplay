## xDisplay

### Usage

```bash
xdisplay -l (--list)                   # list displays
xdisplay -b (--brightness) DP-1 up     # increase brightness of DP-1 display
xdisplay -b (--brightness) DP-1 down   # increase brightness of DP-1 display
xdisplay -b (--brightness) DP-1 0.5    # set brightness of DP-1 display (min = 0.1, max 1.0)

# if you want to save default display for ease-of-use
xdisplay -s (--save-default) DP-1      # save DP-1 as default display
xdisplay up                            # increase default display brightness
xdisplay down                          # decrease default display brightness
xdisplay 0.5                           # set default display brightness
```
