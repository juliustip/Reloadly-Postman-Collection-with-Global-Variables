# Reloadly Postman Collections with Global Variables

This a Reloadly postman collection with global variables that makes it easy to input onces the Live and Sandbox client ID, client secret and bearers for Airtime, Giftcards and Utility endpoints.

## Features
There is a pre-request script ```{{randomString}}``` for people who need random string and not wanting to use ```{{$guid}}``` for customIdentifier.

## Usage

After importing this collection, Click on Reloadly API


1. Select Variables tab and fill in the Current value fields.
    - client_id: Live Client ID 
    - client_secret: Live Client Secret 
    - sandbox_client_id: Sandbox Client ID 
    - sandbox_client_secret: Sandbox Client Secret 

    - bearer_airtime: Live authtoken for airtime
    - sandboxbearer_airtime: Sandbox authtoken for airtime
    - bearer_giftcard: Live authtoken for giftcards
    - sandboxbearer_giftcard: Sandbox authtoken for giftcard
    - bearer_utility: Live authtoken for utility
    - sandboxbearer_utility: Sandbox authtoken for utility
