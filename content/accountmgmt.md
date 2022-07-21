---
title: 'Account Management'
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

<p>Our first account management product was developed for the Philadelphia Airport's ground transportation system. The product is adaptable to your specific use case.</p>
<div class="flexbox-container">
    <div class="flex-child">
<!-- <img src="https://i.imgur.com/4rACbvh.png" class="center"/> -->
<h2>Features</h2>
<ul class="roman" style="list-style-type:disc">
    <li>Account reports/tracking</li>
    <li>Users can add funds to their accounts at any time</li>
    <li>Kiosks can be added to accept payments in addition to web and mobile payments</li>
    <li>Prepay option: users are a set amount every month, week, etc.</li>
    <li>Instant postpay option:credit/debit card on file can be charged on a per-use basis</li>
    <li>Reconciliation between various entities and payment gateway</li>
    <li>Available real-time reports</li>
</ul>
<ul class="square" style="list-style-type:circle">
    <li>Payment transactions</li>
</ul>
<ul class="next" style="list-style-type:square">
    <li>Separable by payment form: cash, credit, checks</li>
    <li>Filter by sources: kiosk, POS, web, mobile</li>
</ul>
<ul class="square" style="list-style-type:circle">
    <li>Graphical representations</li>
    <li>Deposits</li>
    <li>Reconciliation</li>
    <li>General ledger</li>
    <li>Acount audits</li>
    <li>Device information</li>
</ul>
<h2>Benefits</h2>
<ul class="roman" style="list-style-type:disc">
    <li>User-friendly</li>
</ul>
<ul class="square" style="list-style-type:circle">
    <li>Presents info in accessible format</li>
    <li>Easily generate invoices and add/edit charges</li>
</ul>
<ul class="roman" style="list-style-type:disc">
    <li>Real-time transaction updates</li>
    <li>Integrated email- and text-based alerts </li>
</ul>
<ul class="square" style="list-style-type:circle">
    <li>Automatically send a range of alerts via email/text to inform users of upcoming payments, missing/expired credit cards on file, recurring charges, etc.</li>
</ul>
<ul class="roman" style="list-style-type:disc">
    <li>Security</li>
</ul>
<ul class="square" style="list-style-type:circle">
    <li>Advanced role-based user security</li>
    <li>Cloud-based storage by Amazon AWS</li>
    <li>All data is automatically backed up daily</li>
</ul>
    </div>
    <div class="flex-child-1">
        <img src="https://i.imgur.com/4rACbvh.png" loading="lazy" width="400px" class="center"/>
    </div>
</div>
<a href="/contact/">Learn more</a>