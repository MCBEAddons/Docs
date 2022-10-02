# Overview

This category will explain how to use the Manifest classes.



{% tabs %}
{% tab title="TypeScript" %}
{% code title="index.js" overflow="wrap" lineNumbers="true" %}
```typescript
import { RP } from '@mcbeaddons/creatorjstypes';

const myAddonName = 'yourAddonName';
const myAddonDescription = 'yourAddonDescription';

const myRPManifest = RP.format({ name: myAddonName, description: myAddonDescription })

console.log(myRPManifest);
```
{% endcode %}
{% endtab %}

{% tab title="ESM" %}
{% code title="index.js" overflow="wrap" lineNumbers="true" %}
```javascript
import { RP } from '@mcbeaddons/creatorjstypes';

const myAddonName = 'yourAddonName';
const myAddonDescription = 'yourAddonDescription';

const myRPManifest = RP.format({ name: myAddonName, description: myAddonDescription })

console.log(myRPManifest);
```
{% endcode %}


{% endtab %}

{% tab title="CommonJS" %}
{% code title="index.js" overflow="wrap" lineNumbers="true" %}
```javascript
const { RP } = require('@mcbeaddons/creatorjstypes');

const myAddonName = 'yourAddonName';
const myAddonDescription = 'yourAddonDescription';

const myRPManifest = RP.format({ name: myAddonName, description: myAddonDescription })

console.log(myRPManifest);
```
{% endcode %}
{% endtab %}
{% endtabs %}

{% hint style="info" %}
You can also input a version using a number array, for example `[1,0,0]`
{% endhint %}
