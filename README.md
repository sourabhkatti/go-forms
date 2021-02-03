# go-forms

An example Go forms application built from the tutorial here: https://gowebexamples.com/forms/

This application can be used to try out the Contrast Go agent

## Steps to run the application WITH the Contrast Go agent:
1. [Download](https://docs.contrastsecurity.com/en/install-the-go-agent.html) the Go agent 
2. [Download](https://docs.contrastsecurity.com/en/contrast-service.html) the Contrast Service
3. [Setup](https://docs.contrastsecurity.com/en/go-configuration.html) your Contrast configuration (contrast_security.yaml)
4. Instrument your application with the Go agent: `./contrast-go build -o go-forms`
5. Run the Contrast Service: `./contrast-service`
6. Run the application: `./go-forms`
7. Visit the application at localhost:8080 and submit a form
8. The application should now show up in your Contrast UI


## Steps to run the application WITHOUT Contrast:
1. Built the application: `go build -o go-forms`
2. Run the application: `./go-forms`
