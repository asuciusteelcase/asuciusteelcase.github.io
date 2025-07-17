<html>
  <body>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DO500000YIWgz',
				'MIAW_for_GitHub_Test',
				'https://steelcase--newsfchat.sandbox.my.site.com/ESWMIAWforGitHubTest1752751523827',
				{
					scrt2URL: 'https://steelcase--newsfchat.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://steelcase--newsfchat.sandbox.my.site.com/ESWMIAWforGitHubTest1752751523827/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
</body>
</html>
