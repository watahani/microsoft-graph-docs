
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let res = await client.api('/drive/root/workbook/worksheets/{id}/pivotTables/{id}')
	.version('beta')
	.get();

```