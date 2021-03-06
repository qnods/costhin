---
title: Road to Reconciliation
layout: post-notes
tags: [notes, concept]
excerpt: Some ideas to smoothen your reconciliation process between your various accounts. 
---

This is a note that I write based on couple on things that I do before I start doing any reconciliation. Reconciliation is the process of matching various transactions in accounting. The most common one is when you try to match amount on your issued invoice and the actual amount that your client paid or when you try to match the amount sent from your credit card provider like Stripe or PayPal to your bank account. Reconciliation, can be frustrating especially if you have limited experience on doing accounting, but it is still doable and can be quite monotonous once you have discovered the pattern.

#### Account assessment
Start with check on all available statement that you have and need to be reconciliated. While most people aware that they have bank account where they receive payment from their customer, they sometimes forget other accounts that act as intermediary or the amount is too little. This can be statement from your credit card provider or cash in hand or something similar. All of those need to be accounted into your reconciliation.

#### Analyze the first point of contact of your income
If you receive payment via bank transfer, your first point of contact is your bank account so you should compare invoice issued with the amount received on your bank. However, if you receive payment via credit card provider like Stripe or PayPal and they transfer the money to your bank account at the later date, your first point of contact is your credit card provider like Stripe or PayPal and you should compare your invoice issued with the amount received on your Stripe or PayPal. The money that the credit card provider transfer to your bank account at the later date should be treated as internal transfer between your company’s different account.

#### Statement date vs Post /Value date
Most of the time, your bank account or statement from your credit card provider will have two different date. The first one is statement date which indicates when the transaction appears on your statement and the second one is post / value date which indicates when the transaction is actually received on your account. So, if your client says, they have paid you on 18 January 2021, you should be able to find the transaction on or after the post / value date of 18 January 2021 instead of try find the transaction based on the statement date.

#### Find the “common ground”
Although reconciliation is about matching between two different accounts, that does not mean you can only make a good guess which is transaction is which one solely based on amount received and transaction date. Most of the bank or credit card provider nowadays also provide expanded version of your statement that shows additional information, like the invoice number that your client enters when making payment or your client’s email in the case of credit card provider, they are providing extra column that can help you to match the transaction with your invoice list or your other statement. You can simply get all of these extra info by downloading the CSV version of your statement from your internet banking or your online account.

#### Formula and Pivot Table for Excel or Google Sheet
While you can do manual reconciliation from checking line by line of your two bank accounts, you can accelerate the matching process by learning VLOOKUP or Pivot Table. Simply just search on Google and you will find many explanations for this formula as well.