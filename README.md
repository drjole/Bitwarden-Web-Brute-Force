# Bitwarden-Web-Brute-Force

## Introduction

Brute-force your way into your Bitwarden vault if you have a list of possible passwords.

This is the result of my attempt to change the master password of my Bitwarden vault and immediatly forgetting some parts of it. Luckily I could generate a list of possible passwords since I still knew enough of the actual password.

This repository does not aim at being super clean or maintained. Instead it is just the few lines of code I needed to get back into my vault.

## Usage

Adjuts the code to your needs:

- Adjust the list of words.
- Look for the query selectors of the master password input field and the submit button since they might change in the future and adjust them accordingly.
- I did not optimize the sleep times since I had only *a few* passwords to check.

Finally: Do not try to guess my password from the word list in the script; I of course changed it immediately and stored it in a secure location.
