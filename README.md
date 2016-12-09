# predix-static-content
Static content instruction to Predix

`$ echo 'Hello World' > index.html`

`$ touch Staticfile`

Cloud Foundry requires a file named Staticfile in the root directory of the app to use the Staticfile buildpack with the app.

`$ cf push <unique route> -m 64M`