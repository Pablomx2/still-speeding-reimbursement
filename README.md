# Still Speeding — Expense Reimbursement

A single-file, mobile-first fillable reimbursement form for Still Speeding LLC's
accountable plan. No build step, no backend — open it in a browser and fill it out.

- **[Open the form](https://pablomx2.github.io/still-speeding-reimbursement/)**
- Autosaves your draft to the device you're using (localStorage) as you type
- Add/remove expense line items with a live running total
- **Save** keeps a finished request in the browser; **History** lists everything you've
  kept, so you can open, duplicate, or delete a past request
- **Presets** — tap ☆ on any expense line to keep it as a one-tap chip
  (e.g. "Gas fill-up — Shell — $48.20")
- **Automatic dates** — today's date is filled in for you, the reimbursement period
  is derived from your expense dates ("August 2026", "Q2 2026"), and signature dates
  stamp themselves when you sign. Typing over any of them turns the automation off
- **Automatic categories** — categories are picked from the vendor and description,
  and the form learns from your own past lines
- **Suggestions** — descriptions, vendors, and payment methods you've used before are
  offered as you type, and a "Last time" chip fills the rest of a line from the last
  matching entry
- **Save these details as my defaults** remembers your name, position, company, and
  reimbursement method for every new request
- **Save PDF** builds a clean, document-styled printout (not a screenshot of the form)
- **Download backup / Restore backup** exports your draft *plus* saved requests,
  presets, and learned suggestions as a `.json` file — a safety net, or a way to move
  everything to another device
- Add it to your phone's home screen for a full-screen, app-like launch

No data is sent anywhere — saved requests, presets, and suggestions live only in that
browser on that device, until you print or export a backup file yourself.
