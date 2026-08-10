# Oblsk_notifications Plugin

## Description
The reference notification UI, a Vue global element listening for
core:client:notification-show and rendering a toast-style stack. Talks to
NotificationService (server and client, both in core, unchanged). Fully
swappable: replace this plugin with your own to change how notifications
look, remove it entirely and provide your own global element named
"notifications" instead.

## Installation
This plugin loads as part of the `core` resource. After adding it under
`plugins/`, run `obelisk registry:generate` from `core/` on the host, then
restart `core` (or the whole server).
