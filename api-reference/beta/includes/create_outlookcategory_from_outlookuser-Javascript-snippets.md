
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const outlookCategory = {
      displayName:"Project expenses",
      color:"preset9"
};

let res = await client.api('/me/outlook/masterCategories')
	.version('beta')
	.post({outlookCategory : outlookCategory});

```