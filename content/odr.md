---
title: 'Online Dispute Resolution (ODR)'
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
    <ul class="roman"; style="list-style-type:disc">
        <li>Mobile-enabled technology</li>
        <li>Convenient solution to request a:</li>
    </ul>
    <ul class="square"; style="list-style-type:circle">
            <li>Deferred disposition</li>
            <li>Driver's safety course</li>
            <li>Payment plan to manage citations</li>
    </ul>
        <ul class="roman"; style="list-style-type:disc">
        <li>Courts can share options with citizens via text message
            to resolve citations</li>
        </ul>
    </div>
    <div class="flex-child">
        <img src="https://i.imgur.com/mCHZXso.jpg" loading="lazy" width="400px" class="center"/>
    </div>
</div>
<a href="/contact/">Learn more</a>