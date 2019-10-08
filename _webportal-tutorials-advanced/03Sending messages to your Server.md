---
type: tutorial advanced
---

# Sending a message to your Server

#### What you need

- [Being connected to the MQTT Broker]({{ site.baseurl }}/webportal/tutorial-advanced/#connecting-to-the-mqtt-broker)

- Your [MQTT Subscription Topic]({{ site.baseurl }}/webportal/tutorial-advanced/#selecting-your-mqtt-publishing-topic) looking as follows : `psa/OVIPPartners-Dev/to/uid/{UID}/opa/{VIN|#}/` 

### Sending a Message

The Application generates a message that is encapsulated inside the *content* field then sent to the WebPortal before being forwarded to the Application server through the PSA Messaging System.

To send a message you can do the following:

```javascript
window.parent.postMessage({
    'type' : 'WebPortal.onSendNotificationRequest',
    'value' : yourDataPayload
}, '*');
```

>**Note**: the max size for a MQTT message is 128 Kio
