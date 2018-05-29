# Default Options

All key bindings can be set according to [tkinter](http://effbot.org/tkinterbook/tkinter-events-and-bindings.htm).
Note that `next_image`, `prev_image`, `single_step_backward`, and `single_step_forward` are set with respect to manga mode.

### Example Configuration

```
double_page=True
height=1024
width=768
fullscreen_toggle=<f>
```

### All Options

| Name                 | Description                                                                                           |
| -----------------    | -------------------                                                                                   |
| double_page          | Sets double page mode (default `False`)                                                               |
| fit_mode             | Sets the fit mode to view images from best, height, and width (default `best`)                        |
| fullscreen           | Sets fullscreen (default `False`)                                                                     |
| height               | Sets window height (default `500`)                                                                    |
| manga_mode           | Sets the image scroll from right to left like a manga (default `True`)                                |
| jump_to_beginning    | Sets key for moving to the first image (default `<Home>`)                                           |
| jump_to_end          | Sets key for moving to the last image (default `<End>`)                                             |
| next_image           | Sets key for moving to the next image (default `<Left>`)                                            |
| prev_image           | Sets key for moving to the previous image (default `<Right>`)                                       |
| rotate               | Sets key for rotating image (default `<r>`)                                                         |
| rotation             | Sets image orientation as an integer multiple of 90 degrees from 0-3 (default `0`)                     |
| scale_method         | Sets image scaling method as nearest, bilinear, bicubic, or lanczos (default `lanczos`)              |
| set_best_fit         | Sets key to enable best fit mode (default `<b>`)                                                     |
| set_height_fit       | Sets key to enable height fit mode (default `<h>`)                                                   |
| set_width_fith       | Sets key to enable width fit mode (default `<w>`)                                                    |
| single_step_backward | Sets key to move exactly one page back regardless of double page mode (default `<Shift-Right>`)      |
| single_step_forward  | Sets key to move exactly one page forward regardless of double page mode (default `<Shift-Left>`)    |
| toggle_double_page   | Sets key for toggling double page mode (default `<d>`)                                               |
| toggle_fullscreen    | Sets key for toggling fullscreen (default `<F11>`)                                                  |
| toggle_manga_mode    | Sets key for toggling manga mode (default `<m>`)
| width                | Sets window width (default `500`)                                                                     |
