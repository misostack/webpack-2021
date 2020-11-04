# Webpack Configuration Master Class

## Plugins

```bash
yarn add @babel/core @babel/preset-env babel-loader css-loader file-loader html-webpack-plugin mini-css-extract-plugin node-sass sass-loader style-loader
```

```bash
yarn add -D webpack webpack-cli webpack-dev-server copy-webpack-plugin clean-webpack-plugin
```

## Project

> Sample

```json
{
  "id": 8877163,
  "jwt": "eyJhbGciOiJSUzI1NiJ9.eyJ0eXAiOiJ1c2VyIiwidWlkIjo4ODc3MTYzLCJwbG4iOiJmcmVlIiwiZXhwIjoxNjA0MjQwMzc1LCJpYXQiOjE2MDQyMzY3NzV9.U3sqKgQ1MSz5VxTxNVOXjV3KKomIxELATmdrGcAOCkyJ-Q60dk_FBbPjfekqh1bnyLdQPqCuaJh_DwSeCrTisDyilB2mEp-ZSiIJ-uFVKwv3E3TSO9i7rbo15V63CBXpEzQJb7pcqQ50oaoiGmyPfNVKhzxcLu7mmlCeFPboYgPiTc9yrGkB8XuefpkyG25NPbUd152QpjBHV-sAsPlU4Cpu0DhiEUbrvtTmP41mYRV9HXLHh-8f-kHLfk0LwH-oKuSf5RRkcyaUSuv3g7RCYLuC2NuR6XryqFx4VRZdphylPNSEjUIOp6QzDb2osAr_1mmkPv2A0qEOgY5RuTUpICgMdJ9kIo9jf5Llzs9Q2uSoFkLjCGEhJ0-mBqU37XMFK8AjaXIhKAmhnoPqw7AsVXSHvD5tUfRDhvr6ZlSvJDomVfgudjbf3qRgRjbC89GaS8v8eDkeYJl4InDe68BjIS2IRNFfhI4ELQ4PYKSkhtG2IGbR-vQG6WHXmTsQk3GdnYaUVZxydQdv_XMClxQTBvL5ypO9kSzOd_WyIKNH2e75uGVcNsIGJ4A8keHFskUf0XxAY71EWBP6pfvtYGP1UgeO_tUSxZZtrcxL3NE16TvG-9U1ko0Vxm5n1NF34dCvv9ddgBzJhqj0OGosfYekuu_qyThpy2VDVhmR-4ieQlE",
  "jwtExpiresAt": "2020-11-01T15:19:35.000+01:00",
  "email": "gmmiso88@gmail.com",
  "unconfirmedEmail": null,
  "firstName": "Son",
  "lastName": "Nguyen",
  "fullName": "Son Nguyen",
  "registeredAt": "2020-11-01T14:16:27.863+01:00",
  "hasPremiumFeatures": false,
  "billingStatus": "free",
  "billingInfo": {
    "subscriptionProvider": "stripe",
    "upgradeUrl": "https://resume.io/app/billing/plans",
    "cancelSubscriptionUrl": "https://resume.io/app/billing/subscription/feedback",
    "onTrial": false,
    "cancelledAt": null,
    "premiumEndsAt": null,
    "nextPaymentAt": null
  },
  "socialProfiles": [
    {
      "uid": null,
      "provider": "facebook",
      "connected": false,
      "connectionUrl": "/auth/facebook"
    },
    {
      "uid": null,
      "provider": "linkedin",
      "connected": false,
      "connectionUrl": "/auth/linkedin"
    },
    {
      "uid": "102504427551826823189",
      "provider": "google_oauth2",
      "connected": true,
      "connectionUrl": "/auth/google_oauth2",
      "profileUrl": null,
      "handle": "gmmiso88@gmail.com"
    }
  ],
  "visitedPlans": true,
  "announceEnabled": true
}
```

> Content is King

- https://resume.io/resume-examples/software-developer
- https://resume.io/how-to-write-a-resume/list-skills-on-your-resume
- Edit form : https://resume.io/app/resumes/10506707/edit
- https://itviec.com/blog/11-mau-cv-it-chat/

### References

1. https://recycle.orionthemes.com/demo-1/
2. https://stability.dan-fisher.dev/
3. http://preview.themeforest.net/item/itobuz-one-page-html-template/full_screen_preview/8372118?_ga=2.147683575.1190788254.1604477470-541619344.1591020551
4. https://radiustheme.com/demo/wordpress/redchili/
5. http://themes.pixiesquad.com/?theme=pixiebolt&utm_source=themeforest-pixiebolt&utm_medium=referral

### Centering things

- https://www.w3.org/Style/Examples/007/center.en.html
- https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Aligning_Items_in_a_Flex_Container