# A simple Docusaurus statically generated application, running on Spin

This is a template for building and statically exporting your
[docusaurus](https://docusaurus.io/) application and running it on
[`Fermyon Spin`](https://developer.fermyon.com/spin).

## Using the template

First, you need to tell the Spin CLI where to get the template:

```console
$ spin templates install --git https://github.com/VamshiReddy02/spin-docusaurus
Copying remote template source
Installing template docusaurus...
Installed 1 template
+-------------------------------------------------------------------------+
| Name         Description                                                |
+=========================================================================+
| Docusaurus   Build your front-end application using Docusaurus and Spin |
+-------------------------------------------------------------------------+
```


## Building and running your application

Before you can build your Docusaurus application, make sure to run `npm install` in
the target directory. You are now ready to start building your front-end. Run
`npm start` and start editing your application. Alternatively, you can run
`spin build` and `spin up` to build and run your application.


## Deploy your application to Fermyon Cloud

Using a free [Fermyon Cloud](https://cloud.fermyon.com) account, you can deploy
your WebAssembly applications and get a public URL:

```console
$ spin deploy
# your application will now be available at a *.fermyon.app URL
```

## Credits

The Docusaurus template is based on the
[official Docusaurus template](https://docusaurus.io/docs/installation).

[Blog on Deploying Docusaurus Website on Fermyon Cloud using Spin by Dipankar Das](https://medium.com/@dipankardas0115/bridging-distances-deploying-docusaurus-website-on-fermyon-cloud-using-spin-aws-cloudfront-and-fe0609ab79a7).
