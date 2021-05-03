---
title: "Service"
description: "this is meta description"
bg_image: "images/WYLG.jpeg"
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
    - name : "Precision Weed Eating"
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
  description : "Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, <br> there live the
          blind texts. Separated they live in Bookmarksgrove right at the coast of the Semantics"
  service_item:
    # service item loop
    - icon : ion-coffee #ionicon pack v2 : https://ionicons.com/v2/
      name: Striping
      content: "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut"

    # service item loop
    - icon : ion-compass #ionicon pack v2 : https://ionicons.com/v2/
      name: Edging
      content: "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut"

    # service item loop
    - icon : ion-image #ionicon pack v2 : https://ionicons.com/v2/
      name: Weedeating
      content: "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut"

    # service item loop
    - icon : ion-bug #ionicon pack v2 : https://ionicons.com/v2/
      name: Clean Up
      content: "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut"


      
############################# call to action #################################
cta:
  enable : true
  # call to action content comes from "_index.md"
---