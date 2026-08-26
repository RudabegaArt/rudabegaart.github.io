---
title: "Selected Works"
permalink: /selected-works/
gallery:
  - url: "/assets/images/landscapes/[2026]buoy_pile.jpg"
    image_path: "/assets/images/landscapes/[2026]buoy_pile.jpg"
    alt: "Buoy Pile"
    title: "Buoy Pile <br> 
            18inx24in <br>
            2026"
  - url: "/assets/images/landscapes/[2026]schoodic_roil.jpg"
    image_path: "/assets/images/landscapes/[2026]schoodic_roil.jpg"
    alt: "Schoodic Roil"
    title: "Schoodic Roil <br> 
            20inx20in <br>
            2026"
  - url: "/assets/images/surreal/[2026]prison_guard.jpg"
    image_path: "/assets/images/surreal/[2026]prison_guard.jpg"
    alt: "Prison Guard"
    title: "Prison Guard <br> 
            36inx24in <br>
            2026"
  - url: "/assets/images/surreal/[2026]bigger_on_the_inside.jpeg"
    image_path: "/assets/images/surreal/[2026]bigger_on_the_inside.jpeg"
    alt: "Bigger on the Inside"
    title: "Bigger on the Inside <br> 
            10inx20in <br>
            2026"
  - url: "/assets/images/awlo/[2025]bery_at_home.jpeg"
    image_path: "/assets/images/awlo/[2025]bery_at_home.jpeg"
    alt: "Bery at Home"
    title: "Bery at Home <br> 
            30inx20in <br>
            2025"
  - url: "/assets/images/maine-moments/[2025]Fathers_Shed.jpg"
    image_path: "/assets/images/maine-moments/[2025]Fathers_Shed.jpg"
    alt: "Father's Shed"
    title: "Father's Shed <br>
            24inx18in <br>
            2025"
    

---
<div class="my-custom-400-gallery">
  {% include gallery %}
</div>

<!-- 2. Target ONLY the thumbnail images inside that specific container -->
<style>
  /* Fixes the layout spacing so thumbnails don't overlap */
  .my-custom-400-gallery {
    display: grid;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
  }

  /* Forces ONLY the thumbnail images into a 400x400 cropped square */
  .my-custom-400-gallery img {
    width: 300px !important;
    height: 300px !important;
    object-fit: contain !important;
    object-position: center !important;
  }
</style>

