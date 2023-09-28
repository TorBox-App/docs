# TorBox Open Source Docs

Houses documentation for the TorBox open source projects. If you are looking for docs for the hosted version, they can be found [here](https://support.torbox.app). The open source documentation is hosted by Mintlify, and is using Mintlify.

### 👩‍💻 Developing

If you see an error, think something can be written better, or just want to add content to the docs, open a pull request and add the information you like.

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command

```
npm i -g mintlify
```

Run the following command at the root of your documentation (where mint.json is)

```
mintlify dev
```

#### Troubleshooting

- Mintlify dev isn't running - Run `mintlify install` it'll re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `mint.json`
