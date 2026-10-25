# brycejamesmiller.com

Bryce James Miller's memorial site, rebuilt in October 2026 from the old Parallels Sitebuilder
pages on HostGator as plain HTML and CSS. There is no PHP and no build step, so nothing here
needs updating to keep working.

## Layout

- `index.html` - the memorial page
- `eagle.html` - Bryce the Bald Eagle: his visits, newest first
- `eagle/photos/` - photos for the eagle page, named by date (`2026-10-24-1.jpg`)
- `css/site.css` - all styling
- `images/` - Bryce's photo, the Horde emblem and the banner graphics from the original site

## Adding an eagle visit

1. Resize each photo to about 2000 px on the long side and strip its location data.
2. Save it in `eagle/photos/` as `YYYY-MM-DD-n.jpg`.
3. Copy the visit template in the comment at the top of `eagle.html`, fill it in, and put the
   new visit above the older ones.
