---
layout: page
show_title: false
banner:
  collection: liturgical
  pid: beinecke1184
  y: 25%
---

Liturgy may be defined as the practice of organized, formal worship. It is the ensemble of texts, music (books and instruments), movements, vestments, vessels, and even the buildings and the interaction of all of these used by a group of people to worship God. Liturgy encompasses two main types of service: the Mass and the Divine Office. But a definition of liturgy as public worship also includes group practices such as processions in conjunction with a Mass or an Office, and the chapter meetings associated with the Divine Office of the religious orders.

Western liturgical practice varied tremendously across time, from place to place, and in many specific communities. Manuscripts from the ninth century reveal efforts towards a pan-European unified liturgy initiated under the impetus of the Frankish emperor, Charlemagne, based primarily on Roman practices but with Gallican influence.

In a proclamation that Charlemagne issued in the year 789, he ordered that monasteries and cathedrals should all have well corrected copies of the psalms, the "notes" (perhaps the shorthand system for texts, or perhaps the musical notation itself), the chants, a computus, and a grammar. He added that young boys should not be allowed to copy gospel books, psalters, or missals, but only mature men should do so, whose greater knowledge---including, presumably, that of Latin itself---would preclude profusion of errors in the manuscripts.

Nevertheless, surviving liturgical manuscripts evince the multiplicity of practices of the later Middle Ages. The significant development at this point was a form of the liturgy that arose in the papal chapel in Rome during the twelfth century and that was carried to all parts of the western world by the Franciscans during the thirteenth century and by the printing press from the mid-1400s onwards. This form, termed the Roman rite, has a much broader compass than the city of Rome alone. Major dioceses, however, had their own rites. The liturgy in monasteries continued to differ from the use of secular churches, and was also geographically varied. With the pressures of the Reformation and Counter-Reformation, and aided by the printing press, the Council of Trent (1545-63) imposed a normative liturgy on most Catholics. It remained essentially in place until the Second Vatican Council (1962-65).

<!-- Note: On the following pages, all manuscript citations are understood to be held by Columbia University, Rare Book and Manuscript Library. -->

---

## Browse Exhibits

<ul>
	{% for item in site.exhibits %}
		{% if item.layout == "exhibit" %}
		<li><a href="{{ site.baseurl }}{{ item.permalink }}">{{ item.title }}</a></li>
		{% endif %}
	{% endfor %}
</ul>

---

## Browse Images

{% include collection_gallery.html collection="liturgical" facet_by="tag" %}

---

## Learn More

<ul>
	{% for item in site.exhibits %}
		{% if item.layout != "exhibit" and item.title != "Browse..." %}
		<li><a href="{{ site.baseurl }}{{ item.permalink }}">{{ item.title }}</a></li>
		{% endif %}
	{% endfor %}
</ul>
