<script>
    window.addEventListener(
        "onEmbeddedMessagingReady", () => {
            console.log(
                'Inside Messaging Ready Block'
            );
            let userId = '';
            console.log(
                'User Id is',
                userId
            );
            embeddedservice_bootstrap.prechatAPI.setHiddenPrechatFields( {
                'User_Id' : userId
            } );
        }
    );
  </script>
