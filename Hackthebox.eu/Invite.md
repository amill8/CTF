# Go invite urself

In order to join you have to invite yourself, as the website asks you for an Invite Code
Inspecting the page, find the script 'https://www.hackthebox.eu/js/inviteapi.min.js'

Make a call in console 'makeInviteCode()', which returns you an Object with data encoded in BASE64

Use https://www.base64decode.org to decode which results in 'In order to generate the invite code, make a POST request to /api/invite/generate'
Using Postman, make a POST request to https://www.hackthebox.eu/api/invite/generate

Decode the data, which is going to be your invite code
```
{
    "0": 200,
    "success": 1,
    "data": {
        "code": "VUhXQlYtVkNaR1ktUlpHTUctSVBMT1ItRUxD****",
        "format": "encoded"
    }
}
```
Good job, hackerman :tada:

UHWBV-VCZGY-RZGMG-IPLOR-****
