# Predicting Default Borrowers for Lending Club

This repository contains all of the materials for my Capstone Project for Springboard's Data Science Bootcamp. 

***

## Background

Lending Club is an online peer-to-peer loan platform that allows individuals to take out personal loans of up to $40,000. Borrowers can easily apply for a loan online and will typically receive their money within a few days of submitting their application. Unlike a bank, the platform uses investors to fund loans and acts as the intermediary between investors and borrowers.

When an application is received and approved by Lending Club, it goes into their online platform. Investors can then select which loans to fund by either manually picking specific loans or having Lending Club automatically select a loan portfolio for them. As borrowers pay back their loans, investors receive monthly payments for the principal and interest on each loan. 

Occassionally a borrower does not pay back a loan in full and Lending Club must "Charge Off" the loan. This typically happens once a loan payment is at least 150 days past due, but can also occur earlier or later depending on the circumstances (i.e. a borrower files for bankruptcy). If a borrower charges off (AKA defaults) on their loan, there is limited recourse for an investor and the default can impact their return on investment. 

***

## Problem

Investors lose a significant amount of their potential earnings to loan defaults. As an example, Lending Club explains that a portfolio expecting to make 14% in annual interest, will lose approximately 8% due to defaults. After accounting for Lending Club's 1% fee, an investor can expect to make 5% annually on their investments. 

Is there a way to further maximize the return on investment for an investor while decreasing the amount of interest lost to loan defaults? 

In this project I will explore how much Lending Club loses to charged off loans and whether it is possible to create a model that predicts the risk of a specific borrower failing to pay off their loan. 

***

## The Data

Lending Club's __[dataset](https://www.lendingclub.com/info/download-data.action)__ that contains loan information from 2007-2011

***

## Models Used

* Random Forest 
* kNN

***

## Deliverables

* Report
* Complete code
* Presentation
