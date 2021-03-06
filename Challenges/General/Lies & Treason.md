# Lies & Treason
Name: Lies & Treason

Category: Financial OSINT

Type: Automatic

Flag: `CYBAR{THERESA}`

Points: 450

Difficulty: Medium

Status: Playable after CTF ends

Real Person or Ficticious: Real

## Summary
Even with the ASIC website down during the CTF, players have to try and find key information that might be revealed through various business/corperate information registers.

## Description
An email comes in from a Threat-Intelligence lead in France. Apparently, in a routine Occupational Health & Safety (OH&S) check, inspectors found a warehouse stacked to the roof of roombas. Fortunately, none of them had been pre-loaded with consciousness, but when police arrived on the scene the entire stock was gone.

Fortunately, the warehouse's company was tracked down to an expensive suburb in Sydney's harbour district. **"CYBAR PROPERTY PTY. LTD"** The TI is only a junior and mentions they've done a quick search of the owner - Lillie - but can't find any more information. A laptop found in the French warehouse requires a password and we NEED to find if there are any other Australian warehouses owned by Lillie storing potentially dangerous roombas.

The TI has left you a voicemail: **"The password hint on the laptop is 'my middle name'. Can you grab the current company information and see if the records contain her middle name? I'm sorry, but no one's going to expense you on this one, you gotta find it yourself. Goodluck"*

## Solution
Official: Find the ABN/ACN of the company "CYBAR PROPERTIES PTY LTD". Once found, visit the ASIC register information and purchase the $9 company information record. Lillie Cawthorne's middle name is listed within the document on page 2.

Unofficial: Various other business/corp sites that list this, including one of her book deals.

## Intended Tools
ABN Search
ASIC Register
Google

## Included Files
[ASIC Company Extract](../Files/lies_&_treason.pdf)