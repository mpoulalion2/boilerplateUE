# Forms Boilerplate for Xwalk
Archiving this repository as it has been merged with https://github.com/adobe-rnd/aem-boilerplate-forms.  
Please use https://github.com/adobe-rnd/aem-boilerplate-forms to initialise your forms projects for xwalk.

## Environments
- Preview: https://main--boilerplateUE--mpoulalion2.hlx.page/
- Live: https://main--boilerplateUE--mpoulalion2.hlx.live/

## Installation

```sh
npm i
```

## Linting

```sh
npm run lint
```

## Local development

1. Create a new repository based on the `aem-boilerplate-forms` template and add a mountpoint in the `fstab.yaml`
1. Add the [AEM Code Sync GitHub App](https://github.com/apps/aem-code-sync) to the repository
1. Install the [AEM CLI](https://github.com/adobe/helix-cli): `npm install -g @adobe/aem-cli`
1. Start AEM Proxy: `aem up` (opens your browser at `http://localhost:3000`)
1. Open the `boilerplateUE` directory in your favorite IDE and start coding :)
