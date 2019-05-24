---
layout: exhibit
title: "A Complete Calendar"
editor: John Glasenapp
publish_date: 2018-11-15
permalink: /exhibits/complete/
---

The calendar reproduced here in its entirety is in a book devoted to computistical materials copied in England in the middle years of the 15th century; the calendar itself was probably copied ca. 1417. The codex contains the present calendar, charts of the eclipses of the sun and of the moon, Chaucer's Treatise on the Astrolabe, and a brief medicinal tract on humors of the body.

This calendar contains a large number of computistical columns, given the nature of its text; most liturgical calendars only have the columns numbered 7, 8, 10, 11, 12 below:

1. Beginning of dawn
2. Midnight
3. First Metonic cycle of conjunctions for the years 1387-1405 (left blank)
4. Second Metonic cycle of conjunctions for the years 1406-1424
5. Sunrise
6. Altitude of the sun at noon
7. Golden Numbers
8. Dominical Letters
9. Numbering of the days per month
10. Numbering of the days according to the calends, nones and ides
11. Names of the calends, nones and ides
12. Saints' feasts
13. Planetary hours
14. Third Metonic cycle of conjunctions for the years 1425-1443
15. Fourth Metonic cycle of conjunctions for the years 1444-1462
16. Midday
17. Beginning of dusk

For the full explanation of these columns, see Linne R. Mooney, *The Kalendarium of John Somer* (Athens GA, University of Georgia Press, 1998), pp. 38-41.

---

## Browse by Image

{% include collection_gallery.html collection="liturgical" facet_by="tag" only="A Complete Calendar" %}

---

## Browse by Label

{% for item in site.liturgical %}{% if item.tag == page.title %}
- [{{item.label | remove: 'New York, Columbia University, ' }}]({{site.baseurl}}{{item.permalink}})
{% else %}{% endif %}{% endfor %}