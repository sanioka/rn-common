# rn-common

Common documentation for my React Native apps:

https://github.com/sanioka/rn-tesla-clone

https://github.com/sanioka/rn-whatsapp-clone

https://github.com/sanioka/rn-todo-app

https://github.com/sanioka/rn-local-blog

https://github.com/sanioka/rn-letsgo-proto1

<br>

### How to build project

⚽️ Prepare expo environment by https://docs.expo.dev/get-started/installation/

⚽️ `npm install`

⚽️ `expo start` or `npm start`

⚽️ Install Expo app to mobile phone.

⚽️ Scan the QR code above with Expo Go (Android) or the Camera app (iOS)

<br>

### Upgrading Expo SDK

https://docs.expo.dev/workflow/upgrading-expo-sdk-walkthrough/

`npm i -g expo-cli`

`expo upgrade`

<br>


### Publishing to expo.io

`expo publish`

<br>

### Init AWS Amplify from Zero

https://docs.amplify.aws/start/getting-started/installation/q/integration/react-native/

https://www.youtube.com/watch?v=fWbM5DLh25U&t=34s

`npm install -g @aws-amplify/cli`

`amplify configure`

<br>

https://docs.amplify.aws/start/getting-started/nextsteps/q/integration/react-native

`amplify init`

`npm install aws-amplify aws-amplify-react-native @react-native-community/netinfo @react-native-async-storage/async-storage
copy`

<br>

### How to prepare AWS Amplify environment

[https://console.aws.amazon.com/](https://console.aws.amazon.com/) eu-central-1

> ⚠️ Error: Unable to resolve module `./aws-exports` from `App.tsx`:

> ⚠️ Unable to resolve module ../aws-exports from /Users/sanioka/Sites : Work/ReactNative/rn-letsgo-proto1/src/hooks/loadResourcesAndDataAsync.ts:

It means you need to generate 'aws-exports.js' file. So read config from AWS Amplify server:

`amplify -v` ? `do nothing` : `npm install -g @aws-amplify/cli` // check amplify-cli already installed

`amplify pull --appId ************ --envName dev` // 'aws-exports.js' file will be generated automatically

⚽️ See Notion App — react-native-amplify-1 (universal user)

<br>

(c) 2022