# Niffy


## Introduction

Prevent merchants from printing your invoices and receive them instantly in your smartphone.


## Description

Niffy allows consumers to receive their shopping invoices in real time on their smartphones. Merchants can automatically skip invoice printing whenever their customers have sign up on Niffy.

When a merchant fills in its customer tax id on creating an invoice, the following occurs:
 * Niffy is inquired using the customer tax id;
   * If the response is positive, printing is skipped and the customer gets its invoice on the smartphone through the Niffy app;
   * If the response is negative, business as usual: the printer will spit some paper.

Consumers:
 * Must sign up on Niffy with their tax id
 * Can gather all their invoices in one place
 * Can use stored invoices for warranty purposes (no thermal printing fading away)

Merchants:
 * Save money on printing costs
 * Save time on printer maintenance (paper replacement, etc.)
 * Improve customer satisfaction

Everyone:
 * Protect the environment!


## Team

 * João Colaço (https://pixels.camp/jcolaco-nmz)
 * Rui Pinge (https://pixels.camp/ruipinge)
 * Hélder Duarte (https://pixels.camp/cossou)


## Code repository

Check out the code created during Pixels Camp at https://github.com/jcolaco-nmz/niffy


## URL

We application available at https://niffy-pixelscamp.appspot.com

iOS app not available (yet!) in the App Store


## Other information

This project includes some challenges related with consumers, merchants and invoicing software houses identity verification. A few distinct methods have already been discussed:

 * mail letter with code sent to a public address
 * __unprivileged__ user credentials for tax portal
 * presential consumer id confirmation done by merchants
 * id card reader

Additional notes:
 * Niffy calls can be part of the invoicing software.
 * Only verified software houses and/or merchants are allowed to query Niffy.
 * Another aproach can include a hardware device between the POS and printer; it can look into ESC/POS commands to inquire Niffy, achieving the same result when software integration is not available or possible.
