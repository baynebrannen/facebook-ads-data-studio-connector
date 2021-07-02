# facebook-ads-data-studio-connector
A Google Data Studio connector for Facebook Ads data

You will need to do a few things in preparation for using this code.

1. Obtain a Facebook API token with the proper permissions from the Facebook Graph API. You will want to get a "long-lived" access token: https://developers.facebook.com/docs/facebook-login/access-tokens/refreshing
2. Get your Facebook ad account id: https://www.facebook.com/business/help/1492627900875762
3. Add these into the proper spaces in the code. It is in the comments, but the token should be added where it says "YOUR-ACCESS-TOKEN" and the ad account id should be added after the "act_" where the X's are
IMPORTANT NOTE: MAKE SURE THAT THIS ACCESS TOKEN AND THE CODE CONTAINING IT IS NOT AVAILABLE TO ANYONE ELSE. YOUR ADS ACCOUNT WILL BE DESTROYED BY HACKERS IF YOU DO. I AM NOT RESPONSIBLE FOR THAT IF IT HAPPENS TO YOU.
4. Put this script into Google Apps Script and save it.
5. Put together the manifest for your organization: https://developers.google.com/datastudio/connector/build
6. Deploy the community connector to your specific dashboard: https://developers.google.com/datastudio/connector/deploy

This is a little bit of work, but trust me when I say it's not as much work as creating this connector!
