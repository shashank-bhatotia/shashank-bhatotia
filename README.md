## Hi, I'm Shashank 👋

Full-stack product engineer. Rails on the backend, React Native on mobile.

I've spent nearly seven years at BigBinary building software end to end. Right now that's [Aligned Showings](https://www.alignedshowings.net), the scheduling and messaging platform MLS Aligned puts in front of a US network of listing services, used by more than 150,000 real-estate agents. A regulated workflow with real money behind it: the rules change often and getting it wrong is expensive.

### React Native (Meta) contributor

I wrote the fix for an Android crash in React Native's animation system, where a mapped prop node could be removed mid-animation and take the app down. It [ships in React Native 0.87](https://github.com/react/react-native/commit/53369ed3216d973b52fd825001a53434137da4a6) via [#57298](https://github.com/react/react-native/pull/57298) and closes [#37267](https://github.com/react/react-native/issues/37267), open since 2023.

The crash only reproduced probabilistically on a device, so it went in with a regression test that reproduces the race deterministically. It cannot be reverted silently.

Also upstream in react-native-app-auth: a broken iOS SSO login traced to a type boundary, where a JavaScript `state: null` reaches Objective-C as `NSNull` and reads as truthy. Open PR [#1125](https://github.com/FormidableLabs/react-native-app-auth/pull/1125).

### What I build now

**Aligned Showings.** Client product for MLS Aligned, Rails and React Native. I spend as much time on the workflow as on the code.

**Neeto.** BigBinary's own SaaS suite. I own React Native apps in it end to end: user feedback, specs, implementation, debugging, code review, and the App Store and Play Store releases. neeto-ui-rn, one of the component libraries I help maintain, is the UI layer under six shipped iOS apps.

### Stack

**Backend** · Ruby on Rails, Ruby, PostgreSQL, PostGIS, Sidekiq, Redis, OpenSearch, REST APIs, OAuth2, AWS S3
**Mobile** · React Native (iOS and Android), Redux, React Navigation, Mapbox, push notifications
**Integrations** · RETS (MLS data), Twilio, PubNub

I use AI tools every day, mostly to get through the boring parts faster. Nothing ships until I have reproduced and verified it.

I work remotely from Gurugram, India. Most interested in teams putting AI in front of real users, where being wrong has a cost.

🔗 [Website](https://shashank-bhatotia.github.io) · [Email](mailto:shashankbhatotia@gmail.com) · [LinkedIn](https://www.linkedin.com/in/shashank-bhatotia/)
