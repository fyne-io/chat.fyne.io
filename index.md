---
layout: default
---

<script src='https://meet.jit.si/external_api.js'></script>
<div id="meet"></div>

<script>
const domain = 'meet.jit.si';
const options = {
    roomName: 'FyneChat',
    width: '100%',
    height: '480pt',
    parentNode: document.querySelector('#meet')
};
const api = new JitsiMeetExternalAPI(domain, options);
</script>

