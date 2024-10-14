# figma-discord-webhook
 Figma - Discord 간 코멘트 / 배포 알리미
## How to use
 1. Fork to your org
 2. Add new Vercel project
 3. Set Environment variables
    - Discord Webhook URL
    - Figma API(Personal) Token
    - Project Name
    - Endpoint of Comment event
    - Endpoint of Version update event
    - Replace words (Optional)
 6. POST two Figma Webhooks (Set event_type "FILE_COMMENT" "FILE_VERSION_UPDATE" each.
    - https://www.figma.com/developers/api#webhooks-v2-endpoints
 7. Publish Vercel on Product level.
