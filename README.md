# VIP Jetpack Sync Cron
This drop-in plugin ensures that Jetpack only syncs on the dedicated cron task, as Jetpack Sync piggybacks on various cron/API requests causing slowdowns on the shutdown hook.
