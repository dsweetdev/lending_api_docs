---
title: API Reference

language_tabs:
  - shell: Shell
  - java: Java  
  - csharp: C#
  - javascript--browser: JS  
  - javascript--node: NodeJS
  - php: PHP
  - ruby: Ruby
  - python: Python
  - perl: Perl
  - go: Go
  - swift: Swift


toc_footers:

includes:
  - APIReference/Lending/programs.md.erb  
  - APIReference/Lending/get_all_programs.md.erb    
  - APIReference/Lending/get_specific_program.md.erb  

  - APIReference/Lending/eligibilities.md.erb
  - APIReference/Lending/get_eligibilities_for_an_account.md.erb

  - APIReference/Lending/quotes.md.erb
  - APIReference/Lending/create_loan_quote.md.erb  
  - APIReference/Lending/get_specific_loan_quote.md.erb    
  - APIReference/Lending/get_loan_quotes_for_an_account.md.erb

  - APIReference/Lending/loans.md.erb
  - APIReference/Lending/create_loan.md.erb  
  - APIReference/Lending/get_specific_loan.md.erb
  - APIReference/Lending/get_loans_for_an_account.md.erb  
  - APIReference/Lending/get_loan_transaction_history.md.erb    
  - APIReference/Lending/close_loan.md.erb

  - APIReference/Lending/loan_transactions.md.erb    
  - APIReference/Lending/apply_interest.md.erb   
  - APIReference/Lending/make_payment.md.erb     
  - APIReference/Lending/add_collateral.md.erb     
  - APIReference/Lending/liquidate_collateral.md.erb   


  - APIReference/Lending/webhooks.md.erb    

  - errors

search: true

code_clipboard: true
---

# Overview

We're pleased to offer a brand new Lending API to make it possible for our partners to develop solutions that enable their end-users to obtain a USD loan against their Bitcoin position. This site is a supplement to our existing API documentation, and the methods herein are to be used in conjunction with it.

## Authentication & Authorization
No changes are required, as this API uses the same mutual TLS (mTLS) mechanism that you're familiar with. Provided you've worked with your implementation team to set up keys, certificates, and whitelisted IP's you'll be good to go!

## Postman Collection
The quickest way to get started is to use our [Postman](http://www.postman.com/) request collection. Ask about how to get started.

## Base URL

All URLs referenced in the documentation have the following base:

<code class="standout">https://api.example.com/v1/lending</code>