---
title: Google Sheets 3
layout: post
author: felix.bradbury
permalink: /google-sheets-3/
source-id: 1ItV6JuGJrRdR-cMahsOdl8_SN24hV4EeZV3llLGHYdg
published: true
---
Today we worked on discount codes. So for example if the code contained AA it would be -10%. We used two separate codes to do this one was the left code so it chooses the left digits of a string for example =(left I7,2) would result in the 2 leftmost digits or letters in the I7 cell. The final line of coding we used was =if (I8="AA”, 10, if (I8= "AB”, 10, if (I8= “AC” 10, 0) this code would look at the left code and if the left code was AA, AB, AC it would give a discount accordingly else it would put the letter 0 for no discount. I just timesed the price by the discount to get how much was being discounted and then I minused that from the price to get the final price.  

