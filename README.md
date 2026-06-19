# Okta-Hub-and-Spoke-Identity-Integration

## Feature
+ Implemented a full Okta Org2Org SAML federation in a hub-and-spoke multi-tenant architecture, with the spoke acting as the primary identity provider
+ Configured SP-initiated and IdP-initiated SSO flows, enabling cross tenant authentication for applications
+ Designed attribute mapping to align profile schemas between tenants to facilitate automated lifecycle management cross Org2Org integration

### Steps
* At the spoke, set up Org2Org


 
* At the hub, set up IdP
*      
* Install Git
* Start sonarqube server run in docker container: `docker run -d --name sonar-server -p 9000:9000 sonarqube:lts-community`; correpondingly, open port 9000 in security group
