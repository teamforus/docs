# organisation-internal
This repository is to be used for internal organisational structure and discussions.


## Repository Structure:

The following repository naming structure tries to avoid confusion and make it as easy as possible to understand where to create comments/issues and how to name new repositories.

Repos are categorized as either being **top-level** or child. All issues should go to the top-level (open-source) repository unless there is a specic reason to add it to a child repository (for example it should be kept private).

Sub-repositories can be either open or closed source and can optionally be added to the top-level repository as a submodule. e.g. how it’s done at https://github.com/teamforus/me

New repos will be prefixed with the corresponding top-level repo name if there is one available.

## Top level repo’s (open source):
**me**  
**forus**  
**research-and-development**  
**service**  
**foundation**  
**organisation**  

_Note: The difference between foundation and organisation is that foundation is about the legal entity, its employees, organisation and finances. Organisation is for all involved parties, regardless of their company._

_Added bonus: 6 repositories is exactly the amount we can pin on https://github.com/teamforus_

## Top level + child repo’s:

**me**  
me-api
me-api-identity
me-android  
me-ios  

**forus**  
forus-front  
forus-front-ext-provider  
forus-front-ext-sponsor  
forus-front-ext-...  
forus-api 
forus-api-media  
forus-api-records  
forus-api-records-mysql  
forus-api-fund  
forus-api-validator  
forus-api-provider  
forus-api-sponsor  
forus-api-category 

**research-and-development**  
rd-demo.api.forus.io
rd-ethereum-eventhub

**service**  
service-support  
implementation-westerkwartier
chat.forus.io  

**foundation**  
foundation-internal  
foundation-finance  
foundation-direction  
foundation.forus.io  

**organisation**  
organisation
organisation-internal