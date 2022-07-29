---
title: 'SMS Notifications'
date: 2018-02-22T17:01:34+07:00
---

<style>
.roman {
    list-style-type: lower-roman;
}
.square {
    list-style-type: square;
    margin-left: 30px;
}    

.column {
    float: left;
    width: 50%;
}

.right {
    width: 50%;
}

.row:after {
    content: "";
    display: table;
    clear: both;
}

.benefits {
    text-align:left;
}

.flexbox-container {
    display: flex;
    align-items: flex-start;
    flex-wrap: wrap;
}

.flex-child {
    flex:1;
    border: 1px;
    min-width: 400px;
    max-width: 800px;
    padding-right: 30px;
}

.flex-child-1 {
    flex:2;
    border: 1px;
    padding-left: 20px;
    padding-right: 20px;
    flex-shrink: 0;
}

.center {
    margin-left: auto; 
    padding-right: 30px;
    margin-right: auto; 
    display: block;
}

@media screen and (max-width: 990px) {
    .flexbox-container {
        display: flex;
        flex-direction: column-reverse;
    }

    .flex-child {
        flex:1;
        border: 1px;
        min-width: 400px;
    }

    .flex-child-1 {
        flex:2;
        border: 1px;
        padding-left: 20px;
        padding-right: 20px;
        flex-shrink: 0;
    }
}
</style>

<div class="flexbox-container">
    <div class="flex-child">
        <!-- <img src="https://i.imgur.com/0gmWNtN.jpg" width="50%" style="margin-left:50px; margin-right:100px; margin-bottom:20px; align:left;"/> -->
    <h1>Benefits</h1>
    <ul style="list-style-type:disc">
    <li>Send residents periodic reminders via text message</li>
    <li>Facilitate payments for water bills, utility bills, and taxes</li>
    <li>Periodic reminders will ensure residents don't unintentionally miss a payment due date</li>
    <li>Increases collections and boosts public confidence in your services</li>
    <li>Can fully integrate with existing management software</li>
    </ul>
    <br>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/2nPEIOhOCmA" loading="lazy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    <div class="flex-child-1">
        <iframe width="560" loading="lazy" height="315" src="https://www.youtube.com/embed/_YeiBYrJLSI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" class="center" allowfullscreen></iframe>
    </div>
</div>
<br><br>
<a href="/contact/">Learn more</a>