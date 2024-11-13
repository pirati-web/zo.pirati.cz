---
layout: default
title: Tým Zahraničního odboru Pirátské strany
description:  Tým Zahraničního odboru Pirátské strany
keywords: zahraniční odbor, piráti, pirátky, příznivci
---
<div class="row o-section-block ">
    <div class="medium-12 large-12 columns">
      
        <section class="o-section">
        
            <div class="o-section-inner">
              
                <main class="o-section-block">
                
                    <div class="c-BasicPage">
                        <div class="c-BasicPage-content">
 
                                  <a href="#garant" ><h3>VEDOUCÍ ZAHRANIČNÍHO ODBORU</h3></a>
                                    <div id="garant">
                                        {% assign team = site.people | where_exp:"item","item.categories contains 'garant'" | sort:"ordgarant" %}
                                        {% include people/list-2col.html param=team %}
                                    </div>

 


         
    </div>

</div>
