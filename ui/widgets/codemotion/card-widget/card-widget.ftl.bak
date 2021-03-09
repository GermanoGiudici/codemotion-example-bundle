<#assign wp=JspTaglibs["/aps-core"]>

<div id="codemotion-card-widget"></div>

<script nonce="<@wp.cspNonce />">
    System.import('single-spa').then(function (singleSpa) {
        System.import('codemotion-card-widget').then(parcel=>{
            const domElement = document.getElementById('codemotion-card-widget');
            const parcelProps = {domElement, url: '/germanogiudici/codemotion-bff/0-0-1-snapshot/api/metrics'};
            singleSpa.mountRootParcel(parcel, parcelProps);
        })

        singleSpa.start();
    });
</script>
