---
title: 'Solutions'
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

<script>
function openTab(evt, tabName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }
  document.getElementById(tabName).style.display = "block";
  evt.currentTarget.className += " active";
}
</script>

# By Department

<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'Utilities')">Utilities</button>
  <button class="tablinks" onclick="openTab(event, 'Courts')">Courts</button>
  <button class="tablinks" onclick="openTab(event, 'Taxes')">Taxes</button>
  <button class="tablinks" onclick="openTab(event, 'Transportation')">Transportation</button>
  <button class="tablinks" onclick="openTab(event, 'Parking')">Parking</button>
  <button class="tablinks" onclick="openTab(event, 'Public Works')">Public Works</button>
  <button class="tablinks" onclick="openTab(event, 'Finance')">Finance/Payroll</button>
  <button class="tablinks" onclick="openTab(event, 'Permits')">Permits</button>
</div>

<div id="Utilities" class="tabcontent">
    <div class='row'> <!-- JACK -->
        <div class='colimg'>
            <img src='/images/products/paymentkiosk.webp' width="50%" loading="lazy" class='smallimg'>
        </div>
        <div class='coltext'>
            <br>
            <h4>JACK (Payment Kiosk)</h4>
            <p>
                Our bilingual, self-service payment kiosk works around the clock, providing residents with an easy solution to make contactless, in-person bill payments using cash, check or credit card.
                <br>
                <a href="/contact/">Learn more</a>
            </p>
        </div>
    </div>
    <div class='row'> <!-- Utility Express -->
        <div class='colimg'>
            <img src='/images/products/utilityexpress.webp' width="45%" loading="lazy" class='smallimg'>
        </div>
        <div class='coltext'>
            <br>
            <h4>Utility/Tax Express</h4>
            <p>
                Using their smartphones, residents can quickly and easily pay their utility bills or taxes. Recurring SMS reminders will ensure your residents don’t unintentionally miss a payment due date, leading to fewer defaults. This will help you increase collections as well as boost public confidence and trust in your services.
                <br>
                <a href="/contact/">Learn more</a>
            </p>
        </div>
    </div>
    <div class='row'> <!-- Online Payments -->
        <div class='colimg'>
            <img src='/images/products/onlinepayment.webp' width="45%" loading="lazy" class='smallimg'>
        </div>
        <div class='coltext'>
            <br>
            <h4>Online Payments</h4>
            <p>
                We create secure web and mobile payment solutions to help you ensure seamless revenue collection and provide your residents with a user-friendly and convenient payment experience.
                <br>
                <a href="/contact/">Learn more</a>
            </p>
        </div>
    </div>
    <div class='row'> <!-- IVR -->
        <div class='colimg'>
            <img src='/images/products/ivr.webp' width="45%" loading="lazy" class='smallimg'>
        </div>
        <div class='coltext'>
            <br>
            <h4>Pay by Phone (IVR)</h4>
            <p>
                Our Interactive Voice Response (IVR) technology allows you to provide residents with the option to make secure credit card or check payments over the phone using automated, bilingual voice assistance.
                <br>
                <a href="/contact/">Learn more</a>
            </p>
        </div>
    </div>
    <div class='row'> <!-- Point of Sale -->
        <div class='colimg'>
            <img src='/images/products/pos.webp' width="45%" loading="lazy" class='smallimg'>
        </div>
        <div class='coltext'>
            <br>
            <h4>Point-of-Sale System (POS)</h4>
            <p>
                Using our point-of-sale payment system, you can facilitate quick and efficient in-person payments of utility bills, citations and taxes. Our point-of-sale system is easy to use and comes with a receipt printer, barcode scanner and credit card reader.
                <br>
                <a href="/contact/">Learn more</a>
            </p>
        </div>
    </div>
    <div class='row'> <!-- Gov On Track -->
        <div class='colimg'>
            <img src='/images/products/got.webp' width="45%" loading="lazy" class='smallimg'>
        </div>
        <div class='coltext'>
            <br>
            <h4>GovOnTrack (ERP Software)</h4>
            <p>
                Use GovOnTrack to streamline your billing process and monitor collections. Our applications help you automatically generate statements for utilities and taxes that reflect residents’ payment history, account balance, and other details, helping you save time by eliminating the need to manually create these bills. GovOnTrack also helps you track and manage revenue collection, including property taxes.
                <br>
                <a href="/contact/">Learn more</a>
            </p>
        </div>
    </div>
    <div class='row'> <!-- Electronic Forms -->
        <div class='colimg'>
            <img src='/images/products/dice.webp' width="45%" loading="lazy" class='smallimg'>
        </div>
        <div class='coltext'>
            <br>
            <h4>Electronic Document Exchange</h4>
            <p>
                e-Documents provide a convenient alternative to printing and mailing paperwork for utilities, courts, taxes, and permits. Also accepts digital signatures from a smartphone, tablet, or computer.
                <br>
                <a href="/contact/">Learn more</a>
            </p>
        </div>
    </div>
