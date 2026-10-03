# Dashboard Help

Use the arrows to select a UK calendar day or **Today** to return to the current day. **Refresh** recalculates the page; there is no automatic refresh. **Data as of** shows when the numbers were calculated in UK time.

- **Jobs** uses the selected service date. Scheduled is Booked + In Progress + Completed + Exception.
- **Coming up jobs** shows scheduled jobs for UK today, tomorrow and the following day, regardless of the selected date.
- **Shift cover** shows this week and the next two weeks, Monday to Sunday. Calendars appear when any week has fewer than four registered shifts; AM, PM and Eve each count as one shift. The table disappears when every calendar has enough shifts. Select **Open Schedules** to arrange cover.
- **Orders** uses the selected booking creation date. New orders is Confirmed + Cancelled + Refunds. Confirmed is Booked + In Progress + Completed + Exception; Refunds is Pending Refund + Refunded.
- **Checkouts** shows Pending Payment and Discarded separately from New orders.
- **Needs Follow-up** lists Unresolved Exception, Pending Refund and Overdue in that order, with the oldest first. An exceptional Discarded Payment Refunds queue appears when a late captured payment needs review. Empty lists are hidden.

Select an entire metric card to open its matching booking list, paginated at 50 rows per page. Calendar tables show counts without links. Select a booking number to open its details. Calendar names are shown as **C#id · full name**.

Follow-up uses UK today, independently of the selected date. When opened from Reports, follow-up is restricted to that period's service dates. Older dates use the latest booking status. A cancellation or refund moves a paid order between categories without reducing New orders.

Use **Revenue & refunds → Stripe** for financial figures. This dashboard shows no monetary amounts.
