---
description: >-
  Step-by-step guide for connecting your G Suite account to Leave Me Alone.
  Takes 1-2 minutes to complete.
---

# Connecting a G Suite account

![](../.gitbook/assets/image%20%283%29.png)

## Step 1: Manage app access control

1. [Sign in to your Google Admin Console](https://admin.google.com/) and go to **Security**.
2. Scroll to the bottom and click **API Controls**.
3. Under App access control click **MANAGE THIRD-PARTY APP ACCESS**.

{% tabs %}
{% tab title="View steps in a video" %}
![](../.gitbook/assets/1-manage-3rd-party-access.gif)
{% endtab %}

{% tab title="View steps as pictures" %}
![Navigate to MANAGE THIRD-PARTY APP ACCESS](../.gitbook/assets/step1%20%284%29.png)
{% endtab %}
{% endtabs %}

## Step 2: Configure trusted apps

{% hint style="info" %}
Make sure you use the right app name "**LeaveMeAlone**" ****without spaces!

Check the Client ID matches the one below.
{% endhint %}

```text
229643572503-d51b5c1infuudehgdlg1q0sigjella2h.apps.googleusercontent.com
```

1. Click **Configure new app** and select **OAuth App Name Or Client ID**.
2. Enter **LeaveMeAlone** \(_without spaces_\) and click **Search**.
3. Find **LeaveMeAlone** and click **Select**. \(You might see our old logo, it will update soon\).
4. **Check the box** to select the LeaveMeAlone Client ID and click **Select**.
5. Choose **Trusted: Can access all Google services** and click **Configure**.

{% tabs %}
{% tab title="View steps in a video" %}
![](../.gitbook/assets/2-configure.gif)
{% endtab %}

{% tab title="View steps as pictures" %}
![Configure a new OAuth app](../.gitbook/assets/step2_a.png)

![Search for &quot;LeaveMeAlone&quot; and select the LeaveMeAlone app](../.gitbook/assets/step2_b%20%281%29.png)

![Check the box to select MeAlone and click Select](../.gitbook/assets/step2_c%20%281%29.png)

![Select Trusted and click Configure](../.gitbook/assets/step2_d%20%281%29.png)
{% endtab %}
{% endtabs %}

All done!

You can now sign-in to [Leave Me Alone](https://leavemealone.app/) using the Sign in with Google option.

## Troubleshooting

### App not found

If you see an error message "**App not found**" then you might be using the wrong app name.

![](../.gitbook/assets/screenshot-2021-01-14-at-12.59.58.png)

**Solution:** make sure the app name is correct and **without spaces** "LeaveMeAlone". Or you can use our Client ID to search.

```text
229643572503-d51b5c1infuudehgdlg1q0sigjella2h.apps.googleusercontent.com
```

### Still need help?

Submit a request [here](https://leavemealone.app/feedback) or email us at [support@leavemealone.app](mailto:support@leavemealone.app).