</div>

<div id="Courts" class="tabcontent">
    <div class='row'> <!-- Citation Smart -->
        <div class='colimg'>
            <img src='/images/products/cs.webp' width="50%" loading="lazy" class='smallimg'>
        </div>
        <div class='coltext'>
            <br>
            <h4>Citation Smart</h4>
            <p>
                With Citation Smart, courts can send reminders via text message to defendants with active citations and facilitate payments. This easy-to-use interactive application is a cost-effective and convenient solution that allows courts to better serve citizens, build trust, and reduce defaults.
                <br>
                <a href="/contact/">Learn more</a>
            </p>
        </div>
    </div>
    <div class='row'> <!-- Online Dispute Resolution -->
        <div class='colimg'>
            <img src='/images/products/odr.webp' width="50%" loading="lazy" class='smallimg'>
        </div>
        <div class='coltext'>
            <br>
            <h4>Online Dispute Resolution</h4>
            <p>
                Our Online Dispute Resolution (ODR) module is a customizable, web-based case or citation resolution system designed for municipal courts. Through this mobile-enabled technology, courts can provide defendants with options to pay a citation, sign up for a driver’s safety course, submit a request for deferred disposition, request a dismissal, or a pre-trial -- all through a single, convenient, user-friendly platform.
                <br>
                <a href="/contact/">Learn more</a>
            </p>
        </div>
    </div>
    <div class='row'> <!-- Remote Magistration -->
        <div class='colimg'>
            <img src='/images/products/cotg.webp' width="50%" loading="lazy" class='smallimg'>
        </div>
        <div class='coltext'>
            <br>
            <h4>Remote Magistration</h4>
            <p>
                Courts On The Go is an intuitive technology that enables courts to set up virtual hearings and facilitate online dispute resolution. This platform allows courts to modernize services to streamline workflow and make courtrooms more accessible to citizens, helping them resolve legal issues quickly and avoid defaults.
                <br>
                <a href="/contact/">Learn more</a>
            </p>
        </div>
    </div>
    <div class='row'> <!-- Electronic Forms -->
        <div class='colimg'>
            <img src='/images/products/dice.webp' width="45%" loading="lazy" class='smallimg'>
        </div>
        <div class='coltext'>
            <br>
            <h4>Electronic Document Exchange</h4>
            <p>
                e-Documents provide a convenient alternative to printing and mailing paperwork for utilities, courts, taxes, and permits. Also accepts digital signatures from a smartphone, tablet, or computer.
                <br>
                <a href="/contact/">Learn more</a>
            </p>
        </div>
    </div>
    <div class='row'> <!-- JACK -->
        <div class='colimg'>
            <img src='/images/products/paymentkiosk.webp' width="50%" loading="lazy" class='smallimg'>
        </div>
        <div class='coltext'>
            <br>
            <h4>JACK (Payment Kiosk)</h4>
            <p>
                Our bilingual, self-service payment kiosk works around the clock, providing residents with an easy solution to make contactless, in-person bill payments using cash, check or credit card.
                <br>
                <a href="/contact/">Learn more</a>
            </p>
        </div>
    </div>
    <div class='row'> <!-- Online Payments -->
        <div class='colimg'>
            <img src='/images/products/onlinepayment.webp' width="45%" loading="lazy" class='smallimg'>
        </div>
        <div class='coltext'>
            <br>
            <h4>Online Payments</h4>
            <p>
                We create secure web and mobile payment solutions to help you ensure seamless revenue collection and provide your residents with a user-friendly and convenient payment experience.
                <br>
                <a href="/contact/">Learn more</a>
            </p>
        </div>
    </div>
    <div class='row'> <!-- IVR -->
        <div class='colimg'>
            <img src='/images/products/ivr.webp' width="45%" loading="lazy" class='smallimg'>
        </div>
        <div class='coltext'>
            <br>
            <h4>Pay by Phone (IVR)</h4>
            <p>
                Our Interactive Voice Response (IVR) technology allows you to provide residents with the option to make secure credit card or check payments over the phone using automated, bilingual voice assistance.
                <br>
                <a href="/contact/">Learn more</a>
            </p>
        </div>
    </div>
