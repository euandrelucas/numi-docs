# Privacy Policy — Numi

**Last updated:** June 28, 2026

This Privacy Policy explains what data the **Numi** bot collects, why it is collected, and how you can delete it.

## 1. What data we collect

| Data                                                              | Purpose                                                                         | When                                                        |
| ----------------------------------------------------------------- | ------------------------------------------------------------------------------- | ----------------------------------------------------------- |
| Your Discord ID                                                   | Identify your account and your Numi                                             | When you mention the bot or use any command                 |
| Language (locale)                                                 | Respond in the correct language                                                 | Automatically detected or selected in Settings              |
| Your Numi data (name, level, EXP, stats, items, coins)            | Game functionality                                                              | Every time you perform an action (feed, bathe, play, etc.)  |
| Notification preferences                                          | Determine whether we may send you DMs                                           | Bot Settings                                                |
| CPF/CNPJ                                                          | Required by our payment provider to issue invoices, only if you make a purchase | During a purchase or subscription                           |
| Payment history (excluding card information)                      | Grant purchased benefits and process refund requests                            | During a purchase or subscription                           |
| Anonymous usage events (e.g., "command executed", "Numi hatched") | Understand feature usage and improve the bot                                    | Continuously via Mixpanel — no message content is collected |

We do **not** read or store the content of messages in your server. We only process the `@Numi` mention that opens the bot, along with the command and button interactions that you initiate.

## 2. Where your data is stored

* **Game data** (Numi, coins, items): Stored in our own PostgreSQL database, hosted by the developer.
* **Payments:** Processed by Asaas (a third-party payment provider). Data processed through Asaas is subject to their Privacy Policy.
* **Usage events:** Stored in Mixpanel (if analytics collection is enabled).

## 3. Who we share your data with

We do **not** sell or share your data with third parties for marketing purposes.

We only share the minimum necessary information with:

* **Asaas**, for payment processing, only if you make a purchase.
* **Mixpanel**, for aggregated usage analytics, without payment information or CPF.

## 4. How to delete your data

In **Settings → Delete Account**, within the bot itself, you can permanently delete your account, your Numi, and all associated progress. Deletion from our primary database is immediate.

For fraud prevention and payment chargeback auditing, we retain a temporary backup of deleted data for a limited period. To request the removal of this backup as well, please contact the developer through the Numi support server.

## 5. Your rights

At any time, you may:

* View your current data with `/numi status`.
* Change your language and notification preferences in **Settings**.
* Delete your account and data (see Section 4).

## 6. Contact

If you have questions about privacy or requests regarding your data, please contact us through the Numi support server or send a direct message to the developer on Discord.

See also our [Terms of Service](./terms-of-service.md).
