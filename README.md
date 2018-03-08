# DHealth Signup Frontend

https://signup.dhealth.live

Registration Frontend for Dhealth.live

## Installation
```
npm i
npm run dev 
npm run build
```

## ENV

There are 6 different ENV that have to be setup.

You can find these under the folder **config**

```
  NODE_ENV: '"production"',
  ROOT_PATH: '"https://signup.dhealth.live"', // or localhost for dev
  API_PATH: '"https://api.dhealth.live/api"', // or localhost for dev
  FACEBOOK_CLIENT_ID: '"CLIENT_ID"',
  GITHUB_CLIENT_ID: '"CLIENT_ID"',
  LINKEDIN_CLIENT_ID: '"CLIENT_ID"'
```

These have also corresponding ENV variables in api.dhealth.live which have to be changed as well

