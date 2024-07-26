# MailCarrier-master
User friendly, provider-aware, mailing platform with templates and logs included.
Design global layouts, compose your template, preview your emails and send them with your desired provider (SES, MailGun etc.) through intuitive and friendly API endpoint protected by your desired auth guard. Then, inspect them through logs.

Features
🎨 Beautiful syntax: Explore a beautiful, expressive template syntax similar to JS thanks to Twig by Symfony.
🧩 Provider aware: Bring your desired provider to send email, such as Amazon SES, MailGun, SendGrid etc.
✨ Friendly APIs: Use a friendly and well documented API endpoint to send your emails.
🔐 Secure by default: Both authentication and API endpoint are always secure: use one of the pre-built auth system or bring your own.
📎 Attachments: Upload or retrieve attachments from a remote source such S3, Spaces etc.
🪄 Hackable: MailCarrier relies on Laravel and Filament, that means that over 30K packages are available to customise your MailCarrier instance.
⏳ Queues: You can choose whether or not to send emails in a enqueued, background jobs, to not block the user experience.
