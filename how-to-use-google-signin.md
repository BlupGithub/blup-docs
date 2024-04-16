# How To Use Google SignIn in Blup

<figure><img src=".gitbook/assets/google-singin-.gif" alt="Google SignIn"><figcaption><p>Google SignIn</p></figcaption></figure>

To integrate Google Sign-In into your app, follow these steps:

1. **Create a UI**: Design a user interface (UI) where you want to incorporate the Google Sign-In button. This UI should include a button or any other widget to trigger the sign-in process.

2. **Implement Logic**: In the logic of the widget associated with the UI, add the Social Login can select the Google in it.

3. **Trigger Google Sign-In**: On the click event of the button or widget in your UI, trigger the Google Sign-In process. This can be done by calling the appropriate method provided by the Google Sign-In SDK.

4. **On Setting**: On Social login setting you need to add google-services.json for connecting to the google services so that you can signin with google.

5. **Navigate to Google Sign-In**: When the user triggers the sign-in process, navigate to the Google Sign-In screen or flow. This is typically handled by the Google Sign-In SDK, which provides a standard sign-in interface that users are familiar with.


6. **Auto Save User**: After successful sign-in, you can optionally save the user's information, such as their email or profile picture, for future use. This can be done using local storage or by sending the user data to the backend for storage.

{% hint style="info" %}
<mark style="color:blue;">Note: To know how to get google-services.json [Click Here](https://support.google.com/firebase/answer/7015592?hl=en#zippy=%2Cin-this-article).</mark>
{% endhint %}

If you have any ideas to make Blup better you can share them through our [Discord community channel ](https://discord.com/channels/940632966093234176/965313562425823303)

## Music to go with.
 
<div class="container">
  {% tab title="Music" %}
  {% embed url="https://open.spotify.com/playlist/0vvXsWCC9xrXsKd4FyS8kM?si=2c7f55bd3f944878" %}
  Lofi music
  {% endembed %}
  {% endtab %}
  {% endtabs %}
</div>