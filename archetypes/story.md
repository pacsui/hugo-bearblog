+++
title = "{{ replace .Name "-" " " | title }}"
date = "{{ .Date }}"

#
# Collection/Trip name - for grouping stories together
# Example: "Summer Vacation 2024"
#
collection = ""

#
# Optional: Story order within the collection (lower numbers first)
#
order = 0

#
# Story media URL (MP4 or WebP)
# Example: https://bucket.r2.cloudflarestorage.com/story.mp4
#
mediaUrl = ""

#
# Media type: "video" or "image"
# Default is auto-detected from mediaUrl
#
mediaType = "video"

#
# Optional: Display caption/text overlay
#
caption = ""

#
# Optional: Duration in seconds (mainly for image display)
#
duration = 10

#
# Optional: Show progress bar at top
#
showProgress = true

#
# Optional: Allow user interaction
#
interactive = true

+++

Add story content here (optional, displayed below media).
