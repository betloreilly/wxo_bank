<!DOCTYPE html>
<html lang="en-US">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Watson Assistant Bank</title>
</head>
<body>
  <script>
    window.watsonAssistantChatOptions = {
      integrationID: "b095c428-6a2f-4e54-beab-e57046599257",
      region: "wxo-us-south",
      serviceInstanceID: "54254974-2e9f-4b4a-983e-1f3b2dbc8092",
      orchestrateUIAgentExtensions: false,
      onLoad: async (instance) => { await instance.render(); }
    };
    setTimeout(function(){
      const t=document.createElement('script');
      t.src="https://web-chat.global.assistant.watson.appdomain.cloud/versions/" 
          + (window.watsonAssistantChatOptions.clientVersion || 'latest') 
          + "/WatsonAssistantChatEntry.js";
      document.head.appendChild(t);
    });
  </script>
</body>
</html>
