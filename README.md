# TOP-project-admin-dashboard

## Lesson Link:
https://www.theodinproject.com/lessons/node-path-intermediate-html-and-css-admin-dashboard

## Live Preview:
https://suprasensum.github.io/TOP-project-admin-dashboard/

## GitHub Repo:
https://github.com/SupraSensum/TOP-project-admin-dashboard

## Struggles:
* Can't use clamp(200px, 1fr, 300px) for a grid track. Either my google-fu is very weak or there just isn't a straightforward way to implement something like this. Two spots I ran into this issue with were for the blue sidebar and for the column containing announcements and trending.
* For some reason, when I would increase the width of the buttons (new, upload, share), the flexbox container would overflow due to the grid cell not growing with it. Meanwhile, the login and notifications grid cell would grow as its contents grew, just as expected. I tested this by increasing the width of the login-name container. Do grid cells not count button widths?
* On a similar note as the bullet point above, I noticed row-gap would affect overflow behavior. I developed an awkward workaround by dividing the row-gap size by the number of rows, then subtracting that from each row's height. Need to learn more about this grid quirk. Or maybe it's to do with how overflow does its calculations?
