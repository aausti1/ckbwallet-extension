# CKB wallet Extension

An simple extension wallet for Nervos CKB.
           
## Building

1. `git clone git@github.com:aausti1/ckbwallet-extension.git`
   or
   `git clone https://github.com/aausti1/ckbwallet-extension.git`
2. `yarn`
3. `cp .env.example .env`
4. `yarn dev` to compile once or `yarn watch` to run the dev task in watch mode
5. `yarn build` to build a production (minified) version
6. `yarn test` to run test

## Lint

We use eslint, Please install the following extensions in your vscode:

- ESLint
- Prettier
- EditorConfig

## How to install

### Installation for developer

1. Complete the steps to build the project above
2. Go to [_chrome://extensions_](chrome://extensions) in Google Chrome
3. With the developer mode checkbox ticked, click **Load unpacked extension...** and select the _dist_ folder from this repo

### Installation for non-developer

1. Download the latest released zip file: https://github.com/aausti1/ckbwallet-extensionreleases

2. Uncompress `ckbwallet-extension.zip`, you will get a folder named `ckbwallet-extension`

3. Open Chrome `chrome://extensions/`, enable `Developer mode`

4. Click `Load unpacked` button, select `ckbwallet-extension` folder

5. You will see synapse extension icon on you tool bar
