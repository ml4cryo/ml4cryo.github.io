<!-- About heading is already included -->

ML4Cryo is a place where the cryosphere community and the machine learning community come together. We are here to bridge gaps, support each other, and do science together.

To melt our communities together, we do the following:
- Maintain a Community Platform (Slack Space)
- Offer Announcement Options (Mailinglist & Re-tweeting)
- Organize Scientific Exchange (Workshops / Winter Schools)

The website you are on, is supposed to be the entry point, where you can choose how exactly you want to interact with the broader community :)

<!-- <br><br>
    ML4Cryo brings together experts from cryospheric disciplines, machine learning, and related fields to advance reserach in areas such as sea ice forecasting, ice sheet modelling, and other impactful yet challenging problems concerning the frozen parts of the Earth system, also known as <i>the croysphere</i>. ML4Cryo was founded in 2024 by PhD students Julia, Andrew, and Kim - together representing three different continents - to provide a platform for this growing community, to foster collaboration, and facilitate mutual support on shared scientific endeavors. 
    <i>'While ice expands as it freezes, the ML4Cryo community shall expand as it melts.'</i> -->

<!-- ## Vision & Mission
Our vision is to build a community in which machine learning and cryospheric are thought together.

## Values -->


<!-- - COP29
- NeurIPS workshop
- Grants for field work
- International Polar Year -->

<!-- ## Review paper

We are currently working on a review paper to capture the current state of machine learning applications to the cryospheric sciences. -->

## How can I interact with the ML-Cryo community?
We offer some facilitation to get in touch, with folks working on either side and anywhere in between.

### Slack Space
This is the right place for you, if you want to regularly interact with ML4Cryo people. 

You might be actively doing research at the intersection, or you are an ML person or Cryo person who needs ML support / domain expertise. If you are a professor or senior scientist and want to be up-to-date who is doing what in the community, this is also the right place. If you are not a researcher/scientists, but another stakeholder (e.g. users, applied folks, indigenous community, and more), and you want regular interactions, this is also the right place for you.

Forms of interactions:
Learning from each other, teach, inspire, support, exchange, share your work, joke around, find collaborators or co-workers, and more.

### Mailing List & Twitter
This is the right place for you, if you do not want to miss the most important developments.

Twitter might be the more regular, less filtered, and less consistent option.

The Mailing List is a form of community-lead newsletter. Once a month you will receive a collection of the most important news. Everyone who is part of the community can send requests of news items to be included.

This is the right place to hear about conference-sessions, workshops, and other events, as well as job announcements, highlighted papers and datasets and funding opportunities.

Form of interactions:
Listening, observing, receiving announcements. (Submitting announcements)

### Events
You can also participate in events to share your work and learn actively with others. Right now, we have a list of conference sessions, workshops, and summer schools collected on this website ("Events"). In the future, we want to offer a regular winter school where everyone can get together.

Form of interactions:
Actively learning, presenting your work, networking, having fun together.

### Become Part of our Team!
If you want to get more actively involved, we are happy to share tasks and responsibilities for the ML4Cryo platforms! 

Currently open positions (volunteering):
- Moderation committee
- Public Relations committee
- Finance committee
- EDI committee

If you are interested, please reach out to us at ml4cryo@gmail.com with a short description of who you are, and how you would like to contribute! 

Form of interactions:
Community engagement, sharing responsibility in community building, organizing, supporting, working together with fantastic human-beings ;D

## Team
ML4Cryo is a research community initiated by Julia Kaltenborn, Andrew McDonald, and Kim Bente. 

{% assign people = site.data.team | sample: site.data.team.size %}
{% for person in people %}
  {% assign side = forloop.index0 | modulo: 2 %}
    {% if side == 1 %}
      {% include team-card.html %}
    {% else %}
      {% include team-card.html %}
    {% endif %}
{% endfor %}