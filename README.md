# Parliament

Parliament is a process to easily enable products to host their developer focused documentation.
test

![owls](images/owls.jpg)
📷 Photo credit: [National Parks Service](https://www.nps.gov/index.htm)

## What is Parliament?

Parliament is a set of projects that enable the rapid and continuous deployment of developer documentation to an [internal doc portal](http://docs.corp.adobe.com/).

- [parliament-site](https://git.corp.adobe.com/devrel/parliament-site): a listing of all on boarded developer documentation
- [parliament-client-template](https://git.corp.adobe.com/devrel/parliament-client-template): the site template used for all documentation projects
- [parliament-ui-components](https://git.corp.adobe.com/devrel/parliament-ui-components): a set of reusable UI components shared between the site and the template
- [gatsby-remark-afm](https://git.corp.adobe.com/devrel/gatsby-remark-afm): a set of extensions to GitHub flavoured markdown that are in common use around Adobe

Once you [on board](onboarding.md) your project to Parliament it will automatically update the documentation portal whenever there is a new check in to your git repository. Our template uses the same manifest file format as the external [Adobe.io](https://adobe.io) website to make transition to external documentation site easier.

## When is Parliament available?

Parliament is currently in beta but you can join the beta immediately.

## How do I use Parliament?

If you have a git repository, git.corp.adobe.com or github.com, with a collection of markdown documents you can get started right away. Also, if you have your API spec using swagger in YAML or JSON format we will convert that to developer docs with auto generated source code examples.

Just follow our [Onboarding](onboarding.md) documentation!

## Who are Parliament?

Parliament is brought to you by the Adobe I/O Developer Relations team.

## Why is it called Parliament?

Well, Owls are wise animals and a collection of owls is called a Parliament. Not unlike the wisdom stored in our developer docs and collected on our documentation portal.

Also, the two main engineers behind the project are from countries, 🇨🇦 and 🇮🇳, which have parliamentary governments.

## Contributing

Parliament is an open development project and pull requests are welcome. For major changes, please open a [JIRA ticket](https://jira.corp.adobe.com/projects/DEVEP/issues) first to discuss what you would like to change. When filling out the JIRA ticket be sure to include the Epic Link, `Internal Microsite for Platform API Documentation` and Component, `Advocacy Sprint`
