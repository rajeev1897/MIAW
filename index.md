<html>
  <body>
    
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'
window.addEventListener("onEmbeddedMessagingReady", () => {            
				console.log( "Inside Prechat API!!" );
			embeddedservice_bootstrap.prechatAPI.setHiddenPrechatFields( { "Claimant_Number" : "7654321","First_Name" : "Alex","Last_Name" : "Test1","Middle_Initial" : "H" } );
			});
			embeddedservice_bootstrap.init(
				'00D3S0000009roe',
				'Janet_In_git',
				'https://nmdws--tigerchat.sandbox.my.site.com/ESWJanetIngit1718263212306',
				{
					scrt2URL: 'https://nmdws--tigerchat.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://nmdws--tigerchat.sandbox.my.site.com/ESWJanetIngit1718263212306/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

  </body>
</html>
