# FSCSS Snake_case Properties
A comprehensive FSCSS library that enables writing CSS properties in snake_case notation (Python/Ruby style), automatically converting them to their standard kebab-case equivalents.
## Overview
This library provides a clean and readable way to write CSS in FSCSS using snake_case property names, making your styles more consistent with Python, Ruby, or database naming conventions. It includes support for over 500 CSS properties, covering everything from basic layout to modern CSS features.
## Features
 * 300+ CSS Properties – Comprehensive coverage of CSS properties.
 * Automatic Conversion – Seamless snake_case to kebab-case conversion.
 * Easy Integration – Simple import and usage.
 * Modern CSS Support – Includes Grid, Flexbox, Container Queries, and more.
 * Type-Safe – Works seamlessly with FSCSS's type system.
 * Readable – More natural for Python/Ruby developers.
## Installation
### Basic Import (FSCSS 1.1.16+)
```css
/* Import the snake_case converter*/
@import((snake_case) from snake_case))

/* Or import everything */
@import((*) from snake_case))
```
### Legacy Import (FSCSS system)
@import(exec(_init snake_case))

## Usage
### Basic Example
```css
@import((snake_case) from snake_case))

body {
  background_color: #f0f0f0;
  font_family: 'Arial', sans-serif;
  font_size: 16px;
  line_height: 1.5;
  margin: 0;
  padding: 20px;
}

.container {
  display: flex;
  flex_direction: column;
  justify_content: center;
  align_items: center;
  gap: 16px;
  border_radius: 8px;
  box_shadow: 0 2px 4px rgba(0,0,0,0.1);
}
```
### Advanced Example with Modern CSS
@import((snake_case) from snake_case))
```css
.card {
  /* Layout */
  display: grid;
  grid_template_columns: repeat(3, 1fr);
  gap: 24px;
  
  /* Spacing */
  padding: 20px;
  margin_bottom: 16px;
  
  /* Styling */
  background_color: white;
  border_radius: 12px;
  box_shadow: 0 4px 6px rgba(0,0,0,0.1);
  
  /* Typography */
  font_family: 'Inter', system-ui;
  font_size: 14px;
  font_weight: 500;
  line_height: 1.4;
  
  /* Animations */
  transition: all 0.3s ease;
  transition_property: transform, box_shadow;
  
  &:hover {
    transform: translateY(-4px);
    box_shadow: 0 8px 12px rgba(0,0,0,0.15);
  }
}
```
## Supported Properties
### Layout & Display
 * display, position
 * top, right, bottom, left
 * z_index, float, clear
 * visibility, opacity
### Flexbox
 * flex_direction, justify_content, align_items
 * flex_wrap, flex_grow, flex_shrink, flex_basis
 * order, gap, row_gap, column_gap
### Grid
 * grid_template_columns, grid_template_rows
 * grid_auto_columns, grid_auto_rows, grid_auto_flow
 * grid_gap, grid_row, grid_column
### Typography
 * color, font_family, font_size, font_weight
 * text_align, text_decoration, text_transform
 * letter_spacing, word_spacing, line_height
### Background & Borders
 * background_color, background_image, background_size
 * border, border_width, border_style, border_color
 * border_radius, box_shadow
---
## Complete Properties List

<details>
<summary>Click to view all supported properties (300+)</summary>

