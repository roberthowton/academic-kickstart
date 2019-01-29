+++
# Custom widget.
# An example of using the custom widget to create your own homepage section.
# To create more sections, duplicate this file and edit the values below as desired.
widget = "projects"
active = true
date = 2016-04-20T00:00:00

# Note: a full width section format can be enabled by commenting out the `title` and `subtitle` with a `#`.
title = "Teaching"
subtitle = ""

# Order that this section will appear in.
weight = 60

# Content.
# Display content from the following folder.
# For example, `folder = "project"` displays content from `content/project/`.
folder = "teaching"

# View.
# Customize how projects are displayed.
# Legend: 0 = list, 1 = cards, 2 = showcase.
view = 2

# Widget layout
# Legend: 0 = two columns (default), 1 = single column
widget_layout = 0

# For Showcase view, flip alternate rows?
flip_alt_rows = true

# Filter toolbar.

# Default filter index (e.g. 0 corresponds to the first `[[filter]]` instance below).
filter_default = 0

# Add or remove as many filters (`[[filter]]` instances) as you like.
# To show all items, set `tag` to "*".
# To filter by a specific tag, set `tag` to an existing tag name.
# To remove toolbar, delete/comment all instances of `[[filter]]` below.

[[filter]]
  name = "Current Courses"
  tag = "Current Courses"

[[filter]]
  name = "Past Courses"
  tag = "Past Courses"

[[filter]]
  name = "All"
  tag = "*"

+++
