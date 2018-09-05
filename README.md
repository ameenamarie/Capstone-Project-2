# Predicting Default Borrowers for Lending Club

This repository contains all of the materials for my Capstone Project for Springboard's Data Science Bootcamp. 

***

## Background

Lending Club is an online peer-to-peer loan platform that allows individuals to take out personal loans of up to $40,000. Borrowers can easily apply for a loan online and will typically receive their money within a few days of submitting their application. Unlike a bank, the platform uses investors to fund loans and acts as the intermediary between investors and borrowers.

When an application is received and approved by Lending Club, it goes into their online platform. Investors can then select which loans to fund by either manually picking specific loans or having Lending Club automatically select a loan portfolio for them. As borrowers pay back their loans, investors receive monthly payments for the principal and interest on each loan. 

Occassionally a borrower does not pay back a loan in full and Lending Club must "Charge Off" the loan. This typically happens once a loan payment is at least 150 days past due, but can also occur earlier or later depending on the circumstances (i.e. a borrower files for bankruptcy). If a borrower charges off (AKA defaults) on their loan, there is limited recourse for an investor and the default will impact their return on investment. 

As an example Lending Club explains that a portfolio expecting to make 14% in annual interest, will have lose approximately 8% due to defaults. After accounting for Lending Club's 1% fee, an investor can expect to make 5% annually on their investments.

***

## Problem

As you can see from the example above, investors can lose over half of their potential earnings due to loan defaults. Is there a way to further maximize the return on investment for investors and decrease the amount of interest lost to loan defaults? 

In this paper I will be exploring that question as well as asking: 
* How much money does Lending Club lose to charged off loans? 
* Is it possible to help Lending Club predict the risk of a specific borrower failing to pay off their loan? 
* Can a model be built to minimize the risk to Lending Club investors and decrease the amount of money lost each year?

***

## The Data

To answer the questions posed I will be using Lending Club's __[dataset](https://www.lendingclub.com/info/download-data.action)__ that contains loan information from 2007-2011.

***

## Methods

* Random Forest 
* kNN

***

## Deliverables

* Report
* Complete code
* Presentation
