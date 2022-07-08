---
title: 'Parking'
date: 2018-02-22T17:01:34+07:00
---

<style>
/* Style the tab */
.tab {
  overflow: hidden;
  border: 1px solid #ccc;
  background-color: #f1f1f1;
  margin-right: 40px;
}

/* Style the buttons inside the tab */
.tab button {
  background-color: inherit;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  transition: 0.3s;
  font-size: 17px;
}

/* Change background color of buttons on hover */
.tab button:hover {
  background-color: #ddd;
}

/* Create an active/current tablink class */
.tab button.active {
  background-color: #ccc;
}

/* Style the tab content */
.tabcontent {
  display: none;
  margin-right: 40px;
  padding-left: 6px 12px;
  border: 1px solid #ccc;
  border-top: none;
  padding-left: 30px;
  padding-bottom: 40px;
}

.smallimg {
    display: block; 
    margin-left: auto; 
    margin-right: auto; 
    margin-top: auto; 
    margin-bottom: auto;
}

.row {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  width: 100%;
  margin: 20px;
}

.coltext {
  display: flex;
  flex-direction: column;
  flex-basis: 100%;
  flex: 2;
  padding-right: 40px;
}

.colimg {
  display: flex;
  flex-direction: column;
  flex-basis: 100%;
  flex: 1;
}
</style>

<div class='row'> <!-- Parking Kiosks -->
    <div class='colimg'>
        <img src='/images/products/parkingkiosk.webp' width="45%" loading="lazy" class='smallimg'>
    </div>
    <div class='coltext'>
        <br>
        <h4>Parking Kiosks</h4>
        <p>
            Using our kiosks, you can accept credit card or cash payments for parking fees or tickets, print and share thermal tickets with visitors, scan employee cards and adopt license plate recognition software to ensure a secure, convenient and safe parking experience for all employees and visitors.
            <br>
            <a href="/contact/">Learn more</a>
        </p>
    </div>
</div>
<div class='row'> <!-- Mobile Payments -->
    <div class='colimg'>
        <img src='/images/products/parkingpayment.webp' width="45%" loading="lazy" class='smallimg'>
    </div>
    <div class='coltext'>
        <br>
        <h4>Mobile Payments</h4>
        <p>
            Using their smartphone, visitors can send a text message with their license plate number to pay their parking fee and receive a virtual parking permit, providing them with a user-friendly and accessible payment option
            <br>
            <a href="/contact/">Learn more</a>
        </p>
    </div>
</div>