</div>

<div id="Taxes" class="tabcontent">
    <div class='row'> <!-- Gov On Track -->
        <div class='colimg'>
            <img src='/images/products/got.webp' width="45%" loading="lazy" class='smallimg'>
        </div>
        <div class='coltext'>
            <br>
            <h4>GovOnTrack (ERP Software)</h4>
            <p>
                Use GovOnTrack to streamline your billing process and monitor collections. Our applications help you automatically generate statements for utilities and taxes that reflect residents’ payment history, account balance, and other details, helping you save time by eliminating the need to manually create these bills. GovOnTrack also helps you track and manage revenue collection, including property taxes.
                <br>
                <a href="/contact/">Learn more</a>
            </p>
        </div>
    </div>
    <div class='row'> <!-- Tax Express -->
        <div class='colimg'>
            <img src='/images/products/utilityexpress.webp' width="45%" loading="lazy" class='smallimg'>
        </div>
        <div class='coltext'>
            <br>
            <h4>Utility/Tax Express</h4>
            <p>
                Using their smartphones, residents can quickly and easily pay their utility bills or taxes. Recurring SMS reminders will ensure your residents don’t unintentionally miss a payment due date, leading to fewer defaults. This will help you increase collections as well as boost public confidence and trust in your services.
                <br>
                <a href="/contact/">Learn more</a>
            </p>
        </div>
    </div>
    <div class='row'> <!-- JACK -->
        <div class='colimg'>
            <img src='/images/products/paymentkiosk.webp' width="50%" loading="lazy" class='smallimg'>
        </div>
        <div class='coltext'>
            <br>
            <h4>JACK (Payment Kiosk)</h4>
            <p>
                Our bilingual, self-service payment kiosk works around the clock, providing residents with an easy solution to make contactless, in-person bill payments using cash, check or credit card.
                <br>
                <a href="/contact/">Learn more</a>
            </p>
        </div>
    </div>
    <div class='row'> <!-- Online Payments -->
        <div class='colimg'>
            <img src='/images/products/onlinepayment.webp' width="45%" loading="lazy" class='smallimg'>
        </div>
        <div class='coltext'>
            <br>
            <h4>Online Payments</h4>
            <p>
                We create secure web and mobile payment solutions to help you ensure seamless revenue collection and provide your residents with a user-friendly and convenient payment experience.
                <br>
                <a href="/contact/">Learn more</a>
            </p>
        </div>
    </div>
    <div class='row'> <!-- IVR -->
        <div class='colimg'>
            <img src='/images/products/ivr.webp' width="45%" loading="lazy" class='smallimg'>
        </div>
        <div class='coltext'>
            <br>
            <h4>Pay by Phone (IVR)</h4>
            <p>
                Our Interactive Voice Response (IVR) technology allows you to provide residents with the option to make secure credit card or check payments over the phone using automated, bilingual voice assistance.
                <br>
                <a href="/contact/">Learn more</a>
            </p>
        </div>
    </div>
    <div class='row'> <!-- Point of Sale -->
        <div class='colimg'>
            <img src='/images/products/pos.webp' width="45%" loading="lazy" class='smallimg'>
        </div>
        <div class='coltext'>
            <br>
            <h4>Point-of-Sale System (POS)</h4>
            <p>
                Using our point-of-sale payment system, you can facilitate quick and efficient in-person payments of utility bills, citations and taxes. Our point-of-sale system is easy to use and comes with a receipt printer, barcode scanner and credit card reader.
                <br>
                <a href="/contact/">Learn more</a>
            </p>
        </div>
    </div>
    <div class='row'> <!-- Electronic Forms -->
        <div class='colimg'>
            <img src='/images/products/dice.webp' width="45%" loading="lazy" class='smallimg'>
        </div>
        <div class='coltext'>
            <br>
            <h4>Electronic Document Exchange</h4>
            <p>
                e-Documents provide a convenient alternative to printing and mailing paperwork for utilities, courts, taxes, and permits. Also accepts digital signatures from a smartphone, tablet, or computer.
                <br>
                <a href="/contact/">Learn more</a>
            </p>
        </div>
    </div>
