# organisation-internal
This repository is to be used for internal organisational structure and discussions.


## Repository Structure:

The following repository naming structure tries to avoid confusion and make it as easy as possible to understand where to create comments/issues and how to name new repositories.

Repos are catagorized as either being **top-level** or child. All issues should go to the top-level (open-source) repository unless there is a specic reason to add it to a child repository (for example it should be kept private).

Sub-repositories can be either open or closed source and can optionally be added to the top-level repository as a submodule. e.g. how it’s done at https://github.com/teamforus/me

New repos will be prefixed with the corresponding top-level repo name if there is one available.

## Top level repo’s (open source):
**me**  
**forus.io**  
**research-and-development**  
**service**  
**foundation**  
**organisation**  

_Note: The difference between foundation and organisation is that foundation is about the legal entity, its employees, organisation and finances. Organisation is for all involved parties, regardless of their company._

_Added bonus: 6 repositories is exactly the amount we can pin on https://github.com/teamforus_

## Top level + child repo’s:

**foundation**  
foundation-internal  
foundation-finance  
foundation-direction  
foundation.forus.io  

**organisation**  

**service**  
service-support  
service-implementation  
service-collaboration  
service-chat.forus.io  

**me**  
me-android  
me-ios  

**forus.io**
forus.io-front  
forus.io-front-ext-provider  
forus.io-front-ext-sponsor  
forus.io-front-ext-...  

**api.forus.io** (backend: decentralized)  
api.forus.io-identity  
api.forus.io-media  
api.forus.io-records  
api.forus.io-records-mysql  
api.forus.io-fund  
api.forus.io-validator  
api.forus.io-provider  
api.forus.io-sponsor  
api.forus.io-category  
api.forus.io-product  
api.forus.io-assets  
api.forus.io-vouchers  
api.forus.io-token  
api.forus.io-transaction  

**services.forus.io** (backend: centralized / oracle)  
services.forus.io-php  
services.forus.io-bunq  
services.forus.io-digid  
services.forus.io-notifications-email  
services.forus.io-notifications-push  
services.forus.io-db-zuidhorn  
services.forus.io-etc..  