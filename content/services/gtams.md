---
title: "Transit Account Management"
date: 2018-11-18T12:33:46+10:00
draft: false
featured: true
weight: 7
---

We offer a payment ecosystem for taxicabs, shuttles, and other commercial vehicles with flexible, easy-to-use solutions to pay ground transportation fees. Our first iteration was developed for the Philadelphia Airport's ground transportation system, and the product is adaptable to your specific use case.

## Ground Transportation Account Management System (GTAMS) Features

<div class="flexbox-container">
    <div class="flex-child">
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
        <ul class="roman" style="list-style-type:disc">
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
        <ul class="roman" style="list-style-type:disc">
            <li>Easily generate invoices and add/edit charges</li>
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
        <img src="https://i.imgur.com/4rACbvh.png" width="90%" loading="lazy" style="max-width: 300px; margin-left: auto; margin-right: auto; padding-right: 20px; display: block;">
    </div>
</div>



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
