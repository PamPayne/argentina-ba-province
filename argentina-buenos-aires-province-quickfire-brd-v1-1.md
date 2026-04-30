---
source_url: https://dbnsa.sharepoint.com/sites/ComplianceOfficers93/Regulatory Repository/Rest of World/Argentina BA Province/3. Project/Argentina Buenos Aires Province - QuickFire BRD v1.1.pdf
country: Argentina
document_name: Argentina Buenos Aires Province - QuickFire BRD v1.1
source_file: Argentina Buenos Aires Province - QuickFire BRD v1.1.pdf
source_url: https://dbnsa.sharepoint.com/sites/ComplianceOfficers93/Regulatory Repository/Rest of World/Argentina BA Province/3. Project/Argentina Buenos Aires Province - QuickFire BRD v1.1.pdf
extracted_date: 2026-04-30
jurisdiction: Argentina BA Province
description: Business requirements document for the QuickFire solution in the regulated market of Argentina (Buenos Aires Province).
regulatory_body: Regulatory body of Argentina
---

# Argentina (Buenos Aires Province) QuickFire Solution

**Analyst** Ashley Dhunraj  
**Department** Quickfire - Business Analyst  
**Version** 1.1  
**Release Date** 07/23/2019  
**Project** Argentina (Buenos Aires Province)  
**QuickFire Solution**  
**MGS Order No.** TBD

Argentina (Buenos Aires Province) QuickFire Solution  
Version 1.1 Page 2 of 8 2019/07/23

## Table of Contents

**Table of Contents**

- TABLE OF CONTENTS ..................................................................................................................................................2
- REVISION HISTORY ....................................................................................................................................................3
- INTRODUCTION .........................................................................................................................................................4
- SCOPE ....................................................................................................................................................................4
- OUT OF SCOPE .........................................................................................................................................................4
- TEAMS IMPACTED .....................................................................................................................................................5
  - Casino ............................................................................................................................................................................ 5
  - Other ............................................................................................................................................................................. 5
- PRODUCTS IN SCOPE ..................................................................................................................................................5
- BUSINESS REQUIREMENTS ...........................................................................................................................................6

Argentina (Buenos Aires Province) QuickFire Solution  
Version 1.1 Page 3 of 8 2019/07/23

## Revision History

| Revision | Date | Changed By | Comments / Reason |
|---|---|---|---|
| 1.0 | 16 July 2019 | Ashley Dhunraj | Initial Version |
| 1.1 | 23 July 2019 | Ashley Dhunraj | Updated Autoplay 1.8.2 as per Michele’s review comment. |

Argentina (Buenos Aires Province) QuickFire Solution  
Version 1.1 Page 4 of 8 2019/07/23

## Introduction

This document provides the business requirements for Argentina (Buenos Aires Province) where we are looking to have games introduced into the regulated marked space. The requirements are based on the regulations specified by the regulatory body of Argentina.

This document will also highlight the adoption of the gaming components that will be customized to suit the , Argentinian (Buenos Aires Province) regulated market.

As a reference, Argentinian (Buenos Aires Province) legislation documents can be found at the following location:  
Argentina – Buenos Aires Province Legislation

## Scope

As with most Quickfire solutions, the bulk of the work will be pushed to the operator. However, we are still responsible for the gaming content. This includes translations, currency support and bet settings, as well as unique market requirements detailed in the business requirement section below.

The following games are in scope:

1. Slot Games – H5 (Mobile and Desktop)
2. Table Games
3. Jackpots (Allowed – TBC if we are taking jackpot games)

## Out of Scope

The following are out of scope.

1. Multiplayer games
2. Live Games (Live Dealer)
3. Slot Games – Flash (TBC)

The below checklists have been completed based on the information gathered to date and are merely intended to be an indication of the identified scope thus far. Both the BA and the relevant developers will be responsible for maintaining it for the duration of the project.

Argentina (Buenos Aires Province) QuickFire Solution  
Version 1.1 Page 5 of 8 2019/07/23

## Teams Impacted

### Casino

### Other

## Products In Scope

Viper Core X Feature Rich Games X Build & Configure MPV  
Flash Core X Integrations Support Casino DB  
Web Tech Casino Config Land Based White Box Testing  
HTML5 – Lobby Tools Dev QA Dev Partners  
X HTML5 - Games Live Dealer Services Casino Architecture  
X HTML5 - Core Casino Architecture  
X Markets Mobile Download Form Service Bingo  
Poker Banking Registration PCM  
X Testing Usability Art Playability  
X End Process QA X Back Office Service Managers X IT  
Viper HTML5 Lobby iCafe / On Cash CiP  
Flash (Lobby) HTML5 Instant Play Sportsbook CiB  
Flash Instant Play Land Based MPV MPF  
X Quickfire Live Dealer My Account X PlayCheck  
Forgot Password Responsible Gaming Help (Flare) Loyalty  
Change Username Avatar NemID Login App Open Bets Redirector  
Change Password Alias Activation CAPI X Integrity Checker  
Change Contact  
Details  
X H5 QuickFire

