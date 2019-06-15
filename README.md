# Why do we need language independent components? 
The objective of language independent components is to reuse plenty of existing code solutions written in different languages on creating new applications.

# How do they work?
Every component is represented by code repository containing .lic file which describes the interface of the component.

# What can .lic file contain?
```
{
  name: "ContactFormPage"
  description: "Contact form hadler for web application. Managing records && sending via email, slack, etc"
  tags: ["contactform", "web", "webform"]
  url: http://contactformpage.lic.org
  implements: [...]
  repo: {
    type: "git"
    url: "github..."
  }
  version: 0.1,
  commands {  
    install {
      script: "install.sh",
      params: {
      
      }
    }
	  start: "start.sh"
	  stop: "stop.sh"
    process: "process.sh"
  }
  events: [
	  {
		  name: ContactFormSent,
		  params: {

		  }	
	  }
  ]
  dependencies: {
	  nameOfInterface: {
		  testedImpmementationNames: [],
		  version: 1.1,
		  optional: true
	  },
	  httpLayer: {
		  testedImpmementationNames: [],
		  version: 1.1,
		  optional: true
	  }
	  ...
  }
```

# What is licplatform?
LIC platform helps to setup, compose, bind, deploy and monitor applications built from language independent components.
