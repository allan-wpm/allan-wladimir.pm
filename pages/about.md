---
layout: page
title: About me
permalink: /about/
weight: 1
---


<div class="row justify-content-center align-items-center p-4">
  <div class="col-lg-4 col-md-6 text-center mt-4">

    <!-- Fine Circle Responsive Image -->
    <div id="container" class="my-2">
      <div id="dummy"></div>
      <div id="element">
        <img src="{{ site.author.image }}" alt="{{ site.title }}" class="circle-image wow animated zoomIn" data-wow-delay=".1s">
      </div>
    </div>

    <p class="text-muted wow animated slideInUp" data-wow-delay=".15s">{{ site.description }}</p>

  </div>
</div>




# **About Me**

Hi I am **{{ site.author.name }}**

I am a transport researcher with extensive experience investigating a wide range of transport challenges across academia, government, and industry. My journey in the transport sector began in 2007 when I commenced my undergraduate studies in Logistics and Transportation at ESPOL Polytechnic School in Guayaquil, Ecuador. Since then, I have held a variety of transport-related roles, including delivery planner, transport analyst, transport policy advisor, and local transport expert.

Throughout my career, I have worked in both private and public sector organisations, holding several senior and managerial positions. These have included Director of Studies and Projects at the Ecuadorian Agency of Transit, Interim Manager at Metro de Quito, and Chief Executive Officer of Cercana Consulting. These roles provided valuable experience in transport planning, policy development, project management, and strategic decision making.

Between 2021 and 2026, I completed my doctoral research while contributing to teaching and learning at Cardiff University. During this period, I taught Sustainable Transport Policies and further strengthened my expertise in transport economics, policy evaluation, and transport planning. My research interests encompass transport demand, road pricing, sustainable mobility, equity in transport, and the economic evaluation of transport policies.

<div class="row">
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
</div>