<html>
  <body>
    <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DD4000000HsJ5',
				'MIAW_BOt',
				'https://sonyhondamobility01--devpro1.sandbox.my.site.com/ESWMIAWBOt1712677727186',
				{
					scrt2URL: 'https://sonyhondamobility01--devpro1.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://sonyhondamobility01--devpro1.sandbox.my.site.com/ESWMIAWBOt1712677727186/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>


  </body>
</html>
