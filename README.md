# Okta-Hub-and-Spoke-Identity-Integration

## Feature
+ Implemented a full Okta Org2Org SAML federation in a hub-and-spoke multi-tenant architecture, with the spoke acting as the primary identity provider
+ Configured SP-initiated and IdP-initiated SSO flows, enabling cross tenant authentication for applications
+ Designed attribute mapping to align profile schemas between tenants to facilitate automated lifecycle management cross Org2Org integration

### Steps
* ✅ At the spoke, set up Org2Org, and choose SAML

<img src="org2org.png" width="80%">

<img src="org2org saml instructions.png" width="80%">

<img src="org2org saml signon.png" width="80%">


* ✅ At the spoke, enable provisioning

<img src="org2org saml provision.png" width="80%">


* ✅ At the spoke, assign Org2Org

<img src="org2org app assignment.png" width="80%">


* ✅ At the hub, set up IdP and enable linking

<img src="org2org idp setting.png" width="80%">


* ✅ At the spoke, map attributes

<img src="org2org attribute mapping.png" width="80%">


* ✅ Push groups from spoke to hub

<img src="org2org push group.png" width="80%">
<img src="org2org push group2.png" width="80%">
