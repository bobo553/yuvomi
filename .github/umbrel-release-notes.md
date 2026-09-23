<!-- version: 2.69.0 -->
This release brings a nutrition log to Health, keeps you signed in for longer, and makes restoring a backup safer. It also closes several places where a household member could see or change data that their module rights did not allow, so updating is recommended.

Health has a new Nutrition tab: a daily target per person and a log of what was eaten, with an optional dashboard tile. The dashboard can also show a fasting timer. Inventory items can have recurring dates, a service history and, for vehicles, an odometer. Rewards can say how many of them the household has, a recipe ingredient can be linked to the pantry row it means, and a payment recorded in shared expenses can now be reversed.

You now stay signed in as long as you open Yuvomi at least once every 90 days, and you can sign out your other devices from your account settings. Existing sign-ins move to the new rule on their next visit.

A restore now swaps the database in as a whole and checks every page of the backup first, so an interrupted restore no longer leaves a broken database behind and a damaged backup is refused. A backup from another installation can be restored from the settings page by entering its key.

Documents attached to calendar events, receipts on budget entries and inventory items, pantry and shopping transfers and shared-expense member lists now all follow the documents and module rights of the person looking. Many smaller fixes cover read-only members, reminders on synced appointments, calendar colours and accessibility.

The database is updated automatically on the first start after the update. It adds a few tables and columns and can rebuild shared-expense bookings that an earlier account deletion removed, so the first start may take a little longer than usual. Taking a backup before updating is a good idea.

Full release notes are available at https://github.com/ulsklyc/yuvomi/releases/tag/v2.69.0