</div>

<div id="Transportation" class="tabcontent">
    <div class='row'> <!-- GTAMS -->
        <div class='colimg'>
            <img src='/images/products/gtams.webp' width="45%" loading="lazy" class='smallimg'>
        </div>
        <div class='coltext'>
            <br>
            <h4>Ground Transportation Accounting Management System</h4>
            <p>
                GTAMS is an intuitive financial management system designed to provide airports with a reliable solution to oversee ground transportation fee payments and accounts. We offer GTAMS with a Commercial Vehicle Management System (CVMS), providing a comprehensive software suite to manage ground transport.
                <br>
                <a href="/contact/">Learn more</a>
            </p>
        </div>
    </div>
    <div class='row'> <!-- Balance Express -->
        <div class='colimg'>
            <img src='/images/products/balanceexpress.webp' width="45%" loading="lazy" class='smallimg'>
        </div>
        <div class='coltext'>
            <br>
            <h4>Balance Express</h4>
            <p>
                Balance Express is an intuitive system that sends out periodic reminders via text message to ground transportation operators, such as taxicabs, to ensure they maintain sufficient prepay account balance.
                <br>
                <a href="/contact/">Learn more</a>
            </p>
        </div>
    </div>
    <div class='row'> <!-- JACK -->
        <div class='colimg'>
            <img src='/images/products/paymentkiosk.webp' width="50%" loading="lazy" class='smallimg'>
        </div>
        <div class='coltext'>
            <br>
            <h4>JACK (Payment Kiosk)</h4>
            <p>
                Our bilingual, self-service payment kiosk works around the clock, providing taxicabs, shuttle buses, and other commercial vehicles with an easy solution to make contactless, in-person bill payments using cash, check or credit card.
                <br>
                <a href="/contact/">Learn more</a>
            </p>
        </div>
    </div>
    <div class='row'> <!-- Online Payments -->
        <div class='colimg'>
            <img src='/images/products/onlinepayment.webp' width="45%" loading="lazy" class='smallimg'>
        </div>
        <div class='coltext'>
            <br>
            <h4>Online Payments</h4>
            <p>
                We create secure web and mobile payment solutions to help you ensure seamless payments from transportation providers with a user-friendly payment experience.
                <br>
                <a href="/contact/">Learn more</a>
            </p>
        </div>
    </div>
    <div class='row'> <!-- IVR -->
        <div class='colimg'>
            <img src='/images/products/ivr.webp' width="45%" loading="lazy" class='smallimg'>
        </div>
        <div class='coltext'>
            <br>
            <h4>Pay by Phone (IVR)</h4>
            <p>
                Our Interactive Voice Response (IVR) technology allows you to provide drivers with the option to make secure credit card or check payments over the phone using automated, bilingual voice assistance.
                <br>
                <a href="/contact/">Learn more</a>
            </p>
        </div>
    </div>
    <div class='row'> <!-- Electronic Forms -->
        <div class='colimg'>
            <img src='/images/products/dice.webp' width="45%" loading="lazy" class='smallimg'>
        </div>
        <div class='coltext'>
            <br>
            <h4>Electronic Document Exchange</h4>
            <p>
                e-Documents provide a convenient alternative to printing and mailing paperwork for transportation permits. Also accepts digital signatures from a smartphone, tablet, or computer.
                <br>
                <a href="/contact/">Learn more</a>
            </p>
        </div>
    </div>
