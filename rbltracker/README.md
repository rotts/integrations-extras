## Overview

RBLTracker provides easy-to-use, real-time blacklist monitoring, for your email, website, and social media.

Connect your [RBLTracker](https://rbltracker.com/) account to Datadog to:

*   Push listing events from RBLTracker to your dashboard.
*   Push de-listing events from RBLTracker to your dashboard.

## Setup
### Configuration

Setting up RBLTracker using webhooks:

1.  In Datadog, copy your API key from the **Integrations -> APIs** section.
2.  In [RBLTracker](https://rbltracker.com/), create a new Datadog contact type from the **Manage -> Contacts** section of the RBLTracker portal.
3.  Paste the Datadog **API Key**.
4.  (optional) adjust the contact schedule for this new contact.

RBLTracker will send listing and delisting alerts to your Datadog events dashboard. Click [here](https://rbltracker.com/docs/adding-a-datadog-contact-type/) for a full integration guide.

## Data Collected
### Metrics
See [metadata.csv](https://github.com/DataDog/integrations-extras/blob/master/rbltracker/metadata.csv) for a list of metrics provided by this integration.

### Events
Push your RBLTracker listing/de-listing events into your [Datadog Even Stream](https://docs.datadoghq.com/graphing/event_stream/) 

### Service Checks
The RBLTracker check does not include any service checks at this time.

## Troubleshooting
Need help? Contact [Datadog Support](http://docs.datadoghq.com/help/).

## Further Reading

Learn more about infrastructure monitoring and all our integrations on [our blog](https://www.datadoghq.com/blog/).