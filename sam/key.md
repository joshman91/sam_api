---
layout: default
title: Request an API Key
nav: key
---

Sign up for an application programming interface (API) key to access and use web services available on the Data.gov developer network. Of note, we are transitioning to include an email verification step for API key sign up. All API keys used to access SAM APIs must have a verified email address associated no later than Friday, November 17, 2017. 

{% raw %}
<div id="apidatagov_signup">Loading signup form...</div>
<script type="text/javascript">
  /* * * CONFIGURATION VARIABLES: EDIT BEFORE PASTING INTO YOUR WEBPAGE * * */
  var apiUmbrellaSignupOptions = {
    registrationSource: 'gsa-sam',
    apiKey: '2cnHYrvWoVvKnV7BahvMvxOWa8z4RHx9K7MtkS5G',
    exampleApiUrl: 'https://api.data.gov/sam/v1/registrations/1459697830000?api_key={{api_key}}',
    contactUrl: 'https://github.com/GSA/GSA-APIs/issues',
    siteName: 'SAM.gov',
    emailFromName: 'SAM.gov Developer Hub',
    verifyEmail: true
  };

  /* * * DON'T EDIT BELOW THIS LINE * * */
  (function() {
    var apiUmbrella = document.createElement('script'); apiUmbrella.type = 'text/javascript'; apiUmbrella.async = true;
    apiUmbrella.src = 'https://api.data.gov/static/javascripts/signup_embed.js';
    (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(apiUmbrella);
  })();
</script>
<noscript>Please enable JavaScript to signup for an <a href="http://api.data.gov/">api.data.gov</a> API key.</noscript>
{% endraw %}
