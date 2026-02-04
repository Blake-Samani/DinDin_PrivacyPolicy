<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>DinDin - Privacy Policy</title>
  <style>
    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
      max-width: 720px;
      margin: 0 auto;
      padding: 24px 16px;
      line-height: 1.6;
      color: #333;
    }
    h1 { color: #FF5722; }
    h2 { color: #444; margin-top: 2em; }
    ul { padding-left: 1.5em; }
    a { color: #FF5722; }
  </style>
</head>
<body>

<h1>DinDin Privacy Policy</h1>
<p><strong>Effective Date:</strong> February 3, 2026</p>

<p>DinDin ("we", "our", "us") operates the DinDin mobile application. This Privacy Policy explains what information we collect, how we use it, and your choices regarding your data.</p>

<h2>1. Information We Collect</h2>

<h3>Account Information</h3>
<ul>
  <li>Email address</li>
  <li>Password (stored securely via AWS Cognito; we never have access to your plaintext password)</li>
  <li>Account role (consumer or restaurant owner)</li>
</ul>

<h3>Google Sign-In</h3>
<p>If you sign in with Google, we receive your email address and basic profile information (name) from Google. We do not receive your Google password.</p>

<h3>Restaurant Owner Information</h3>
<p>If you register as a restaurant owner, we collect:</p>
<ul>
  <li>Restaurant name, phone number, and website</li>
  <li>Restaurant address and geographic coordinates (latitude/longitude)</li>
  <li>Dish information: names, descriptions, cuisine type, food type, prices, and photos</li>
</ul>

<h3>Location Data</h3>
<p>We request location permission only for restaurant owners who choose to auto-fill their restaurant address using their device's GPS. Location is collected once at that time and is not continuously tracked. Consumers are never asked for location access.</p>

<h3>Usage Data</h3>
<ul>
  <li>Swipe history (likes, passes, and dislikes on dishes)</li>
  <li>Saved favorites</li>
  <li>Last active timestamp (to understand general app usage patterns)</li>
</ul>

<h3>Photos</h3>
<p>Restaurant owners may upload photos of their dishes from their device's photo library. These images are stored on our servers and displayed to consumers in the app.</p>

<h2>2. How We Use Your Information</h2>
<ul>
  <li><strong>To provide the service:</strong> Showing you dishes, saving your preferences, and displaying restaurant information.</li>
  <li><strong>To personalize your feed:</strong> Using your swipe history to avoid showing you dishes you've already seen or disliked.</li>
  <li><strong>To provide analytics to restaurant owners:</strong> Aggregate like and pass counts on their dishes (owners cannot see which individual users swiped).</li>
  <li><strong>To communicate with you:</strong> Sending verification emails during sign-up and notifications related to your account.</li>
</ul>

<h2>3. Data Sharing</h2>
<p>We do <strong>not</strong> sell your personal information to third parties.</p>
<p>We share data only with the following service providers that help us operate the app:</p>
<ul>
  <li><strong>Amazon Web Services (AWS):</strong> Our infrastructure provider. All data is stored and processed using AWS services including Cognito (authentication), DynamoDB (database), S3 (image storage), and Lambda (application logic).</li>
  <li><strong>Google:</strong> Only if you use Google Sign-In, to authenticate your identity.</li>
</ul>
<p>We do not use any third-party analytics, advertising, or tracking services.</p>

<h2>4. Data Retention</h2>
<ul>
  <li><strong>Account data:</strong> Retained as long as your account is active.</li>
  <li><strong>Passed dishes:</strong> Swipe records for dishes you pass on are automatically deleted after 7 days, allowing those dishes to reappear in your feed.</li>
  <li><strong>Liked and disliked dishes:</strong> These records are kept until you delete your account.</li>
  <li><strong>Restaurant and dish data:</strong> Retained as long as the restaurant owner's account is active.</li>
</ul>

<h2>5. Data Security</h2>
<p>All data is transmitted over HTTPS. Passwords are securely hashed and managed by AWS Cognito. Authentication tokens are stored locally on your device using your operating system's standard secure storage.</p>

<h2>6. Your Rights and Choices</h2>
<ul>
  <li><strong>Access:</strong> You can view your account information and saved favorites within the app.</li>
  <li><strong>Deletion:</strong> You may request deletion of your account and all associated data by contacting us at the email below. Upon deletion, all your personal data, swipe history, favorites, and any restaurant/dish data you own will be permanently removed.</li>
  <li><strong>Location:</strong> You can deny or revoke location permission at any time through your device settings. The app will continue to function; you will simply need to enter your restaurant address manually.</li>
  <li><strong>Photos:</strong> You can deny photo library access through your device settings. You will still be able to use the app but cannot upload dish images.</li>
</ul>

<h2>7. Delete Your Account</h2>
<p>You can request deletion of your DinDin account and all associated data by following these steps:</p>
<ol>
  <li>Send an email to <a href="mailto:blake1.samani@gmail.com?subject=DinDin%20Account%20Deletion%20Request">blake1.samani@gmail.com</a> with the subject line <strong>"DinDin Account Deletion Request"</strong>.</li>
  <li>Include the email address associated with your DinDin account.</li>
  <li>We will process your request and confirm deletion within 30 days.</li>
</ol>

<h3>What gets deleted:</h3>
<ul>
  <li>Your account and login credentials</li>
  <li>Your swipe history (likes, passes, and dislikes)</li>
  <li>Your saved favorites</li>
  <li>Your usage data and activity timestamps</li>
  <li>If you are a restaurant owner: your restaurant profile, all dish listings, and all uploaded dish photos</li>
</ul>

<h3>What is not retained:</h3>
<p>No personal data is kept after deletion. Aggregate, anonymous analytics (e.g., total like counts on dishes) that cannot be linked back to your identity may remain.</p>

<h2>8. Children's Privacy</h2>
<p>DinDin is not directed at children under the age of 13. We do not knowingly collect personal information from children under 13. If you believe a child under 13 has provided us with personal information, please contact us and we will promptly delete it.</p>

<h2>9. Changes to This Policy</h2>
<p>We may update this Privacy Policy from time to time. We will notify you of material changes by updating the "Effective Date" at the top of this page. Continued use of the app after changes constitutes acceptance of the updated policy.</p>

<h2>10. Contact Us</h2>
<p>If you have questions about this Privacy Policy or wish to exercise your data rights, contact us at:</p>
<p><a href="mailto:blake1.samani@gmail.com">privacy@dindin.app</a></p>

</body>
</html>