</div>

<div id="Parking" class="tabcontent">
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
</div>

<div id="Public Works" class="tabcontent">
    <div class='row'> <!-- GovOnTrack -->
        <div class='colimg'>
            <img src='/images/products/got.webp' width="45%" loading="lazy" class='smallimg'>
        </div>
        <div class='coltext'>
            <br>
            <h4>GovOnTrack</h4>
            <p>
                With GovOnTrack, you can efficiently track service requests and work orders. Our user-friendly and efficient cloud-based software helps you smoothly manage work order transactions for labor, materials and services, and monitor projects.
                <br>
                <a href="/contact/">Learn more</a>
            </p>
        </div>
    </div>
    <div class='row'> <!-- DICE -->
        <div class='colimg'>
            <img src='/images/products/parkingpayment.webp' width="45%" loading="lazy" class='smallimg'>
        </div>
        <div class='coltext'>
            <br>
            <h4>Electronic Document Exchange</h4>
            <p>
                Through our Digital Interaction and Citizen Engagement (DICE) platform, you can use e-forms for work orders that can be electronically shared with vendors and stakeholders to facilitate efficient communication and faster turnaround time.
                <br>
                <a href="/contact/">Learn more</a>
            </p>
        </div>
    </div>
</div>

<div id="Finance" class="tabcontent">
    <div class='row'> <!-- GovOnTrack -->
        <div class='colimg'>
            <img src='/images/products/got.webp' width="45%" loading="lazy" class='smallimg'>
        </div>
        <div class='coltext'>
            <br>
            <h4>GovOnTrack</h4>
            <p>
                With GovOnTrack, you get easy-to-use cloud-based software applications that provide real-time data to enable confident decision-making and automate aspects of budgeting, accounting, procurement and payroll to enhance efficiency.
                <br>
                <a href="/contact/">Learn more</a>
            </p>
        </div>
    </div>
</div>

<div id="Permits" class="tabcontent">
    <div class='row'> <!-- GovOnTrack -->
        <div class='colimg'>
            <img src='/images/products/got.webp' width="45%" loading="lazy" class='smallimg'>
        </div>
        <div class='coltext'>
            <br>
            <h4>GovOnTrack (ERP)</h4>
            <p>
                Using GovOnTrack’s cloud-based services, you can track and manage business licenses, animal licenses, building permits, and more, across different stages from application and approval to renewal. By reducing dependence on paper-based processes, you can ensure faster turnaround and better project management to improve efficiency and foster greater customer satisfaction.
                <br>
                <a href="/contact/">Learn more</a>
            </p>
        </div>
    </div>
    <div class='row'> <!-- DICE -->
        <div class='colimg'>
            <img src='/images/products/dice.webp' width="45%" loading="lazy" class='smallimg'>
        </div>
        <div class='coltext'>
            <br>
            <h4>Electronic Document Exchange</h4>
            <p>
                With our Digital Interaction and Citizen Engagement (DICE) platform, you can allow citizens applying for a permit or license to submit any required documents and forms electronically to facilitate better tracking of document submissions and quickly process applications.
                <br>
                <a href="/contact/">Learn more</a>
            </p>
        </div>
    </div>
    <div class='row'> <!-- Online Payments -->
        <div class='colimg'>
            <img src='/images/products/onlinepayment.webp' width="45%" loading="lazy" class='smallimg'>
        </div>
        <div class='coltext'>
            <br>
            <h4>Online Payments</h4>
            <p>
                With our web payment solutions, you can allow applicants to make online payments for permit and license fees for fast, secure processing.
                <br>
                <a href="/contact/">Learn more</a>
            </p>
        </div>
    </div>
