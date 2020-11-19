De [richtlijnen rond identiteit authenticatie, en autorisatie](https://acpaas.digipolis.be/nl/docs/identiteit-authenticatie-en-autorisatie) bevatten een toelichting over welke componenten in welk autorisatie scenario gebruikt worden. Hieronder vindt je een kort overzicht over UME & BRaaS.

# Autorisatie via UME

## Introductie

De [User Management Engine](https://acpaas.digipolis.be/nl/product/user-management-engine) faciliteert de configuratie van de permissies van een gebruiker binnen een toepassing.

Opgelet! Het betreft enkel gebruikers met een M-profiel (typisch medewerkers) of systeem accounts.

Via de APIs 'Authz' of 'MeAuth' kan een toepassing de permissies van een gebruiker opvragen:

1. Authz = is een API om de permissies van een gebruiker op te vragen op basis van user id.
2. MeAuthz = is een API om de permissies van een gebruiker op te vragen op basis van OAuth token.

## UME en APIs

Meer info over het [beveiligen van applicaties met UME en APIs](https://wiki.antwerpen.be/ACPAAS/index.php/Securing_application_with_the_user_management_Engine) is hier terug te vinden.

## UME en rol provisioning 

1. Toegang aanvragen
   - [Aanvragen van een rol](https://wiki.antwerpen.be/ACPAAS/index.php/UM_Engine_-_Aanvragen_van_een_rol)
   - [Goedkeuren van een rol](https://wiki.antwerpen.be/ACPAAS/index.php/UM_Engine_-_Goedkeuren_van_een_rol)
   - [Status van rolaanvragen bekijken](https://wiki.antwerpen.be/ACPAAS/index.php/UM_Engine_-_Status_van_rolaanvragen_bekijken)
   - [Toegekende rollen bekijken](https://wiki.antwerpen.be/ACPAAS/index.php/UM_Engine_-_Toegekende_rollen_bekijken)

2. Rolbeheer
   - [Opvoeren van rollen (CSV)](https://wiki.antwerpen.be/ACPAAS/index.php/UM_Engine_-_Opvoeren_van_rollen_(CSV))
   - [Rollen beheren (manueel)](https://wiki.antwerpen.be/ACPAAS/index.php/UM_Engine_-_Rollen_beheren_(manueel))

3. Policybeheer
   - [Policies beheren](https://wiki.antwerpen.be/ACPAAS/index.php/UM_Engine_-_Policies_beheren)

4. Administrator
   - [Rechten binnen de User Management Engine toekennen](https://wiki.antwerpen.be/ACPAAS/index.php/Rechten_binnen_de_User_Management_Engine_toekennen)
   
# Autorisatie via BRaaS
De [BRaaS Engine](https://acpaas.digipolis.be/nl/product/braas-engine) faciliteert de configuratie van de rechten van een subject (gebruiker/toepassing/...) binnen een toepassing.

Het betreft gebruikers met volgende profielen:
1. Mprofiel (in combinatie met UME)
2. Aprofiel
3. Applicaties (gekend binnen de api-gateway)

Via de API 'Authz' kan een toepassing autorisaties van een subject opvragen op basis van een ID.
