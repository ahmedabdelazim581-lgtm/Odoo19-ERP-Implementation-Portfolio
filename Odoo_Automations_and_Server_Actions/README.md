Odoo 19 Technical Customizations & Automations
This folder showcases the capability to extend Odoo's standard functionality using Server Actions and Python code to enforce strict business rules:
Sales Discount Control Rule:** A Python script triggered on `Sales Order Line` update that restricts specific users from granting a discount higher than 10%, raising a native `UserError` to enforce internal company policies.
Data Mapping & Live Notifications:** An automated server action on `Sales Order` to map custom studio fields dynamically while triggering live client-side sticky notifications (`display_notification`) to enhance UX.
