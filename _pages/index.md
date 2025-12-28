---
defaults:
  # _pages
  - scope:
      path: ""
      type: pages
    values:
      layout: single
      author_profile: true
title: Engineering Portfolio
permalink: /

feature_row_projects:
  - image_path: /assets/images/first/9128_2025.jpg
    title: "REEFSCAPE - 2025 FRC"
    excerpt: "The 2025 FRC Season, during which I competed with team 9128 ITKAN Robotics."
    url: "/first/reefscape/"
    btn_label: "Read More"
    btn_class: "btn--info"

  - image_path: /assets/images/PLTW/homepage/elevatorIso.png
    title: "Machine Control Project"
    excerpt: "I worked with my team to CAD and program a full elevator prototype using feedback control systems."
    url: "/pltw-engineering/machine-control/"
    btn_label: "Read More"
    btn_class: "btn--warning"

  - image_path: /assets/images/PLTW/homepage/motorCarIso.png
    alt: "image of motor car"
    title: "Motor Car"
    excerpt: "I worked with a partner to create a unique three-wheel solution to create a reliable motor car, while looking stylish at the same time!"
    url: "/pltw-engineering/motor-car/"
    btn_label: "Read More"
    btn_class: "btn--warning"
---
<section class="hero">
  <div class="overlay"></div>
  <div class="hero-content">
    <h1 style="text-size: 100px;">Abdullah Khaled</h1>
    <p>Engineering Portfolio</p>
  </div>
</section>
<br>
---
<i>Passionate about combining my skills in design, software, and electronics to create cool robots that do cool things.</i>
{: .text-center}
---
<h2>Quick Links</h2>
{: .text-left}
[Browse Projects](/featured/){: .btn .btn--warning .btn--x-large}
[Download Resume](/resume/){: .btn .btn--primary .btn--x-large}
[GitHub](https://github.com/akhaled247){: .btn .btn--purple .btn--x-large}
{: .text-center}
---
<h2>Background</h2>
I am currently a junior at Wakeland High School in Frisco, TX, and have been working with robots since I was in kindergarten when I participated in a local LEGO BattleBots using EV3s. While I don't play with LEGOs as much as I used to (though I still find myself drawn to them at times), I now indulge in big LEGOs—actual robots made using real-world manufacturing and assembly techniques.
Through my background in engineering both through academic courses and extracurricular activites, I have developed my skills in design, software, and electronics to become a (hopefully) well-rounded student. For more information about me, see my [about me](/about/) or my [resume](/resume/)!

---
<h2>Featured Projects</h2>
{% include feature_row id="feature_row_projects"%}