</div>




# By Product

<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'jack')">JACK (Kiosks)</button>
  <button class="tablinks" onclick="openTab(event, 'got')">GovOnTrack (ERP)</button>
  <button class="tablinks" onclick="openTab(event, 'odr')">Online Dispute Resolution</button>
  <button class="tablinks" onclick="openTab(event, 'remote')">Remote Magistration</button>
  <button class="tablinks" onclick="openTab(event, 'sms')">SMS Alerts</button>
  <button class="tablinks" onclick="openTab(event, 'totg')">Mobile Ticketing</button>
  <button class="tablinks" onclick="openTab(event, 'acct')">Account Management</button>
  <button class="tablinks" onclick="openTab(event, 'docexch')">Document Exchange</button>
</div>

<div id="jack" class="tabcontent" style="padding-left:30px; padding-bottom:30px;">
    <h1>Justified Automated Cashiering Kiosk (JACK)</h1>
    <!-- <img src="https://i.imgur.com/FA7l0vF.jpg" width="40%" style="margin-left:100px; margin-right:100px; margin-bottom:40px; align:left;"/> -->
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
</div>

<div id="got" class="tabcontent" style="padding-left:30px; padding-bottom:30px;">
<a href="/contact/">Learn more</a>
</div>

<div id="odr" class="tabcontent" style="padding-left:30px; padding-bottom:30px;">
    <h1>Online Dispute Resolution</h1>
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
            <img src="https://i.imgur.com/mCHZXso.jpg" width="400px" class="center"/>
        </div>
    </div>
<a href="/contact/">Learn more</a>
</div>

<div id="remote" class="tabcontent" style="padding-left:30px; padding-bottom:30px;">
<a href="/contact/">Learn more</a>
</div>

<div id="sms" class="tabcontent" style="padding-left:30px; padding-bottom:30px;">
    <h1>SMS Alerts</h1>
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
        </ul></div>
        <div class="flex-child-1">
            <iframe width="560" loading="lazy" height="315" src="https://www.youtube.com/embed/_YeiBYrJLSI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" class="center" allowfullscreen></iframe>
        </div>
    </div>
<a href="/contact/">Learn more</a>
</div>

