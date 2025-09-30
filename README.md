<html lang="en-US">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <img src = "DTE_Bank_wxO.png"
    	width="auto" height="1200"
         alt = "New Watson Assistant Bank" />

</head>
<script>
  window.watsonAssistantChatOptions = {
  integrationID: "b095c428-6a2f-4e54-beab-e57046599257", // The ID of this integration.
  region: "wxo-us-south", // The region your integration is hosted in.
  serviceInstanceID: "54254974-2e9f-4b4a-983e-1f3b2dbc8092", // The ID of your service instance.
  orchestrateUIAgentExtensions: false, // If you wish to enable optional UI Agent extensions.
  onLoad: async (instance) => { await instance.render(); }
};
  setTimeout(function(){
    const t=document.createElement('script');
    t.src="https://web-chat.global.assistant.watson.appdomain.cloud/versions/" + (window.watsonAssistantChatOptions.clientVersion || 'latest') + "/WatsonAssistantChatEntry.js";
    document.head.appendChild(t);
  });
</script>

<body></body>

</html>
