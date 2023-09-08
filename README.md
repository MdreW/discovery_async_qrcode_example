# discovery_async_qrcode_example

example of discovery page that creates the qr code from remote on click string.
The discovery page is configured from load the remote json from https://common.intranet.isprambiente.it/code.json.
The remote json contain this data: `{"code": "https://www.isprambiente.gov.it/it", "ttl": 150}`

must be implemented the authentication check. In response json must be added the authentication id, the url for check the status, and the redirect url on success.
