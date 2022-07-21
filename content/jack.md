---
title: 'Payment Kiosks (JACK)'
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
            <li>Bilingual</li>
            <li>Self-service</li>
            <li>Available 24/7 - residents can pay their bills in-person on weekends, holidays, and late nights</li>
        </ul>
        <ul class="square"; style="list-style-type:circle">    
                <li>Customizable to the specific needs of your department/residents - can be installed indoors or outdoors, walk-up or drive-thru</li>
                <li>Can accept whichever forms of payment you like</li>
        </ul>
        <ul class="roman"; style="list-style-type:disc">
            <li>Quick payment posting and real-time reporting</li>
        </ul>
        <ul class="square"; style="list-style-type:circle">
                <li>Payments are immediately posted to your department to minimize revenue delays</li>
                <li>Real-time transaction reports</li>
        </ul>
        <ul class="roman"; style="list-style-type:disc">
            <li>Secure and monitored</li>
        </ul>
        <ul class="square"; style="list-style-type:circle">
                <li>Payments are encrypted and PCI compliant</li>
                <li>AdComp monitors all activity to solve technical or security issues</li>
                <li>Residents get digital or paper receipts after every transaction</li>
        </ul>
        <ul class="roman"; style="list-style-type:disc">
            <li>Takes multiple forms of payments:</li></ul>
        <ul class="square"; style="list-style-type:circle">
                <li>Contactless</li>
                <li>Cash</li>
                <li>Check</li>
                <li>Credit Card</li>
                <li>Debit Card</li>
        </ul>
    </div>
    <div class="flex-child-1">
        <img src="https://i.imgur.com/FA7l0vF.jpg" width="400px" style="margin-left: auto; margin-right: auto; display: block;">
    </div>
</div>
<a href="/contact/">Learn more</a>