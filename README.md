# Google Tag Manager Criteo User Identification Tag

The purpose of this tag is to call Criteo Identification Services, enable PSB APIs and store the result in 2 first party cookies : 

* **crto_mapped_user_id** : id of the user retrieved by Criteo
* **crto_is_user_optout** : information about if the user has opted-out of Criteo Retargeting

The lifetime of these cookies is 3 days, and no additional calls to Criteo Services are made if the cookies are already present.

# Installation

Please get in touch with your Criteo contact to get your **callerId** and **partnerId**, two parameters for this Tag which is used for User Identification.
