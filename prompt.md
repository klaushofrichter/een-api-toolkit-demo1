We are building a Vue 3 web app that accesses the EEN Video Platform by using the
een-api-toolkit (npm install een-api-toolkit@latest) and list up to 9 cameras for that user
in a 3x3 grid with a live preview image on the camera card. There is pagination when there
are more than 9 cameras aavailable. When clicking on a card, a modal window is shown with
a live main video feed from that camera.

Refer to https://github.com/klaushofrichter/een-api-toolkit/blob/develop/docs/AI-CONTEXT.md
for more information about the een-api-toolkit. 

Use these configuration details:
* VITE_EEN_CLIENT_ID="PREVIEW-KLAUS-MOBILE"
* VITE_PROXY_URL=http://localhost:8787
