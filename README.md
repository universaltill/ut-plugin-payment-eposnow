# ut-plugin-payment-eposnow

**Status: not built. No integration exists** (research 2026-10-25, [ut-docs#5027](https://github.com/universaltill/ut-docs/issues/5027)).

Epos Now publishes no API to start a card payment on its terminals. Recording a sale and tender into Epos Now is plausible through its REST API, but that is the sale-push sync of [ut-docs#4426](https://github.com/universaltill/ut-docs/issues/4426) (card #4434, in `ut-plugin-import-eposnow`), not a payment plugin. For card payments use `ut-plugin-payment-sumup` or `ut-plugin-payment-stripe`.

Nothing here connects to any Epos Now account.
