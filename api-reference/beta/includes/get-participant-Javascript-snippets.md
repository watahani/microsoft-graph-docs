
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let res = await client.api('/app/calls/{id}/participants/{id}')
	.version('beta')
	.get();

```