```
background_color
text_align
font_size
font_weight
line_height
margin_top
padding_left
border_width
border_radius
box_shadow
text_decoration
white_space
z_index
flex_direction
justify_content
align_items
grid_template_columns
column_gap
transition_property
animation_name
position
top
right
bottom
left
display
visibility
opacity
width
min_width
max_width
height
min_height
max_height
margin
margin_right
margin_bottom
margin_left
padding
padding_top
padding_right
padding_bottom
padding_left
border
border_top
border_right
border_bottom
border_left
border_color
border_style
background
background_image
background_size
background_repeat
background_position
color
font_family
font_style
font_variant
letter_spacing
word_spacing
text_transform
text_indent
overflow
overflow_x
overflow_y
cursor
pointer_events
user_select
flex_wrap
flex_grow
flex_shrink
flex_basis
align_content
align_self
order
grid_gap
grid_row
grid_column
grid_template_rows
grid_auto_flow
box_sizing
content
transform
transform_origin
transition
transition_duration
transition_timing_function
transition_delay
animation_duration
animation_timing_function
animation_delay
animation_iteration_count
animation_direction
animation_fill_mode
filter
backdrop_filter
mix_blend_mode
text_shadow
clip_path
mask_image
caret_color
scroll_behavior
scroll_snap_type
text_fill_color
object_fit
object_position
float
clear
list_style
list_style_type
list_style_position
list_style_image
table_layout
border_collapse
border_spacing
empty_cells
caption_side
vertical_align
direction
unicode_bidi
writing_mode
text_orientation
word_break
word_wrap
text_overflow
line_break
hyphens
quotes
counter_reset
counter_increment
resize
outline
outline_width
outline_style
outline_color
outline_offset
column_count
column_width
column_rule
column_rule_width
column_rule_style
column_rule_color
column_span
column_fill
perspective
perspective_origin
backface_visibility
transform_style
transform_box
animation_play_state
animation_timeline
scroll_margin
scroll_margin_top
scroll_margin_right
scroll_margin_bottom
scroll_margin_left
scroll_padding
scroll_padding_top
scroll_padding_right
scroll_padding_bottom
scroll_padding_left
scroll_snap_align
scroll_snap_stop
scrollbar_width
scrollbar_color
overscroll_behavior
overscroll_behavior_x
overscroll_behavior_y
isolation
break_before
break_after
break_inside
orphans
widows
fill
stroke
stroke_width
stroke_dasharray
stroke_dashoffset
stroke_linecap
stroke_linejoin
stroke_miterlimit
marker_start
marker_mid
marker_end
paint_order
vector_effect
shape_outside
shape_margin
shape_image_threshold
clip
all
initial
inherit
unset
revert
line_clamp
olverflow_scrolling
tap_highlight_color
text_size_adjust
touch_callout
user_drag
osx_font_smoothing
overflow_style
touch_action
border_top_left_radius
border_top_right_radius
border_bottom_right_radius
border_bottom_left_radius
border_top_color
border_right_color
border_bottom_color
border_left_color
border_top_width
border_right_width
border_bottom_width
border_left_width
border_top_style
border_right_style
border_bottom_style
border_left_style
background_clip
background_origin
background_attachment
gap
row_gap
grid_auto_columns
grid_auto_rows
justify_items
justify_self
inset
inset_block
inset_inline
margin_block
margin_inline
margin_block_start
margin_block_end
margin_inline_start
margin_inline_end
padding_block
padding_inline
padding_block_start
padding_block_end
padding_inline_start
padding_inline_end
border_block
border_inline
border_block_start
border_block_end
border_inline_start
border_inline_end
border_block_color
border_block_style
border_block_width
font_kerning
font_feature_settings
font_variation_settings
text_combine_upright
text_decoration_color
text_decoration_line
text_decoration_style
text_decoration_thickness
text_underline_offset
text_emphasis
text_emphasis_color
text_emphasis_style
translate
rotate
scale
transition_behavior
animation_composition
overflow_anchor
overflow_clip_margin
appearance
forced_color_adjust
color_scheme
contain
contain_intrinsic_size
contain_intrinsic_width
contain_intrinsic_height
container
container_name
container_type
view_transition_name
content_visibility
math_style
math_depth
aspect_ratio
mask
mask_type
mask_composite
mask_mode
mask_position
mask_repeat
mask_size
mask_clip
mask_origin
will_change
counter_set
page
page_break_before
page_break_after
page_break_inside
inset_block_start
inset_block_end
inset_inline_start
inset_inline_end
color_mix
```
</details>

---

## Comparison: CamelCase vs Snake_case
| CSS Property | CamelCase | Snake_case |
|---|---|---|
| background-color | backgroundColor | background_color |
| border-radius | borderRadius | border_radius |
| justify-content | justifyContent | justify_content |
| grid-template-columns | gridTemplateColumns | grid_template_columns |
| transition-property | transitionProperty | transition_property |
## Version Compatibility
 * FSCSS 1.1.20+ - Fully supported (recommended)
 * FSCSS 1.1.16+ - Supported
 * Earlier versions - Use legacy import syntax
---
## Contributing
Feel free to submit issues or pull requests to add more properties or improve the library.
## License
MIT
Made with ❤️ for the FSCSS community

