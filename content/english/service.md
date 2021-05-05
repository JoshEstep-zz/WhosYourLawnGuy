---
title: "Service"
description: "this is meta description"
bg_image: "images/feature-bg.jpg"
layout: "service"
draft: false

########################### about service #############################
about:
  enable : true
  title : "Whos Your Lawn Guy Does It All"
  content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptate soluta corporis odit, optio
          cum! Accusantium numquam ab, natus excepturi architecto earum ipsa aliquam, illum, omnis rerum, eveniet
          officia nihil. Eum quod iure nulla, soluta architecto distinctio. Nesciunt odio ullam expedita, neque fugit
          maiores sunt perferendis placeat autem animi, nihil quis suscipit quibusdam ut reiciendis doloribus natus nemo
          id quod illum aut culpa perspiciatis consequuntur tempore? Facilis nam vitae iure quisquam eius harum
          consequatur sapiente assumenda, officia voluptas quas numquam placeat, alias molestias nisi laudantium
          nesciunt perspiciatis suscipit hic voluptate corporis id distinctio earum. Dolor reprehenderit fuga dolore
          officia adipisci neque!"
  image : "images/weedeater.jpeg"


########################## featured service ############################
featured_service:
  enable : true
  service_item:
    # featured service item loop
    - name : "Lawn Striping"
      icon : "ion-erlenmeyer-flask"
      color : "primary"
      content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Saepe enim impedit repudiandae omnis est temporibus."
      
    # featured service item loop
    - name : "Precision Trimming"
      icon : "ion-leaf"
      color : "primary-dark"
      content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Saepe enim impedit repudiandae omnis est temporibus."
      
    # featured service item loop
    - name : "Clenaup Service"
      icon : "ion-lightbulb"
      color : "primary-darker"
      content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Saepe enim impedit repudiandae omnis est temporibus."

      
############################# Service ###############################
service:
  enable : true
  title : "Our Services"
  description : "Whos Your Lawn Guy! will go above and beyond to ensure your lawn is beautiful and well"
  service_item:
    # service item loop
    - icon : ion-coffee #ionicon pack v2 : https://ionicons.com/v2/
      name: Striping
      content: "All of our mowers are equipped with striping kits.  Striping kits push the grass in certain directions to give the appearance of stripes or diamonds in the lawn."

    # service item loop
    - icon : ion-compass #ionicon pack v2 : https://ionicons.com/v2/
      name: Edging
      content: "Creates a clean line that separates the lawn from driveways, sidewalks, and curbs."

    # service item loop
    - icon : ion-image #ionicon pack v2 : https://ionicons.com/v2/
      name: Trimming
      content: "Weed eating the lawn where the mower can’t reach or is unstable to ride on.  All the edges and around every structure, landscape, and pavement on the property."

    # service item loop
    - icon : ion-bug #ionicon pack v2 : https://ionicons.com/v2/
      name: Clean Up
      content: "Pick up of minimal trash and brush prior to mowing.  High velocity backpack blowers to put the cut blades of grass back into the lawn for natural fertilization and also blowing all pavement and porches."


      
############################# call to action #################################
cta:
  enable : true
  # call to action content comes from "_index.md"
---