Argentina (Buenos Aires Province) QuickFire Solution  
Version 1.1 Page 6 of 8 2019/07/23

## Business Requirements

### 1. Games

#### 1.1. Currency

##### 1.1.1.
The currency will be the “Legal currency of Argentina” which currently is the Argentine peso.

| Dialog Text | Symbol | Currency Code (ISO 4217) | Country Code (ISO alpha-3) |
|---|---|---|---|
| Total Wagered | $ | ARS | ARG |
| Total Payout | $ | ARS | ARG |
| Balance | $ | ARS | ARG |
| View Pays – Credits | $ | ARS | ARG |
| Bet | $ | ARS | ARG |

Note: We may need to consider not showing the $ symbol in games as a representation of the Argentinian pesos, as to not confuse the player with the US$. We could show the currency ISO code (ARS) like we do for Colombia.

#### 1.2. Language

##### 1.2.1.
Game rules must be provided in Spanish.

##### 1.2.2.
There is no mention of the specific language requirements for games itself.

Note: We can assume that English only, semi translated and fully translated games in Spanish will be allowed (TBC)

#### 1.3. Access to Help

##### 1.3.1.
Microgaming game help files must be available for all Microgaming casino games.

#### 1.4. RTP

##### 1.4.1.
The RTP must be displayed in help files.

##### 1.4.2.
The prize percentages (RTP) established in the relevant game rules, or defined in the future by the regulator, shall apply.

#### 1.5. Games Demos

##### 1.5.1.
For each game, mode and version, a game demo must be included; that is, a game demo version.

##### 1.5.2.
This may be a video, a sequence of images or a presentation that allows to identify, in general, the main graphical aspects and game mechanics.

#### 1.6. Game Name

##### 1.6.1.
The name of the game that the participant is playing must be clearly visible on all associated screens.

Argentina (Buenos Aires Province) QuickFire Solution  
Version 1.1 Page 7 of 8 2019/07/23

#### 1.7. Wager Cycle

##### 1.7.1.
Quickspin can be enabled, as no minimum time for each spin is mentioned.

#### 1.8. Autoplay

##### 1.8.1.
Autoplay is allowed.

##### 1.8.2.
The player must be able to stop **Autoplay** at any given time.

##### 1.8.3.
A max **Autoplay** limited must be set. Although the max **Autoplay** limit value is not specified in the legislation we usually set this to 100 spins.

### 2. Playcheck

#### 2.1.
Players must have access to any information related to the gaming account balance, gaming history, deposits and withdrawals, as well as other related transactions.

#### 2.2.
**Playcheck** must be configured to provide transactions for the last 30 days, online.

Note: We will provide **PlayCheck** information on gaming history transactions. Operators will be responsible to provide other information which includes deposits and withdrawals.

### 3. Certification

#### 3.1.
Games must be certified.

#### 3.2.
The RNG must be certified.

### 4. Incomplete Games

#### 4.1.
The game rules must clearly state what will happen to an incomplete games upon reconnection. These are:

- wait for the participant,
- cancel the game,
- or continue the game until it is completed.

Argentina (Buenos Aires Province) QuickFire Solution  
Version 1.1 Page 8 of 8 2019/07/23

### 5. Incomplete Games Sweeper

#### 5.1.
The game rules must inform the player on how funds are returned for games incomplete games cancelled by the operator (there is no specific period mentioned in the regulations for which the incomplete games sweeper job must run)

#### 5.2.
Funds must be returned to the player for any incomplete game that is cancelled by the operator.

### 6. Integrity Checker

#### 6.1.
A documented procedure for managing the incidents of unavailability of one, several or all components, including associated technical measures, must be in place.

#### 6.2.
The components must perform self-diagnosis, check the critical files and check communications between the different components.

Note: This look like an **Integrity Checker** type solution. MGS to confirm if **Integrity Checker** will be implemented in this market.

### 7. Card Games

#### 7.1.
The number of decks must be clearly displayed.

#### 7.2.
If the cards are shuffled during the game, the player must be clearly informed how often this is performed and when it is done.

#### 7.3.
Different colours for each of the four suits are allowed.

#### 7.4.
Jokers or wild cards must be distinguished from the rest of the pack.

## Summary

The summarized list below shows the requirements that will require config/development effort by Derivco:

- Currency must be Argentinian Peso.
- Language must be Spanish.
- **Playcheck** must be configured to be visible to players for 30 days.
- **Autoplay** limit must be set (100 spins, maximum).
- Name of the game must be displayed on all pages.
- Incomplete Games – Sweeper job required.
- Helpfiles required in Spanish. It must contain the RTP and what happens to incomplete games.
- Game Demos required.
- **Integrity Checker** (TBC).
- Number of decks must be shown for card games.
- The player must be informed on number of times and when cards are shuffled.