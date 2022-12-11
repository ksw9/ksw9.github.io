---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: undergrad"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: alumni"
%}
{:.center}

{%
  include figure.html
  image="images/action/brazil_team.jpg"
  caption="TB research meeting, Campo Grande, Brazil"
  link="team"
  width="400px"
%}

{% include section.html background="images/banner.jpg" dark=true%}

## Funding

Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html
  style="square"

  image1="images/photo.jpg"
  link1="https://uofuhealth.utah.edu/immunology-inflammation-infectious-diseases"
  tooltip1="University of Utah 3i Initiative"

  image2="https://www.niaid.nih.gov/themes/custom/niaid-drupal-theme/patternlab/src/images/global/niaid/logo-niaid.svg"
  link2="https://www.niaid.nih.gov/"
  tooltip2="NIH/NIAID"

  image3="images/photo.jpg"
  link3="https://nasa.gov/"
  tooltip3="Cool Initiative"

  image3="https://www.thrasherresearch.org/content/thrasher/bc/thrasher/images/thrasher-logo.png"
  link3="https://www.thrasherresearch.org/purpose-of-fund?lang=eng"
  tooltip3="Thrasher Research Fund"

%}
