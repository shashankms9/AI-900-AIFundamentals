## Explore Cognitive Services

Azure Cognitive Services encapsulate common AI functionality that can be categorized into four main pillars: vision, speech, language, and decision services. In this exercise you will take a look at one of the decision services to get a general sense of how to provision and use a cognitive services resource in a software application.

The specific cognitive service you'll explore in this exercise is *Anomaly Detector*. Anomaly Detector is used to analyze data values over time, and to detect any unusual values that might indicate a problem or an issue for further investigation. For example, a sensor in a temperature-controlled storage facility might monitor the temperature every minute and log the measured values. You can use the Anomaly Detector service to analyze the logged temperature values and flag any that fall significantly outside of the normal range of expected temperatures.

This exercise is part of a module on Microsoft Learn, and requires an Azure subscription. You should use the Azure subscription provided as part of the class.

> **Note**: The goal of this exercise is to get a general sense of how cognitive services are provisioned and used. Anomaly Detector is used as an example, but you are not expected to gain a comprehensive knowledge of anomaly detection in this exercise!

### Exercise 1

#### Task 1 : Create an Anomaly Detector resource

1. Let's start by creating an Anomaly Detector resource in your Azure subscription:

2. In another browser tab, open the Azure portal at https://portal.azure.com, signing in with your Microsoft account.

3. Click the ＋Create a resource button, search for Anomaly Detector, and create an Anomaly Detector resource with the following settings:

    - Subscription: Your Azure subscription.
    - Resource group: Select an existing resource group or create a new one.
    - Region: Choose any available region
    - Name: Enter a unique name.
    - Pricing tier: Free F0

Review and create the resource, and wait for deployment to complete. Then go to the deployed resource.

View the Keys and Endpoint page for your Anomaly Detector resource. You will need the endpoint and keys to connect from client applications.
  
