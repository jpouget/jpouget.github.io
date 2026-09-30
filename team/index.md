---
title: Team
nav:
order: 3
tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}

{% include list.html data="members" component="portrait" filter="role != 'pi'" %}


## Alumni

### Students

{% for person in site.data.alumni.students %}
**{{ person.name }}** — {{ person.current_position }}

{% endfor %}


{% include section.html background="images/background.jpg" dark=true %}
