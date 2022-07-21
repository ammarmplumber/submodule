---
title: 'Remote Magistration'
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

<h2>Key Features</h2>
<div class="flexbox-container">
    <div class="flex-child">
        <ul class="roman" style="list-style-type:disc;">
            <li>Makes courtoom more accessible to all defendants, incuding those unable to attend for reasons beyond control</li>
            <li>Platform is for courts at every level -- state, county, municipal</li>
            <li>Defendants can enter driver's license, citation number, or personal information to endter waiting room</li>
            <li>Courts can electronically send and receive documents</li>
        </ul>
        <h2>Key Benefits</h2>
        <ul class="roman" style="list-style-type:disc">
            <li>Boost accessibility & compliance</li>    
        </ul>
        <ul class="square" style="list-style-type:circle">
            <li>Easier access to courtroom</li>
            <li>Reduces instances of FTA (failure to appear)</li>
        </ul>
        <ul class="roman" style="list-style-type:disc">
            <li>Seamless integration with court management software</li>
        </ul>
        <ul class="square" style="list-style-type:circle">
            <li>Assists with defendant engagement, coordinates delivery of electronic documents, and updates the case status</li>
        </ul>
        <ul class="roman" style="list-style-type:disc">
            <li>Secure technology</li>
        </ul>
    </div>
    <div class="flex=child-1">
        <img src="https://i.imgur.com/rhBvsDC.png?1" loading="lazy" width="400px" class="center">
    </div>
</div>
<a href="/contact/">Learn more</a>