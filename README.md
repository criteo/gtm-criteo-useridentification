# Google Tag Manager Criteo User Identification Tag

This Web Tag runs on the advertiser website, calls Criteo Identification Services and stores the result in 2 first party cookies : 

* **crto_mapped_user_id** : id of the user retrieved by Criteo
* **crto_is_user_optout** : information about if the user has opted-out of Criteo Retargeting

Both of these cookies have a life duration of 3 days, and no additional calls to Criteo Services are made if the cookies are already present.

# Installation

Please get in touch with your Criteo Account Strategist to get your **callerId**, the only parameter for this Tag which is used for User Identification.