<div id="totg" class="tabcontent" style="padding-left:30px; padding-bottom:30px;">
    <h1>Mobile Ticketing</h1>
    <br>
    <h2>Offered by our partner company New In Blue</h2>
    <!-- <img src="https://i.imgur.com/y3T64Kc.png" class="center"> -->
    <h2>Features</h2>
    <div class="flexbox-container">
        <div class="flex-child">
        <ul class="roman"; style="list-style-type:disc">
            <li>eCitation smartphone app</li>
        </ul>
        <ul class="square"; style="list-style-type:circle">
                <li>Auto-populates citation form using data from DL scanner</li>
                <li>Issue both warnings and tickets from any smart device--Android or iOS phones and tablets</li>
                <li>Share tickets with violator using text, email, and print</li>
        </ul>
        <ul class="roman"; style="list-style-type:disc">
                <li>Issue physical tickets using bluetooth printer</li>
                <li>Data securely flows to the cloud in real time</li>
        </ul>
        </div>
        <div class="flex-child">
            <img src="https://i.imgur.com/aLbXwQI.png" width="400px" class="center"/>
        </div>
    </div>
    <h2>Benefits</h2>
    <div class="flexbox-container">
        <div class="flex-child">
        <ul class="roman"; style="list-style-type:disc">
                <li>50% faster than handwriting and ticket writers</li>
                <li>Costs a fraction of a dedicated ticket writer</li>
                <li>No expensive maintenance plans</li>
                <li>Built-in ID / registration scanner and photo caputre</li>
                <li>Less for the officer to worry about--don't need to deal with a computer, and DL/registration info auto-populates</li>
                <li>Enhance resident satisfaction through a quicker process</li>
                <li>Major saving = less grant writing for your department</li></ul>
        </div>
        <div class="flex-child">
            <img src="https://i.imgur.com/JNfUAru.png" width="400px" class="center"/>
        </div>
    </div>
<a href="/contact/">Learn more</a>
</div>

<div id="acct" class="tabcontent" style="padding-left:30px; padding-bottom:30px;">
    <h1>Account Management</h1>
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
            <img src="https://i.imgur.com/4rACbvh.png" width="400px" class="center"/>
        </div>
    </div>
<a href="/contact/">Learn more</a>
</div>

<div id="docexch" class="tabcontent" style="padding-left:30px; padding-bottom:30px;">
    <h1>Document Exchange</h1>
    <br>
    <h2>Digital Interaction for Citizen Engagement (DICE)</h2>
    <h2>Features</h2>
    <div class="flexbox-container">
        <div class="flex-child">
        <ul class="roman"; style="list-style-type:disc">
            <li>Digital forms and e-documents</li>
        </ul>
        <ul class="square"; style="list-style-type:circle">
                <li>Allows you to electronically share and receive information</li>
        </ul>
        <ul class="roman"; style="list-style-type:disc">
                <li>Electronic bills</li>
        </ul>
        <ul class="square"; style="list-style-type:circle">
            <li>Allow you to deliver bills to your residents over the internet</li>
        </ul>
        </div>
        <div class="flex-child">
            <img src="https://i.imgur.com/741yHTM.jpg" width="400px" class="center"/>
        </div>
    </div>
    <h2>Benefits</h2>
    <div class="flexbox-container">
        <div class="flex-child">
        <ul class="roman"; style="list-style-type:disc">
                <li>Cost-effective and eco-friendly</li>
        </ul>
        <ul class="square"; style="list-style-type:circle">
                <li>Reduces postage and other costs from physically printing and mailing documents</li>
                <li>Saves space and reduces storage considerations</li>
        </ul>
        <ul class="roman"; style="list-style-type:disc">
                <li>Convenient and intuitive</li>
        </ul>
        <ul class="square"; style="list-style-type:circle">
                <li>Easily sign and submit a digital document using a secure e-signature</li> 
                <li>View statement via a private, accessible e-bill and quickly make a payment</li>
        </ul>
        <ul class="roman"; style="list-style-type:disc">
                <li>Convenient and intuitive</li>
        </ul>
        <ul class="square"; style="list-style-type:circle">
                <li>Easily sign and submit digital document using secure e-signature</li> 
                <li>View statement via a private, accessible e-bill and quickly make a payment</li>
        </ul>
        <ul class="roman"; style="list-style-type:disc">
            <li>Quick and efficent</li>
        </ul>
        <ul class="square"; style="list-style-type:circle">
            <li>Using e-signatures, documents can be quickly shared and signed by multiple stakeholders</li>
            <li>Cloud-based technology helps centralize data across all departments</li>
        </ul>
        </div>
        <div class="flex-child">
            <img src="https://i.imgur.com/ufxbZSP.jpg" width="400px" class="center"/>
        </div>
    </div>
<a href="/contact/">Learn more</a>
</div>
