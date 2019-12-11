# Retropie 3B

Working with: 
- Dancing Stage Euromix
- Dance Dance Revolution

# Retropie Dance Mat Config

| SELECT       | #########    | START         |
| -----------: | :----------: | :------------ |
| ✕ = Z / 6    | ↥ = 2 / up   | ○ = X / 7     |
| ↤ = 0 / left | #########    | ↦ = 3 / right |
| △ = S / 4    | ↧ = 1 / down | □ = A / 5     |

# Hotkeys

Hotkey enabled = `Select`

Once you've pressed the hotkey, then press: 
Exit = `Start`
Open RGUI Menu = `△`

# Controller config

File: `\\retropie\configs\all\retroarch-joypads`

```
input_device = "USB Gamepad "
input_driver = "udev"
input_start_btn = "9"
input_down_btn = "1"
input_right_btn = "3"
input_state_slot_increase_btn = "3"
input_select_btn = "8"
input_left_btn = "0"
input_state_slot_decrease_btn = "0"
input_up_btn = "2"
input_a_btn = "7"
input_b_btn = "6"
input_reset_btn = "6"
input_x_btn = "4"
input_y_btn = "5"
input_menu_toggle_btn = "4"
input_enable_hotkey_btn = "8"
input_exit_emulator_btn = "9"
```

# Recommended optimisations (I didn't need these)
From: https://www.reddit.com/r/RetroPie/comments/6s5io3/update_the_great_ddr_project_got_it_working/

```
# Settings made here will only override settings in the global retroarch.cfg if placed above the #include line

input_remapping_directory = "/opt/retropie/configs/psx/"

#video_shader_enable = false
#video_smooth = "false"
#video_max_swapchain_images = 2
#video_threaded = "false"
#video_vsync = false
#video_driver = "dispmanx"
#audio_latency = 45

#include "/opt/retropie/configs/all/retroarch.cfg"

```

# The Dancemat
Just a standard USB Dancemat off of ebay:
https://www.ebay.co.uk/itm/USB-Dancing-Mat-For-PC-Video-Games-Gaming-DDR-Dance-Pad-Revolution-Non-Slip/283679881801?ssPageName=STRK%3AMEBIDX%3AIT&_trksid=p2060353.m1438.l2649

- USB connector
- Came with a "Stepmania" CD ROM that you can chuck in the bin
