<script>
    window.addEventListener(
        "onEmbeddedMessagingReady", () => {
            console.log(
                'Inside Messaging Ready Block'
            );
            let userId = $A.get(
                '$SObjectType.CurrentUser.Id'
            );
            console.log(
                'User Id is',
                userId
            );
            embeddedservice_bootstrap.prechatAPI.setHiddenPrechatFields( {
                'User_Id' : 'af1287254218'
            } );
        }
    );
</script>
