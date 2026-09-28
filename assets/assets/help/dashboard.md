# Dashboard Help

The dashboard shows current booking status counts for a selected UK calendar day.

- **Jobs** uses the service date. Scheduled is Booked + In Progress + Completed + Exception. Refunds are shown separately.
- **Orders** uses the booking creation date in UK time. Confirmed is Booked + In Progress + Completed + Exception. Pending Payment, Cancelled, and Refunds complete the order total.
- **Needs Follow-up** uses today in UK time, even when a different dashboard date is selected. It lists overdue work, pending refunds, and unresolved exceptions. When opened from a Reports period, these lists are scoped to that period’s service dates so the pending count matches the report.

Use the arrows to change the date or **Today** to return to the current UK day. Select a count or calendar table cell to open the matching booking list. Select a booking number in Needs Follow-up to open its details. Use **Revenue & refunds → Stripe** for financial figures; this dashboard contains booking counts only.

Counts for older dates use each booking's current status, so they may change when a booking progresses or is refunded.
