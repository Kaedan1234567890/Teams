# Teams 2.5 Alpha 4 — Chat prefix compatibility

- Public chat is no longer intercepted by Allied: Styled Chat can format the username without an extra team tag.
- Private /teams tm remains intercepted and delivered to teammates.
- Use the existing Placeholder API token `%allied:team_prefix%` once at the front of your Styled Chat player-chat format, before the name token.
- Do not add a second team prefix to the same format.
- Tag colour is provided by the team's saved `tagColor`; usernames keep the Styled Chat theme.
- No team data migrations. ZIP source only; NOT compiled/tested.
