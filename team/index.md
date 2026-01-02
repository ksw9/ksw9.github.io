---
title: Team
nav:
  order: 4
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
  filters="role: postdoc"
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
  component="list"
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

  image1="images/3i.jpg"
  link1="https://uofuhealth.utah.edu/immunology-inflammation-infectious-diseases"
  tooltip1="University of Utah 3i Initiative"

  image2="https://www.niaid.nih.gov/themes/custom/niaid-drupal-theme/patternlab/src/images/global/niaid/logo-niaid.svg"
  link2="https://www.niaid.nih.gov/"
  tooltip2="NIH/NIAID"

  image3="https://wilkescenter.utah.edu/wp-content/uploads/sites/42/2023/07/The-Wilkes-Center-Logo_main-black-1536x424.png"
  link3="https://wilkescenter.utah.edu/"
  tooltip3="Wilkes Center for Climate Science & Policy"

%}
