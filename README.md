# Autorisatie

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Document historiek](#document-historiek)
- [OAuth2](#oauth2)
  - [Introductie](#introductie)
  - [Registratie van de applicatie](#registratie-van-de-applicatie)
  - [Authenticeren als een applicatie](#authenticeren-als-een-applicatie)
    - [OAuth2 profiel: client_credentials](#oauth2-profiel-client_credentials)
      - [1) access_token ophalen](#1-access_token-ophalen)
      - [2) API oproepen](#2-api-oproepen)
  - [Authenticeren als een gebruiker](#authenticeren-als-een-gebruiker)
    - [OAuth2 authorizatie server](#oauth2-authorizatie-server)
    - [OAuth2 profiel: authorization_code](#oauth2-profiel-authorization_code)
      - [1) de gebruiker naar de OAuth2 authorizatie applicatie redirecten](#1-de-gebruiker-naar-de-oauth2-authorizatie-applicatie-redirecten)
      - [2) access_token bekomen](#2-access_token-bekomen)
      - [3) API oproepen](#3-api-oproepen)
    - [OAuth2 profiel: implicit](#oauth2-profiel-implicit)
  - [Uitloggen](#uitloggen)
  - [Het uitloggen van een gebruiker initiëren vanuit jouw applicatie](#het-uitloggen-van-een-gebruiker-initi%C3%ABren-vanuit-jouw-applicatie)
  - [De gebruiker in jouw applicatie uitloggen wanneer deze in een andere applicatie uitgelogd is](#de-gebruiker-in-jouw-applicatie-uitloggen-wanneer-deze-in-een-andere-applicatie-uitgelogd-is)
- [SAML](#saml)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# OAuth2

## Introductie

Intro
